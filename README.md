# Titanic Survival Prediction

## Project Overview

This project aims to build a machine learning model to predict whether a passenger survived the Titanic disaster. The dataset includes several features such as age, gender, ticket class, fare, cabin information, and more. The goal is to preprocess the data effectively, train a classification model, and evaluate its performance to predict the survival of passengers.

## Dataset

The dataset used in this project is from Kaggle's Titanic competition. It contains information about passengers aboard the Titanic and their survival outcomes.

### Features:
- **Age**: The age of the passenger.
- **Gender**: The gender of the passenger.
- **Ticket Class**: The class of the ticket purchased by the passenger (1st, 2nd, 3rd).
- **Fare**: The fare paid by the passenger.
- **Cabin**: The cabin number where the passenger stayed.
- **Embarked**: The port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton).
- **SibSp**: The number of siblings/spouses aboard.
- **Parch**: The number of parents/children aboard.

## Objective

The objective of this project is to create a well-trained machine learning model capable of predicting whether a passenger survived the Titanic disaster.

## Steps Involved

### 1. Data Preprocessing:
   - **Handle Missing Values**: Imputed missing values in numerical and categorical columns.
   - **Encode Categorical Variables**: Used one-hot encoding for categorical variables like 'Gender' and 'Embarked'.
   - **Normalize Numerical Data**: Standardized numerical columns such as 'Age' and 'Fare' for consistent scaling.

### 2. Model Selection:
   - **Logistic Regression**: A simple linear model that predicts survival based on passenger features.
   - **Random Forest Classifier**: An ensemble method that combines multiple decision trees to make predictions.

### 3. Model Evaluation:
   - The performance of both models was evaluated using accuracy, precision, recall, and F1-score through cross-validation (5-fold).
   - The results demonstrated that both models performed well, with Random Forest showing a slight advantage in handling complex patterns in the data.

### 4. Performance Metrics:
   - **Accuracy**: The proportion of correctly predicted survival outcomes.
   - **Precision**: The proportion of true positive predictions out of all positive predictions.
   - **Recall**: The proportion of true positive predictions out of all actual positive instances.
   - **F1-score**: The harmonic mean of precision and recall, providing a balanced evaluation metric.

## Conclusion

The Logistic Regression and Random Forest models both performed excellently on the Titanic survival prediction task. While Logistic Regression offers simplicity and interpretability, Random Forest demonstrated better handling of complex feature interactions. The models achieved good generalization during cross-validation and are capable of making accurate survival predictions.


