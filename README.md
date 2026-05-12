# Titanic-Survival-Prediction-ML-Project-classification-
**OVERVIEW**

This project uses the Titanic dataset to build a machine learning model that predicts whether a passenger survived the Titanic disaster or not.
It is a binary classification problem, where the goal is to classify passengers into:
0:Did not survive
1:Survived

**OBJECTIVE**

To analyze passenger data and build a model that can accurately predict survival based on features such as:
Age
Sex
Passenger class
Fare
**DATASET FEATURES**

Pclass – Ticket class (1st, 2nd, 3rd)
Sex – Gender of passenger
Age – Age of passenger
Fare – Ticket fare
SibSp – Number of siblings/spouses aboard
Parch – Number of parents/children aboard
Embarked – Port of embarkation (C, Q, S)

**Machine Learning Workflow**

1.Data preprocessing
    Handling missing values 
    Feature engineering
    Encoding categorical variables
    One-Hot Encoding
    Train-test split
2.Model training
    Random Forest Classifier
3.Evaluation
    Accuracy score
    
**Model Used**

Random Forest Classifier
Achieved accuracy: 81%

**Feature Importance**

The most important features in predicting survival were:
Fare
Age
Sex
These features had the strongest impact on the model’s decisions.
