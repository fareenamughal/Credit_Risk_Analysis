# Credit_Risk_Analysis
 Module 18: Supervised Machine Learning and Credit Risk

___
 
## Overview
___

The purpose of this analysis was to evaluate the credit worthiness or credit risk of customers. We use different machine learning models to try and predict the credit risk and to determine which model is best suited for evaluating credit risk. 

The models used are as follows:
  - Naïve Random Oversampling
  - SMOTE Oversampling
  - Cluster Centroids Undersampling
  - SMOTEENN combination sampling
  - Balanced Random Forest Classifier
  - Easy Ensemble AdaBoost Classifier

#### Resources

 - Data source is the LoanStats_2019Q1.csv
 - Software is jupyter notebook using python
 
 - Links to the two python/jupyter notebook are as below:
 - 1. [Credit risk resampling](https://github.com/fareenamughal/Credit_Risk_Analysis/blob/9572130066ecb1663b31987e0c363a75c9e5cfd9/credit_risk_resampling.ipynb)
 - 2. [Credit risk ensemble](https://github.com/fareenamughal/Credit_Risk_Analysis/blob/9572130066ecb1663b31987e0c363a75c9e5cfd9/credit_risk_ensemble.ipynb)
___

## Results 

___
### 1. Naïve Random Oversampling 

The balanced accuracy score is 65%, precision is 1% and sensitivity is 61% for the high risk class. Overall sensitivity/recall is 61% and F1 score is 81%.


![Naive Random Oversampling](https://github.com/fareenamughal/Credit_Risk_Analysis/blob/9572130066ecb1663b31987e0c363a75c9e5cfd9/Resources/1.Naive%20Random%20Oversampling.png)

### 2. SMOTE Oversampling

The balanced accuracy score is 62%, precision is 1% and sensitivity is 61% for the high risk class. Overall sensitivity/recall is 64% and F1 score is 77%.

![SMOTE Oversampling](https://github.com/fareenamughal/Credit_Risk_Analysis/blob/78e650898acf73827d66dbcd72c5c2d925796e86/Resources/2.%20SMOTE%20Oversampling.png)


### 3. Cluster Centroids Undersampling

The balanced accuracy score is 51%, precision is 1% and sensitivity is 57% for the high risk class. Overall sensitivity/recall is 46% and F1 score is 62%.

![CLuster Centroids Undersampling](https://github.com/fareenamughal/Credit_Risk_Analysis/blob/78e650898acf73827d66dbcd72c5c2d925796e86/Resources/3.%20Cluster%20Centroids%20Undersampling.png)

### 4. SMOTEENN combination sampling 

The balanced accuracy score is 51%, precision is 1% and sensitivity is 57% for the high risk class. Overall sensitivity/recall is 46% and F1 score is 62%.


![SMOTEENN combination sampling](https://github.com/fareenamughal/Credit_Risk_Analysis/blob/96bd572d51f0b32a096e4907f0a792d6ea01605a/Resources/4.%20SMOTEENN%20combination%20sampling.png)

### 5. Balanced Random Forest Classifier

The balanced accuracy score is 79%, precision is 4% and sensitivity is 67% for the high risk class. Overall sensitivity/recall is 91% and F1 score is 95%.


![Balanced Random Forest Classifier](https://github.com/fareenamughal/Credit_Risk_Analysis/blob/96bd572d51f0b32a096e4907f0a792d6ea01605a/Resources/5.%20Balanced%20Random%20Forest%20Classifier.png)

![Balanced Random Forest Classifier Feature Importance](https://github.com/fareenamughal/Credit_Risk_Analysis/blob/18ac71dcbc9957adf12f5ef5f3de295c33cd0798/Resources/5.%20Balanced%20Random%20Forest%20Classifier-Feature%20importance%20.png)


### 6. Easy Ensemble AdaBoost Classifier

The balanced accuracy score is 93%, precision is 7% and sensitivity is 91% for the high risk class. Overall sensitivity/recall is 94% and F1 score is 97%.

![Easy Ensemble AdaBoost Classifier](https://github.com/fareenamughal/Credit_Risk_Analysis/blob/96bd572d51f0b32a096e4907f0a792d6ea01605a/Resources/6.%20Easy%20Ensemble%20AdaBoost%20Classifier.png)

___

## Summary

___

![Summary of the results](https://github.com/fareenamughal/Credit_Risk_Analysis/blob/2e39953a07a5ae3bbf89a74ba99444ae1effbef6/Resources/SUMMARY%20OF%20THE%20OUTCOMES%20OF%20VARIOUS%20MACHINE%20LEARNING%20MODELS%20.png)
