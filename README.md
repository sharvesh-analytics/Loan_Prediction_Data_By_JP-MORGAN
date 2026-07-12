📊 Credit Loan Risk Analysis & Expected Loss Prediction using Machine Learning
📌 Project Overview

This project focuses on Credit Loan Risk Analysis, where a Machine Learning model is developed to estimate the Probability of Default (PD) for loan borrowers based on their financial information. Using the predicted probability, the project also calculates the Expected Loss (EL) of each loan assuming a fixed recovery rate.

The objective is to help financial institutions identify high-risk borrowers, estimate potential loan losses, and support better lending decisions.

🎯 Project Objectives
Analyze borrower loan data.
Perform data cleaning and exploratory data analysis (EDA).
Build a Machine Learning model to predict loan default.
Estimate the Probability of Default (PD).
Calculate Expected Loss (EL) using the predicted probability.
Develop a reusable prediction function for new borrowers.
📂 Dataset Information

The dataset contains financial information of loan borrowers including:

Feature	Description
customer_id	Unique customer identifier
credit_lines_outstanding	Number of active credit lines
loan_amt_outstanding	Current outstanding loan amount
total_debt_outstanding	Total outstanding debt
income	Annual borrower income
years_employed	Employment duration
fico_score	Credit score
default	Target variable (0 = No Default, 1 = Default)
🛠 Technologies Used
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
📈 Exploratory Data Analysis (EDA)

The following analyses were performed:

Dataset inspection
Missing value analysis
Duplicate record detection
Statistical summary
Default distribution
Income distribution
Loan amount distribution
FICO score distribution
Correlation heatmap
Default vs Income analysis
Default vs FICO Score analysis
🤖 Machine Learning Model

The project uses Logistic Regression to predict whether a borrower is likely to default.

Model Workflow
Data Loading
Data Cleaning
Feature Selection
Train-Test Split
Model Training
Prediction
Model Evaluation
Probability Prediction
Expected Loss Calculation
📊 Model Evaluation Metrics

The model is evaluated using:

Accuracy Score
Confusion Matrix
Classification Report
ROC-AUC Score

These metrics help evaluate the model's classification performance and prediction capability.

💰 Expected Loss Calculation

The project assumes:

Recovery Rate = 10%

Loss Given Default (LGD)

LGD = 1 − Recovery Rate

LGD = 0.90

Expected Loss Formula

Expected Loss = Probability of Default × LGD × Loan Amount Outstanding
⚙️ Prediction Function

A reusable function has been created that accepts borrower information and returns:

Probability of Default (PD)
Expected Loss (EL)

This function can be used for predicting risk for any new borrower.

📌 Project Workflow
Loan Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Feature Selection
      │
      ▼
Train-Test Split
      │
      ▼
Logistic Regression Model
      │
      ▼
Probability of Default (PD)
      │
      ▼
Expected Loss Calculation
      │
      ▼
Prediction Function

🚀 Key Features

✔ Credit Risk Analysis

✔ Data Cleaning

✔ Exploratory Data Analysis

✔ Machine Learning Model

✔ Logistic Regression

✔ Probability of Default Prediction

✔ Expected Loss Estimation

✔ Financial Risk Assessment

✔ Loan Risk Prediction

✔ Reusable Prediction Function

📚 Concepts Covered
Data Analysis
Data Visualization
Classification
Logistic Regression
Feature Engineering
Credit Risk Modeling
Probability Prediction
Financial Analytics
Machine Learning
Model Evaluation
📌 Future Improvements
Decision Tree Classifier
Random Forest Classifier
XGBoost Model
Hyperparameter Tuning
Cross Validation
Feature Importance Analysis
Model Comparison Dashboard
Streamlit Web Application
Deployment using Flask/FastAPI

📷 Sample Output

The model predicts:

Probability of Default (PD)
Expected Loss (EL)


🎯 Business Value

This project demonstrates how Machine Learning can assist banks and financial institutions in:

Identifying high-risk borrowers
Estimating loan losses
Improving lending decisions
Reducing financial risk
Supporting credit risk management
Enhancing portfolio monitoring

📌 Skills Demonstrated
Python Programming
Data Cleaning
Exploratory Data Analysis
Machine Learning
Logistic Regression
Model Evaluation
Financial Analytics
Credit Risk Analysis
Predictive Modeling
Business Problem Solving

## AUTHOR*
## SHARVESH PANDEY
