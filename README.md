# 📊 Customer Churn Prediction & Analysis

---

## 📌 1. Introduction

Customer churn refers to the loss of customers who stop using a company’s product or service. Predicting churn is very important for businesses because retaining existing customers is more cost-effective than acquiring new ones.

This project focuses on analyzing customer behavior and predicting churn using Machine Learning and visualizing insights using Power BI.

---

## 🎯 2. Objectives

* To understand customer behavior and patterns
* To identify factors influencing customer churn
* To build a Machine Learning model for churn prediction
* To create an interactive dashboard for business insights

---

## 📂 3. Dataset Description

The dataset used in this project is the **Telco Customer Churn Dataset**.

### 🔹 Features include:

* Customer demographics (Gender, Senior Citizen)
* Account information (Tenure, Contract Type)
* Services used (Internet, Phone, etc.)
* Billing details (Monthly Charges, Total Charges)
* Target variable: **Churn (Yes/No)**

---

## 🧹 4. Data Preprocessing

The following steps were performed:

* Converted `TotalCharges` to numeric format
* Handled missing values using median imputation
* Dropped unnecessary columns like `customerID`
* Converted target variable (Churn) into binary (0/1)
* Applied one-hot encoding to categorical variables

---

## 📊 5. Exploratory Data Analysis (EDA)

EDA was performed to understand patterns and relationships:

### Key Visualizations:

* Churn Distribution
* Monthly Charges vs Churn
* Tenure vs Churn
* Contract Type vs Churn
* Internet Service vs Churn

### 🔍 Observations:

* Customers with **month-to-month contracts** have higher churn
* **Higher monthly charges** are associated with higher churn
* Customers with **low tenure** are more likely to churn

---

## 🤖 6. Model Building

### Algorithm Used:

* Logistic Regression

### Steps:

* Split data into training and testing sets
* Applied feature scaling using StandardScaler
* Trained the Logistic Regression model

---

## 📈 7. Model Evaluation

* Accuracy achieved: **~82%**
* Confusion Matrix used to evaluate performance

### Interpretation:

* Model performs well in predicting churn and non-churn customers
* Provides a good baseline for business decision-making

---

## 📊 8. Dashboard (Power BI)

An interactive dashboard was created to visualize insights:

### 🔹 Features:

* KPI Cards (Total Customers, Churn, Churn Rate)
* Interactive filters (Gender, Contract, Internet Service)
* Multiple charts for trend analysis

### 🔹 Insights:

* Month-to-month customers churn the most
* Fiber users show higher churn tendency
* Churn rate is approximately **26%**

---

## 💡 9. Business Insights

* Retention strategies should focus on new customers
* Pricing strategies may impact churn
* Long-term contracts help reduce churn
* Personalized offers can reduce customer loss

---

## 🚀 10. Conclusion

This project successfully demonstrates how Machine Learning and data visualization can be used together to analyze and predict customer churn.

The insights generated can help businesses make data-driven decisions to improve customer retention and reduce churn.

---

## 🛠 Tools & Technologies

* Python (Pandas, NumPy, Scikit-learn)
* Power BI
* Jupyter Notebook

---

## 📌 Future Scope

* Use advanced models like Random Forest or XGBoost
* Deploy the model using a web application
* Perform hyperparameter tuning for better accuracy
* Integrate real-time data for continuous prediction

---


## 📊 Results

- Model Accuracy: ~82%
- Churn Rate: ~26%
- Key Factors: Contract type, Monthly charges, Tenure

## 📷 Dashboard

![Dashboard](dashboard/dashboard.png)

----
## 👨‍💻 Author

Rushikesh Mhaske
(Data Analyst / Data Science Enthusiast)

---
