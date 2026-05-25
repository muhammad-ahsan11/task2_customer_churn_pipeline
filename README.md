# End-to-End ML Pipeline for Customer Churn Prediction

## Overview
This project focuses on building a complete machine learning pipeline for predicting customer churn using the Telco Customer Churn dataset. The objective is to develop a reusable and production-ready workflow that automates data preprocessing, model training, evaluation, and model export.

In this notebook, different preprocessing techniques such as missing value handling, feature scaling, and categorical encoding are implemented using Scikit-learn’s Pipeline and ColumnTransformer APIs. Two machine learning models — Logistic Regression and Random Forest — are trained and evaluated to compare their performance.

Additionally, GridSearchCV is used for hyperparameter tuning to improve model accuracy and identify the best-performing configuration. The final optimized pipeline is exported using Joblib for future deployment and reuse.

This project demonstrates essential machine learning engineering practices including modular pipeline construction, automated preprocessing, model optimization, evaluation using classification metrics, and production-ready model saving techniques.

---

## Objectives
- Build a complete machine learning pipeline using Scikit-learn
- Perform automated preprocessing for numerical and categorical data
- Train and evaluate multiple machine learning models
- Apply hyperparameter tuning using GridSearchCV
- Export the trained pipeline using Joblib
- Develop a reusable and production-ready ML workflow

---

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Joblib
- Google Colab

---

## Dataset
Dataset Used: Telco Customer Churn Dataset

The dataset contains customer demographic information, account details, subscribed services, and churn labels used to predict whether a customer is likely to leave the company.

---

## Evaluation Metrics
The following evaluation metrics are used:
- Accuracy Score
- Classification Report
- Precision
- Recall
- F1-Score

---

## Expected Outcome
By the end of this project, a fully trained and optimized customer churn prediction pipeline will be developed and saved for deployment or future inference tasks.
