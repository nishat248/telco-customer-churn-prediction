# Telco Customer Churn Prediction using Machine Learning

End-to-end churn prediction pipeline using XGBoost, LightGBM, CatBoost, TabPFN, SHAP explainability, threshold optimization, and retention analytics.

---

## Project Overview

Customer churn is one of the most important business challenges in the telecommunications industry. Losing existing customers directly impacts revenue and increases customer acquisition costs.

This project develops a complete machine learning pipeline to predict customer churn and identify high-risk customers before they leave. Multiple machine learning models were trained, compared, interpreted, and evaluated using both predictive and business-focused metrics.

---

## Dataset

This project uses the IBM Telco Customer Churn Dataset.

Dataset Source:

https://www.kaggle.com/datasets/yeanzc/telco-customer-churn-ibm-dataset

### Dataset Information

- 7,043 customer records
- 33 features
- Customer demographics
- Service subscriptions
- Contract information
- Billing details
- Customer Lifetime Value (CLTV)
- Churn indicators

### Target Variable

- Churn Value
  - 0 = Customer Retained
  - 1 = Customer Churned

---

## Project Features

### Data Preprocessing

- Missing value inspection
- Duplicate checking
- Data cleaning
- Feature encoding
- Train-validation-test splitting

### Leakage Prevention

Potential target leakage features were identified and removed before model training to ensure realistic model performance.

### Machine Learning Models

The following models were trained and evaluated:

- Logistic Regression
- Random Forest
- XGBoost
- LightGBM
- CatBoost
- TabPFN

### Class Imbalance Handling

- Original dataset evaluation
- SMOTE oversampling experiments
- Comparative performance analysis

### Threshold Optimization

Model probability thresholds were optimized to improve churn detection and retention targeting.

### SHAP Explainability

SHAP was used to:

- Analyze feature importance
- Interpret model predictions
- Explain customer-level churn decisions

### Fairness Analysis

Model predictions were analyzed across customer groups to evaluate fairness and potential bias.

### Retention Prioritization

Predicted churn probabilities were used to identify customers requiring immediate retention efforts.

### Single Customer Prediction

A prediction pipeline was implemented for individual customer inference and churn probability estimation.

### Model Persistence

The final trained model was exported and saved for future deployment.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- LightGBM
- CatBoost
- TabPFN
- SHAP
- Matplotlib
- Seaborn

---

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Leakage Removal
6. Train-Validation-Test Split
7. Model Training
8. SMOTE Evaluation
9. Threshold Optimization
10. SHAP Analysis
11. Fairness Assessment
12. Retention Prioritization
13. Final Model Selection
14. Model Export

---

## Business Impact

This system helps organizations:

- Detect churn risk early
- Improve customer retention
- Optimize retention campaigns
- Increase customer lifetime value
- Support data-driven decision making

---

## Repository Structure

telco-customer-churn-prediction/

├── telco_customer_churn_prediction.ipynb

├── README.md

├── LICENSE

---

## Author

Nishat Anjum

Machine Learning Project
