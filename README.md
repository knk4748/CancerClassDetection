# CancerClassDetection
Real Datasets for Cancer Class Analysis
### Data description from Kaggle
[Link to Kaggle Dataset](https://www.kaggle.com/c/msk-redefining-cancer-treatment)    
A lot has been said during the past several years about how precision medicine and, more concretely, how genetic testing is going to disrupt the way diseases like cancer are treated.  
But this is only partially happening due to the huge amount of manual work still required. Memorial Sloan Kettering Cancer Center (MSKCC) launched this competition, accepted by the NIPS 2017 Competition Track,  because we need your help to take personalized medicine to its full potential.  
Once sequenced, a cancer tumor can have thousands of genetic mutations. But the challenge is distinguishing the mutations that contribute to tumor growth (drivers) from the neutral mutations (passengers).  
Currently this interpretation of genetic mutations is being done manually. This is a very time-consuming task where a clinical pathologist has to manually review and classify every single genetic mutation based on evidence from text-based clinical literature.  
For this competition MSKCC is making available an expert-annotated knowledge base where world-class researchers and oncologists have manually annotated thousands of mutations.  
We need your help to develop a Machine Learning algorithm that, using this knowledge base as a baseline, automatically classifies genetic variations.  
Kaggle is excited to partner with research groups to push forward the frontier of machine learning. Research competitions make use of Kaggle's platform and experience, but are largely organized by the research group's data science team. Any questions or concerns regarding the competition data, quality, or topic will be addressed by them.  



## DataDescription
Output Classes : `9 Classes`  
Variables->
- ID
- Gene
- Variant
- Associated Research paper

> Goal was to achieve minimum [Log_Loss](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.log_loss.html#:~:text=Log%20loss%2C%20aka%20logistic%20loss,for%20its%20training%20data%20y_true%20.)


## My approach
> Play with data to get insights
> Built a Random model for reference of Log loss
> Checking dependencies of each Column individually to Output Class
> Built preprocessing function
> Tryout various models for best LogLoss based results
> Retain model with minimum LogLoss 

# Concluding 
Got best LogLoss results with LR model using oneHotencoded model with balanced weights.

#### EXTRAS
We had compromised accuracy at certain points to retain better Log Loss.  
 **Model selection would have been different if model was to achieve other metrics** 










