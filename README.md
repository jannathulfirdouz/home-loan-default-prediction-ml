
# Optimizing Home Loan Origination Decisions Using Machine Learning

## Overview
This project develops machine learning models to improve Home loan approval decisions and credit risk assessment.

The study applies machine learning techniques using SAS Viya to predict borrower risk and support data-driven decision-making in mortgage lending.

## Objectives
- Predict home loan approval probability
- Improve credit risk assessment
- Compare multiple machine learning models

- # HMEQ Home Equity Loan Dataset – Credit Risk Prediction

## Dataset Overview
- **Source:** HMEQ (Home Equity Loan) Dataset "https://www.kaggle.com/datasets/ajay1735/hmeq-data"
- **Total Observations:** 5,960 loan applications  
- **Total Variables:** 13  
- **Objective:** Predict loan default risk (credit risk modeling)  

This dataset is widely used for credit risk modeling and mortgage default prediction.

---

## Target Variable
| Variable | Description | Values |
|----------|-------------|--------|
| `BAD` | Loan Default Indicator | 1 = Borrower defaulted<br>0 = Borrower repaid loan |

- **Default Rate:** 20%  
  *Represents a realistic class imbalance commonly observed in credit risk datasets.*

---

## Predictor Variables

### Financial Variables
- `LOAN` – Loan amount requested  
- `MORTDUE` – Amount still owed on existing mortgage  
- `VALUE` – Current value of property  
- `DEBTINC` – Debt-to-income ratio  

### Employment Variables
- `JOB` – Occupation category  
- `YOJ` – Years at current job  

### Credit Behavior Variables
- `DEROG` – Number of derogatory credit reports  
- `DELINQ` – Number of delinquent credit lines  
- `CLAGE` – Age of oldest credit line  
- `NINQ` – Number of recent credit inquiries  
- `CLNO` – Number of credit lines  

### Loan Purpose
- `REASON` – Purpose of loan  
  - Debt consolidation  
  - Home improvement  

---

## Weight of Evidence (WOE)

### Purpose
- Handle categorical variables  
- Improve model interpretability  
- Stabilize logistic regression models  
- Address credit risk modeling standards  

### WOE Formula
WOE = ln(Percentage of Non-Defaults / Percentage of Defaults)
**

## Methods
- Logistic Regression
- Decision Trees
- Random Forest
- Gradient Boosting

## Tools
- SAS Viya
- SAS Machine Learning
- Data Analytics

## Results
Machine learning models improved predictive performance compared with traditional statistical models and helped identify key factors influencing loan approval.

## Author
Jannathul Firdouz Sahul Hameed  
Master of Analytics – Auckland University of Technology
