# Diabetes-Prediction

This repository contains a machine learning model for predicting the likelihood of diabetes based on various features, such as BMI (Body Mass Index) and number of pregnancies. The model is trained using a dataset that includes historical information about patients, including their health metrics and whether or not they have been diagnosed with diabetes.

## Dataset

The dataset used for training and evaluation consists of a collection of patient records. Each record contains several columns, including the following relevant features:

1. **BMI**: The Body Mass Index is a measure of body fat based on height and weight. It is calculated as weight (in kilograms) divided by the square of height (in meters).

2. **Number of Pregnancies**: This feature represents the number of times the patient has been pregnant.

<!-- Add descriptions of other relevant columns here -->

The dataset also includes a target column, **Diabetes Outcome**, which indicates whether the patient has been diagnosed with diabetes or not (1 for diabetic, 0 for non-diabetic).

## Model

The machine learning model in this repository is built using a supervised learning algorithm, specifically logistic regression. Logistic regression is a popular choice for binary classification problems like diabetes prediction.

The model is trained on the provided dataset, where the features mentioned above are used to predict the target column, Diabetes Outcome. The model learns the relationship between the input features and the target variable during the training process.
