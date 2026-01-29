# Bank Customer Churn Prediction

## Overview
This project predicts customer churn in a banking institution using machine learning. The goal is to identify customers likely to leave the bank and support data-driven retention strategies.

## Dataset
The dataset contains customer demographic, financial, and account information.  
**Target variable:** `Exited` (1 = churned, 0 = retained)

## Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook / VS Code  

## Workflow
1. Data cleaning and EDA  
2. Feature encoding and scaling  
3. Train-test split  
4. Model training and evaluation  

## Feature Scaling
Numerical features were standardized using `StandardScaler`, fitted on the training data and applied to both training and test sets to prevent data leakage.

## Models & Evaluation
- Logistic Regression  
- Model performance evaluated using accuracy and classification metrics

## Conclusion
The model successfully identifies key factors influencing customer churn, demonstrating the value of machine learning in customer retention analysis.

## Author
**Mercy Magut**
