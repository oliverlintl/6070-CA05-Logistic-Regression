# 6070-CA05-Logistic-Regression

## Objective: 
In this project, we use logistic regression to predict whether or not a patient has risk of cardiovascular disease. 

## Data:
The data has 3242 entries and 17 columns. The variable we are trying to predict is cvd_4types

## Model building
In this project, we train multiple different model based on different sample selection techinque, feature selection and hyperparameter tuning. After EDA, we can see an unbalance in our sample dataset. So there is a need for under or over sampling.

### Model 0:
Without balancing the dataset, we jump straight into training a logistic regression

### Model 1: 
Train logistic regression after under-sampling the positive cases to balance dataset.

### Model 2:
Train logistic regression after using the SMOTE technique to over sample the negative cases to balance the dataset.

### Model 3:
Improve logistic regression using RFE techique for feature selection. 
