# Credit-Card-Customer-Churn-Prediction-Using-Machine-Learning

# Project Title

# Credit Card Customer Churn Prediction Using Machine Learning

# Overview

This project focuses on Exploratory Data Analysis (EDA) and modeling to uncover insights from the data and build predictive models to understand Customer Churn.

Customer churn, also known as customer attrition, refers to the phenomenon where customers stop doing business with a company or service. It is a critical metric for businesses as it directly impacts revenue and profitability. High churn rates can indicate dissatisfaction with the product or service, poor customer experience.

# Skills Demonstrated

-Python

-Pandas

-NumPy

-Data Visualization

-Machine Learning

-Classification Models

-Feature Engineering

-Customer Analytics

-Business Intelligence

-Predictive Analytics

# Analytical Skills

-Data Cleaning

-EDA

-Predictive Modeling

# Business Skills

-Customer Analytics

-Retention Strategy

-KPI Analysis

# Dataset Description

Dataset: Churn_Modelling.csv

<img width="904" height="1232" alt="Screenshot 2026-06-02 174623" src="https://github.com/user-attachments/assets/9bac43db-adef-4fc8-b184-59c1c75b494d" />

# Project Objectives

# Descriptive Analytics

Analyze customer demographics

Identify churn patterns

Understand customer behavior

Predictive Analytics

# Build ML models to predict:

Will the customer churn?

Churn probability score

# Project Workflow

<img width="470" height="560" alt="2" src="https://github.com/user-attachments/assets/a8fe1ec6-c45a-4824-91e6-45d8cb41da35" />

# Result

<img width="1038" height="432" alt="image" src="https://github.com/user-attachments/assets/91a3e341-83d9-4d0f-aee4-df98e7b41afb" />

From the results of the classification models on the churn prediction dataset, we can infer the following:

Gradient Boosting has the highest F1 score (0.598391) and the highest ROC AUC score (0.859767) among all the models. This suggests that Gradient Boosting is the most effective model in balancing precision and recall and has the best ability to distinguish between the churned and non-churned customers.

XGBoost also performs well, with a relatively high F1 score (0.586974) and a good ROC AUC score (0.841784). This indicates that XGBoost is another strong model for this task.

Random Forest has a high accuracy (0.862000) but a lower F1 score (0.538976) compared to Gradient Boosting and XGBoost. This suggests that while Random Forest is good at predicting the majority class (non-churned customers), it might not be as effective at identifying the minority class (churned customers).

Support Vector Machine and K-Nearest Neighbors have moderate F1 scores and ROC AUC scores. They perform better than Logistic Regression but are not as effective as Gradient Boosting or XGBoost for this dataset.

Logistic Regression has the lowest accuracy (0.703667), F1 score (0.473029), and ROC AUC score (0.764076) among all the models. This indicates that Logistic Regression is the least effective model for predicting customer churn in this dataset.

# Overall:
Gradient Boosting appears to be the best model for this churn prediction task, followed closely by XGBoost. These models are able to better handle the class imbalance and provide a good balance between precision and recall.

