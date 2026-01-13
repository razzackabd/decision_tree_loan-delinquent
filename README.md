# decision_tree_loan-delinquent
Overview

This project builds a Decision Tree classification model to predict whether a loan will become delinquent based on borrower, loan, and financial attributes. The goal is to support credit risk assessment by providing an interpretable model that highlights key factors influencing delinquency.

Problem Statement

Loan delinquency poses financial risk to lenders. By analyzing historical loan data, we aim to classify loans into:

Delinquent (1)

Non-Delinquent (0)

using a supervised machine learning approach.

Dataset

The dataset typically includes the following features (example):

loan_amount

interest_rate

term

annual_income

credit_score

debt_to_income_ratio

employment_length

loan_purpose

delinquent (target variable)

Note: Feature names and distributions may vary depending on the data source.

Methodology

Data Preprocessing

Handle missing values

Encode categorical variables

Feature selection

Exploratory Data Analysis (EDA)

Distribution analysis

Correlation analysis

Delinquency trends

Model Building

Algorithm: Decision Tree Classifier

Criterion: Gini Index / Entropy

Max depth and pruning to avoid overfitting

Model Evaluation

Accuracy

Precision, Recall, F1-score

Confusion Matrix

ROC-AUC (optional)

Results

The decision tree model provides:

Competitive classification performance

High interpretability

Clear decision rules identifying high-risk loans

Key risk drivers often include credit score, debt-to-income ratio, and loan amount.
