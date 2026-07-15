# 📊 Customer Data Analysis for Business Insights

A complete end-to-end **Python Data Analytics** project focused on customer behavior analysis using **Pandas, NumPy, and Matplotlib**. The project performs data cleaning, exploratory data analysis (EDA), customer segmentation using **RFM (Recency, Frequency, Monetary)** analysis, and generates business insights for marketing and customer retention.

---

## 🚀 Project Overview

Businesses generate thousands of customer transactions every day. Raw transaction data alone provides little value unless it is cleaned, analyzed, and transformed into meaningful business insights.

This project demonstrates how customer demographic information and transaction history can be used to:

- Improve data quality
- Analyze customer purchase behavior
- Identify high-value customers
- Segment customers using RFM Analysis
- Visualize business metrics
- Apply the Pareto Principle (80/20 Rule)

---

## 🎯 Business Problem

A retail company wants to better understand its customer base in order to:

- Improve targeted marketing
- Increase customer retention
- Identify high-value customers
- Detect inactive customers
- Generate actionable business insights from historical transactions

---

# 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 📂 Project Structure

```
Customer-Data-Analysis/
│
├── Customer data analysis for Business Insights.ipynb
├── Career247_Mini_Project_2_Customer_RFM_Output.ipynb
├── Customer_Master_Data.csv
├── Customer_Transactions.csv
├── README.md
└── images/
```

---

# 📋 Dataset

The project uses two datasets.

### Customer Master Data

Contains customer demographic information.

Features include:

- Customer ID
- Name
- Email
- Gender
- Age
- City
- Marital Status
- Number of Children
- Join Date

---

### Customer Transactions

Contains transaction history.

Features include:

- Customer ID
- Transaction Date
- Transaction Amount

---

# 🔍 Project Workflow

## 1. Data Loading

- Imported datasets
- Verified structure
- Checked dataset dimensions
- Previewed records

---

## 2. Data Cleaning

Performed multiple preprocessing steps:

- Removed duplicate records
- Checked missing values
- Converted date columns into datetime format
- Validated CustomerID consistency
- Ensured transaction records matched customer records

---

## 3. Exploratory Data Analysis (EDA)

Performed demographic analysis including:

- Gender distribution
- Age distribution
- City-wise customer distribution
- Marital status analysis

Transaction analysis included:

- Total revenue
- Average transaction value
- Customer purchase frequency

---

## 4. Customer-Level Analysis

Merged customer and transaction datasets to understand:

- Customer spending patterns
- Repeat purchase behavior
- Revenue contribution by customer

---

# 📈 RFM Analysis

The project calculates three important customer metrics.

### Recency

Days since customer's most recent purchase.

---

### Frequency

Number of purchases made.

---

### Monetary

Total amount spent.

---

Using these metrics, every customer receives an RFM score ranging from **111** to **555**.

---

# 👥 Customer Segmentation

Customers are segmented into business-friendly groups such as:

- 🏆 Champions
- ❤️ Loyal Customers
- 🌱 Potential Loyalists
- ⚠️ At Risk
- ❌ Lost Customers
- 💰 Big Spenders

These segments help businesses personalize marketing campaigns.

---

# 📊 Visualizations

The notebook includes several visualizations such as:

- Customer Segment Distribution
- Revenue by Customer Segment
- Recency vs Monetary Scatter Plot
- Pareto (80/20) Analysis
- Customer Distribution Charts

---

# 📌 Key Business Insights

The analysis enables businesses to:

- Identify premium customers
- Detect inactive customers
- Improve customer retention
- Design targeted marketing campaigns
- Optimize loyalty programs
- Focus on high-revenue customer segments

---

# 📈 Pareto Analysis

The project also demonstrates the **80/20 Rule**, showing how a small percentage of customers contribute to the majority of revenue.

This helps businesses prioritize customer engagement strategies.

---

# 📁 Output

The project generates:

- Cleaned datasets
- RFM table
- Customer segments
- Revenue analysis
- Business visualizations
- Customer_RFM_Output.csv

---

# 📚 Learning Outcomes

This project demonstrates practical knowledge of:

- Data Cleaning
- Data Wrangling
- Exploratory Data Analysis
- Customer Analytics
- RFM Analysis
- Customer Segmentation
- Business Intelligence
- Data Visualization
- Pandas GroupBy Operations
- Business Problem Solving

---

# ⭐ Future Improvements

- Interactive dashboard using Power BI or Tableau
- Streamlit web application
- Automated customer segmentation pipeline
- Predict customer churn using Machine Learning
- Customer Lifetime Value (CLV) Analysis
- Marketing recommendation engine

---

# 👨‍💻 Author

**Kshitij Thakur**

If you found this project useful, feel free to ⭐ the repository.
