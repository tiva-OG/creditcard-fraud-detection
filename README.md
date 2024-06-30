Credit-Card Fraud Detection
===========================

Overview:
---------

This is a project on creating a fraud detection system. It engulfs the whole line of ML development except for data collection and model deployment. 
Data used here is the **[creditcard](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)** data from kaggle. This data is a highly unbalanced dataset 
containing *anonymized credit-card transactions labeled as fraudulent or genuine*.
>The project lifecycle encompasses:
**~~Data Collection~~ >>> Exploratory Data Analysis >>> Feature Engineering >>> Modeling >>> Evaluation >>> ~~Deployment~~**

Notebooks:
----------

###### 1. exploratory_data_analysis.ipynb:
> In this notebook, I read and explored the data, trying to find some insights by visualizing relationships and statistics. 
> I used the `seaborn` and `matplotlib` libraries to visualize the correlation between features and create plots like the _scatter-plot_ and _kde-plot_.
###### 2. feature_engineering.ipynb:
> I carried out the data preprocessing in this notebook. Some tasks I completed are:
> - feature selection
> - handling data imbalance
> - scaling & standardization 
> - treating outliers
###### 3. modeling_&_finetuning.ipynb:
> This notebook contains the model _training_, _fine-tuning_, and _evaluation_.
> Some metrics I found helpful considering the nature of the data and also the problem statement
> are the `roc_auc`, `average_precision`, and `f1` scores 

Disclaimer:
-----------

This application is developed for educational purposes and may contain bugs. Use it at personal risk.

For any questions or issues, please contact [me](salvationtiva@gmail.com)