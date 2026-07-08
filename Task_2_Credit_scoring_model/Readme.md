# Credit Scoring Model

## Overview
This project predicts an individual's creditworthiness using historical financial and loan-related information. The goal is to classify whether a loan applicant is likely to default or not by applying machine learning classification algorithms.

## Objective
- Predict credit risk based on applicant information.
- Compare multiple machine learning models.
- Select the best-performing model using evaluation metrics.

## Dataset
**Credit Risk Dataset** (Kaggle)

The dataset contains information such as:
- Age
- Annual Income
- Home Ownership
- Employment Length
- Loan Intent
- Loan Grade
- Loan Amount
- Interest Rate
- Loan Percentage of Income
- Previous Default History
- Credit History Length

**Target Variable:**
- `loan_status`
  - 0 = Non-default
  - 1 = Default

## Project Workflow
- Data Loading
- Exploratory Data Analysis (EDA)
- Missing Value Handling
- Categorical Feature Encoding
- Feature Selection
- Train-Test Split
- Model Training
- Model Evaluation
- Model Comparison
- Model Saving

## Machine Learning Models
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

## Files Included
- `credit_scoring.ipynb` – Complete project notebook
- `credit_risk_dataset.csv` – Dataset
- `credit_scoring_model.pkl` – Saved trained model (optional)

## Results
The models were evaluated using multiple classification metrics, and the best-performing model was selected based on overall performance.

## Author
**Priyanshu Singh**