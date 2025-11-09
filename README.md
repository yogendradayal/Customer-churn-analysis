# 📊 Customer Churn Analysis

## 🧠 Project Overview
This project analyzes customer churn to help businesses understand the reasons behind customer attrition.  
Using the **Telco Customer Churn dataset**, we perform **data cleaning, transformation, and exploratory data analysis (EDA)** to uncover insights about customer behavior and service usage patterns.

The ultimate goal is to identify which factors lead to customer churn and how the company can improve customer retention.

---

## 📁 Dataset Information

**Dataset Name:** `CustomerChurn.csv`  
**Total Records:** 7,043  
**Total Columns:** 21  

Each record represents a customer with various demographic, service usage, and account information.

### 🔑 Key Columns

| Column | Description |
|:--|:--|
| `customerID` | Unique ID for each customer |
| `gender` | Gender of the customer (Male/Female) |
| `SeniorCitizen` | Indicates if the customer is a senior citizen (Yes/No) |
| `Partner` | Whether the customer has a partner |
| `Dependents` | Whether the customer has dependents |
| `tenure` | Number of months the customer has stayed |
| `PhoneService` | Whether the customer has phone service |
| `MultipleLines` | Whether the customer has multiple lines |
| `InternetService` | Type of internet service (DSL/Fiber optic/None) |
| `OnlineSecurity` | Whether the customer has online security |
| `OnlineBackup` | Whether the customer has online backup |
| `DeviceProtection` | Whether the customer has device protection |
| `TechSupport` | Whether the customer has technical support |
| `StreamingTV` | Whether the customer has streaming TV |
| `StreamingMovies` | Whether the customer has streaming movies |
| `Contract` | Type of contract (Month-to-month/One year/Two year) |
| `PaperlessBilling` | Indicates if paperless billing is enabled |
| `PaymentMethod` | Method of payment (Electronic check/Credit card/etc.) |
| `MonthlyCharges` | Monthly charges |
| `TotalCharges` | Total charges to date |
| `Churn` | Whether the customer has left (Yes/No) |

---

## 📈 Exploratory Data Analysis (EDA)

Data visualization was performed using **Matplotlib** and **Seaborn** to identify patterns and trends in customer churn behavior.

### 1️⃣ Overall Churn Distribution
- Approximately **26.54%** of customers have churned.

### 2️⃣ Gender vs Churn
- Churn rates are almost **equal for both genders**.

### 3️⃣ Senior Citizen vs Churn
- **Senior Citizens** show a **higher churn percentage** than younger customers.

### 4️⃣ Tenure vs Churn
- **Short-term customers (1–2 months)** are more likely to churn.
- Customers with **longer tenure** tend to remain loyal.

### 5️⃣ Contract Type
- **Month-to-month** customers churn more frequently.
- **1-year and 2-year** contract customers are more stable and have lower churn.

### 6️⃣ Internet and Additional Services
- Customers **without Online Security, Tech Support, or Device Protection** are more likely to churn.
- **DSL** customers churn less often than **Fiber optic** customers.

### 7️⃣ Payment Method
- Customers using **Electronic Check** have the **highest churn rate**.

---
## 🚀 How to Run This Project

Follow these steps to set up and run the Customer Churn Analysis project on your local machine.

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yogendradayal/Customer-Churn-Analysis.git
cd Customer-Churn-Analysis
```
### 2️⃣ Install Dependencies
Make sure you have **Python 3.x** installed. Then, install the required libraries:
```bash
pip install pandas numpy matplotlib seaborn
```
### 3️⃣ Run the Python Script

To execute the churn analysis:
```bash
python churn_analysis.py
```
---
## 📚 Conclusion

✅ **Key Findings:**
- **Senior Citizens** and **short-tenure customers** are more likely to churn.  
- **Month-to-month contracts** and **electronic check payments** are associated with higher churn.  
- Customers with **long-term contracts**, **bundled services**, and **automatic payment options** show better retention.

---

### 💼 Business Recommendations:
- Encourage customers to **switch to long-term contracts**.  
- Promote **bundled internet and security services**.  
- Offer **discounts for auto-pay and paperless billing**.

By implementing these strategies, companies can significantly **reduce customer churn** and **improve overall satisfaction**.

