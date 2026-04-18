# 🏦 Bank Customer Segmentation and Transaction Analysis

## 📊 Project Overview

This project focuses on analyzing bank customer data and transaction patterns to generate meaningful insights for business decision-making. The dashboard is built using **Power BI** and provides a comprehensive view of customer segmentation and financial activity.

---

## 🎯 Objectives

* Analyze customer demographics and behavior
* Segment customers based on various attributes
* Track debit and credit transaction trends
* Identify high-value customers
* Provide actionable insights for business growth

---

## 🗂️ Dataset Information

This project uses two datasets:

1. **Customer_data.csv**

   * Customer_ID
   * Gender
   * Age Group
   * Region
   * Account Type

2. **Transaction_data.csv**

   * Transaction_ID
   * Customer_ID
   * Transaction_Type (Debit/Credit)
   * Transaction_Amount
   * Transaction_Date

🔗 A relationship is established between both datasets using:

> **Customer_ID (Primary Key)**

---

## 🔗 Data Model

* One-to-Many Relationship
* `Customer_data` → `Transaction_data`
* Enables detailed customer-level transaction analysis

---

## 📈 Dashboard Features

### 🔹 KPI Metrics

* Total Customers: **10K**
* Total Transactions: **10K**
* Total Debit: **12.75M**
* Total Credit: **12.68M**
* Average Transaction Value: **2.54K**

### 🔹 Visualizations

* Transaction Amount by Account Type
* Transaction Distribution (Debit vs Credit)
* Monthly Transaction Trends
* Customer Distribution by Age Group
* Customer Distribution by Gender
* Top 10 Customers by Transaction Amount
* Region-wise Analysis (Map Visualization)

---

## 🎛️ Filters / Slicers

* Transaction Date
* Gender
* Account Type
* Transaction Type
* Age Group
* Region

---

## 🛠️ Tools & Technologies

* Power BI
* Data Modeling
* Data Visualization
* CSV Data Sources

---

## 📸 Dashboard Preview

![Dashboard Screenshot](dashboard.png)

---

## 🚀 How to Use

1. Download the `.pbix` file
2. Open in Power BI Desktop
3. Load the datasets if required
4. Interact with filters and visuals

---

## 💡 Key Insights

* Balanced distribution between debit and credit transactions
* Certain account types contribute more to total transaction volume
* High-value customers can be targeted for premium services
* Monthly trends help identify peak transaction periods

---

## 📌 Future Improvements

* Add real-time data integration
* Enhance predictive analytics using Machine Learning
* Improve geographical insights with advanced maps

---

## 📬 Contact

For any queries or suggestions, feel free to connect.

---
