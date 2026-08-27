# Personal Expense & Spending Analysis

## Project Overview

**Personal Expense & Spending Analysis** is a Power BI-based data analytics project designed to analyze household financial transactions and identify meaningful patterns in income, expenses, spending categories, payment methods, and financial activity over time.

The project transforms raw household transaction data into a cleaned and structured dataset, creates analytical measures using DAX, and presents the results through an interactive Power BI dashboard.

## Business Problem

Managing household transactions manually can make it difficult to understand where money is being spent, how spending changes over time, which payment methods are used most frequently, and how income compares with expenses.

This project addresses these challenges by providing an interactive analytical dashboard for monitoring and understanding household financial activity.

## Business Cases

The project focuses on the following business cases:

1. **Expense Monitoring**
2. **Spending Pattern Analysis**
3. **Category-Wise Expense Analysis**
4. **Monthly Spending Trend Analysis**
5. **Income vs. Expense Analysis**
6. **Spending Behavior by Payment Method**

## Dataset

**Dataset:** Daily Household Transactions

The dataset contains household financial transaction records including transaction dates, amounts, transaction types, categories, and payment modes.

The raw dataset was imported into Power BI and cleaned using Power Query before analysis.

## Data Preparation

The following data preparation activities were performed in Power Query:

* Promoted the first row as column headers
* Corrected date and date/time data types
* Converted the transaction date using the appropriate locale
* Created Year
* Created Month Name
* Created Month Number
* Created Month-Year
* Created Start of Month
* Standardized category/payment-related text values
* Verified data quality
* Confirmed 0% errors in the final transformed columns

## Data Analysis

DAX measures were created to support the analysis, including:

* Total Amount
* Total Expense
* Total Income
* Total Transfer-Out
* Net Balance
* Transaction Count
* Expense Transaction Count
* Income Transaction Count
* Transfer-Out Transaction Count
* Average Expense
* Average Income
* Expense % of Income
* Savings Rate

## Dashboard Pages

### 1. Personal Expense & Spending Analysis

The overall dashboard provides a high-level summary of household financial activity through key KPIs and important analytical visuals.

Key metrics include:

* Total Income
* Total Expense
* Net Balance
* Savings Rate
* Expense % of Income
* Transaction Count

### 2. Expense Monitoring

This page focuses on expense-related monitoring through KPI cards and visual analysis.

Key analysis includes:

* Total Expense
* Total Income
* Net Balance
* Savings Rate
* Expense % of Income
* Expense Transaction Count
* Monthly Expense Trend
* Expense by Category

### 3. Payment Method Analysis

This page analyzes spending behavior according to payment mode.

Key visualizations include:

* Total Expense by Payment Method
* Expense Transaction Count by Payment Method

The analysis helps identify both the payment methods associated with higher spending and the payment methods used most frequently.

### 4. Spending Pattern Analysis

This page analyzes changes in expense transaction frequency over time.

**Visualization:**

* Monthly Expense Transaction Frequency

The analysis uses Month-Year and Expense Transaction Count to identify changes in transaction activity over time.

### 5. Income vs Expense Analysis

This page compares income and expenses on a yearly basis.

**Visualization:**

* Year-wise Income vs Expense

The analysis helps identify years with higher income and higher expenses.

## Key Findings

Based on the completed dashboard analysis:

* Total Income is approximately **₹3 million**.
* Total Expense is approximately **₹2 million**.
* Net Balance is approximately **₹1 million**.
* Savings Rate is **35.66%**.
* Expense as a percentage of income is **64.34%**.
* Expense Transaction Count is approximately **2K**.
* **Cash** is the most frequently used payment method for expense transactions.
* **2017** recorded the highest income at approximately **₹946,411**.
* **2017** also recorded the highest expense at approximately **₹652,598**.

## Tools & Technologies

* **Microsoft Power BI**
* **Power Query**
* **DAX**
* **CSV**
* **Data Visualization**
* **Data Cleaning & Transformation**

## Project Workflow

```text
Raw Data
   ↓
Data Cleaning & Transformation
   ↓
Data Modeling
   ↓
DAX Measures
   ↓
Data Analysis
   ↓
Dashboard & Visualization
   ↓
Business Insights
```

## Skills Demonstrated

* Data Cleaning
* Data Transformation
* Data Modeling
* DAX
* KPI Development
* Data Visualization
* Financial Data Analysis
* Business Case Analysis
* Dashboard Design
* Business Insight Generation

## Project Outcome

The completed Power BI dashboard converts raw household transaction data into an interactive analytical solution that helps users monitor expenses, understand spending behavior, compare income and expenses, and identify important financial patterns.

## Repository Contents

```text
Personal_Expense_and_Spending_Analysis_System/
│
├── data/
│   └── raw/
│       └── Daily Household Transactions.csv
│
├── screenshots/
│   ├── overall_dashboard.png
│   ├── expense_monitoring.png
│   ├── payment_method_analysis.png
│   ├── spending_pattern_analysis.png
│   └── income_vs_expense_analysis.png
│
├── PESAS.pbix
├── README.md
└── requirements.txt
```

## Conclusion

This project demonstrates how Power BI can be used to transform raw household transaction data into meaningful financial insights through data preparation, DAX-based analysis, KPI development, and interactive dashboard visualization.
