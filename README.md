# 📊 **Banking Customer Behavior – Exploratory Data Analysis (EDA)**

This project analyzes customer financial behavior across various banking products such as **Checking Accounts**, **Saving Accounts**, **Foreign Currency Accounts**, and **Bank Deposits**.
The goal is to uncover meaningful insights related to **customer segmentation, financial patterns, product usage, risk indicators, and correlations**.

---

# 🧠 **Project Objectives**

* Understand deposit behavior, account usage, and financial engagement.
* Identify high-value, high-risk, and churn-prone customer segments.
* Analyze the relationship between multiple account types.
* Detect anomalies, outliers, and trends in customer financial activity.
* Provide insights that can support credit risk, fraud, and AML teams.

---

# 📌 **Key Features of the Analysis**

### ✔ Univariate Analysis

Analyzed individual features to understand **distribution, skewness, variance, and outliers**.

### ✔ Bivariate Analysis

Studied relationships between key financial variables such as deposits, balances, and account types.

### ✔ Correlation Study

Generated a **heatmap** revealing strong dependencies among banking products.

### ✔ Customer Segmentation

Used patterns from pairplots & distributions to identify distinct customer groups.

---

# 📝 **EDA Summary**

This EDA explores the relationship between **customer demographics**, **account types**, **deposit behavior**, and **product engagement**. Insights serve as a foundation for **risk scoring**, **customer segmentation**, and **product recommendation systems**.

---

## 🔍 **High-Level Insights**

### **1️⃣ Account Balance & Deposits**

* Strong positive correlation between **Bank Deposits** and **Checking Accounts**.
* Savings, Checking, and Foreign Currency Accounts show aligned behavioral patterns.
* Multi-product customers contribute significantly to overall deposits.

---

### **2️⃣ Customer Segmentation**

* Multi-account customers show **higher deposit volume and balance stability**.
* High-balance users prefer a **Savings + Checking combo**.
* Clear segmentation into *high-balance*, *mid-balance*, and *low-balance* groups.

---

### **3️⃣ Demographic Influence**

* Customers aged **25–45** show highest financial activity.
* Younger users (18–25) show:

  * lower balances
  * higher transaction frequency

---

### **4️⃣ Outlier & Risk Indicators**

* Deposit spikes and large fluctuations suggest:

  * high-value individuals
  * possible high-risk accounts
* FCA account balances show the largest variability → global activity.

---

### **5️⃣ Product Usage Behavior**

* FCA customers show above-average transaction activity → possible **cross-border transactions**.
* Checking Accounts act as **core operational products** with low variance.
* Savings influence long-term wealth accumulation.

---

# 📊 **Chart Insights**

### **Correlation Heatmap**

* 🔹 Checking ↔ Deposits → strongest positive correlation
* 🔹 Savings ↔ Total Balance → primary wealth indicator
* 🔹 FCA ↔ High-Net-Worth Customers → niche but valuable segment

---

### **Distribution Plots**

* Deposits are **right-skewed**, showing income inequality across customers.
* Savings & Checking balances show moderate variance with notable outliers.

---

### **Pairplot Segmentation**

Three customer personas emerge:

#### **🔹 Cluster 1: High-Balance, Low-Transaction**

* Wealthy clients with large savings & forex exposure.

#### **🔹 Cluster 2: Mid-Balance, Multi-Account**

* Salaried professionals with stable deposits.

#### **🔹 Cluster 3: Low-Balance, High-Transaction**

* Students or early-career individuals with frequent small deposits.

---

# 🛠 **Tech Stack**

* **Python**
* **Pandas, NumPy**
* **Matplotlib, Seaborn**
* **Jupyter Notebook**
* **Statistical Analysis**
* **Feature Engineering**

---

# 📈 **Key Outcomes**

* Identified high-value, high-risk, and churn-resistant customer segments.
* Found patterns that can help in:

  * **Risk Modeling**
  * **Customer Lifetime Value (CLV) prediction**
  * **Product cross-sell strategy**
  * **AML / fraud monitoring**
* Revealed strong correlations between core financial products.
