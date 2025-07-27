# 🏦 Loan Status Prediction using Machine Learning

This project predicts whether a loan application will be **approved** or **rejected** based on historical applicant data using various supervised machine learning algorithms.

---

## 📌 Problem Statement

Loan officers at financial institutions must decide whether to approve a loan application based on multiple factors. This manual process can be subjective, time-consuming, and prone to errors. The goal of this project is to **build a machine learning model that automates loan status prediction**, increasing speed and accuracy.

---

## 🧾 Dataset Features

The dataset includes the following key attributes:

| Column             | Description                          |
|--------------------|--------------------------------------|
| Gender             | Male / Female                        |
| Married            | Marital status                       |
| Dependents         | Number of dependents                 |
| Education          | Graduate / Not Graduate              |
| Self_Employed      | Employment status                    |
| ApplicantIncome    | Applicant's income                   |
| CoapplicantIncome  | Co-applicant's income                |
| LoanAmount         | Loan amount requested                |
| Loan_Amount_Term   | Repayment term (months)              |
| Credit_History     | Credit history (1 = good, 0 = bad)   |
| Property_Area      | Urban / Semiurban / Rural            |
| Loan_Status        | Target (Y = Approved, N = Rejected)  |

---

## 🔄 Methodology

1. **Data Preprocessing**
   - Handled missing values
   - Converted categorical variables using Label Encoding
   - Treated outliers and scaled numeric features

2. **Exploratory Data Analysis (EDA)**
   - Identified patterns in approval rates
   - Analyzed correlations and feature distributions

3. **Modeling**
   - Applied multiple classification algorithms:
     - Logistic Regression
     - Decision Tree
     - Random Forest
     - Support Vector Machine
   - Used train-test split for validation

4. **Evaluation**
   - Metrics used:
     - Accuracy
     - Precision
     - Recall
     - F1 Score
     - Confusion Matrix
     - ROC-AUC Curve

---

## 🧠 Tools & Libraries

- Python
- Pandas, NumPy
- scikit-learn
- Seaborn, Matplotlib

---
