# Telecom Churn Case Study

## Problem Statement
 In the telecom industry:
    1. Annual churn rate is 15-25% .
    2. It costs 5-10 times more to acquire a new customer than retaining one.
    3. Two main models of payment are Postpaid and Prepaid

Thus for many incumbent operators, retaining high profitable customers is the number one business goal and to reduce customer churn, telecom companies need to predict which customers are at high risk of churn.

## Case study Objective
In this project, we will analyse customer-level data of a leading telecom firm, build predictive models to identify customers at high risk of churn and identify the main indicators of churn.

#### Before we move ahead with modeling ,let us define what different types of churn are and which type would be our focus .
     1.Revenue based churn- Where a customer has not utilized any revenue generating facilities e.g.calls or mobile internet
                           -This is flawed because user could be a non-wage earning .
     2.Usage based churn- Where customer has not done any usage either incoming or outgoing calls ,internet
                         - This is flawed since if the customer has not used services he/she might have already churned.
#### Our focus for this exercise would be on usage based churn and on high value churn i.e. from where 80% of revenue comes

## Solution Approach
**1. Descriptive Statistics<br>**
**2. Data Cleaning<br>**
    - Data Type conversion
    - Missing Value treatment
**3. Filter High Value Customers<br>**
**4. Tag churned and non churned customers<br>**
**5. Data Pre-processing<br>**
    - Outlier Treatment
    - Multi-collinearity handling
    - Deriving new features
**6. Exploratory Data Analysis (EDA)<br>**
    - Univariate Analysis
    - Bivariate Analysis
**7. Data Standardizaion<br>**
**8. Modelling and Model Evaluation<br>**
    - PCA
    - High Performance models with PCA
        - Logistic Regression
        - Random Forest
        - XG Boost
    - Interpretable models without PCA
        - Random Forest
**9. Model Evaluation Summary<br>**
**10 Recommendations to prevent customer churn<br>**
