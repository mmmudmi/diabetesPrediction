
# Diabetes Prediction
## Overview


Diabetes is one of the most common diseases worldwide and has become a significant public health concern. Research from the Centers for Disease Control and Prevention (2022) found that diabetes increases the risk of heart disease — the most common diabetes complication — by about four times in women, compared to about two times in men.

This project focuses on Diabetes Prediction for Females using diagnostic measurements from a medical dataset. Early detection is crucial to prevent disease progression and associated complications.

## Objective


- Build a prediction model to classify whether a female patient has diabetes based on selected health features.

- Compare two prediction methods: Logistic Regression and Random Forest.

- Select the best-performing model based on AUC (Area Under the Curve) score.

- Identify important features contributing to the prediction.

## Methods


Two machine learning models were trained and evaluated:

- Logistic Regression: AUC = 0.70

- Random Forest: AUC = 0.86

Based on the evaluation, Random Forest was selected as the final model because it achieved the highest AUC score, indicating better predictive performance.

## Features Used
The following diagnostic features were used for prediction:

- Glucose level

- Body Mass Index (BMI)

- Age

- Number of Pregnancies

## Conclusion

The final prediction model uses the Random Forest method with Glucose, BMI, Age, and Pregnancies as input features to classify diabetes in female patients. Given its superior AUC score, the Random Forest model demonstrates higher reliability and is recommended for deployment in early diabetes detection initiatives.

## Citation
 
[Dataset](https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset/discussion)
