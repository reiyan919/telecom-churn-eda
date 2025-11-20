 Telecom Customer Churn – EDA & Dashboard

This project explores the **Telco Customer Churn dataset** through a complete **Data Cleaning**, **Exploratory Data Analysis (EDA)**, and **Tableau Dashboard**.


##  Project Overview

The goal of this project is to understand the key drivers of customer churn in a telecom company. It includes:

* Cleaning and preprocessing the dataset
* Exploratory Data Analysis (EDA)
* Building a Tableau dashboard with insights

Dataset used: `WA_Fn-UseC_-Telco-Customer-Churn.csv`



##  1. Data Cleaning

Main steps completed:

* Removed duplicates
* Handled missing values
* Converted `TotalCharges` to numeric
* Removed rows with blank text
* Saved cleaned data as: **clean-Telco-Customer-Churn.csv**



## 2. Exploratory Data Analysis (EDA)

The EDA includes:

###  Distributions

* Monthly charges
* Total charges
* Tenure

###  Correlation Analysis

* Numeric correlation matrix
* Heatmap using Seaborn

###  Category Patterns

* Churn by contract type
* Churn by payment method
* Churn by internet service type

###  KPIs

* Total customers
* Churn rate
* Average monthly charges
* Tenure statistics

###  Key Insights

* Month-to-month contracts show the highest churn.
* Customers without tech support or online security churn more.
* Fiber optic users churn more than DSL users.
* Higher monthly charges are associated with higher churn.

---

##  3. Dashboard (Tableau)

Dashboard includes:

* KPI cards (Total customers, churn %)
* Customers by contract type
* Internet service vs churn
* Pie/Donut chart for payment method
* Churn distribution by gender
* Correlation heatmap
* Filters: gender, contract, internet service

Dashboard preview is saved in: **dashboard/Dashboard1.png**





