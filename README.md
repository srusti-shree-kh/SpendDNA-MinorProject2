# 💰 SpendDNA – Financial Transaction Analytics

## 📌 Project Overview

SpendDNA is a Python-based financial analytics project that analyzes six months of synthetic bank and UPI transaction data to understand spending habits, categorize expenses, track monthly trends, detect unusual transactions, and identify spending personality archetypes.

The project uses Python, Pandas, and NumPy to transform raw financial transaction data into meaningful insights through data cleaning, exploratory data analysis, and statistical calculations.

## 🎯 Project Objectives

- Clean and preprocess raw financial transaction data.
- Extract standardized vendor names from transaction descriptions.
- Categorize transactions into 12 spending categories.
- Analyze total credits, debits, and spending patterns.
- Identify monthly spending trends.
- Analyze spending behavior by time of day.
- Detect potentially unusual transactions using z-scores.
- Identify spending personality archetypes.
- Generate a structured financial analytics report.

## ✨ Key Features

### 1. Data Cleaning and Preprocessing
Handles inconsistent date formats, different currency formats, duplicate records, and messy transaction descriptions.

### 2. Vendor Extraction
Extracts standardized vendor names from transaction descriptions, such as Swiggy, Zomato, Zepto, and Amazon.

### 3. Expense Categorization
Classifies transactions into relevant spending categories to understand where money is being spent.

### 4. Spending Overview
Calculates total credits, total debits, top vendors, and top spending categories.

### 5. Monthly Spending Trends
Analyzes monthly transaction patterns to identify changes in spending behavior.

### 6. Time-of-Day Analysis
Examines transaction activity at different times of the day to identify spending habits.

### 7. Anomaly Detection
Uses manually calculated z-scores to flag potentially unusual transactions within their respective spending categories.

### 8. Spending Personality Archetypes
Identifies financial behavior patterns, including:

- The Foodie
- The Quick Commerce Junkie
- The Shopaholic
- The Investor
- The Late-Night Snacker
- The YOLO Spender
- The Disciplined Saver
- The Subscription Lover

## 🛠️ Technologies Used

- **Python** – Core programming language
- **Pandas** – Data cleaning and manipulation
- **NumPy** – Numerical calculations and statistical analysis
- **Datetime** – Date and time handling
- **Jupyter Notebook / Google Colab** – Development environment
- **Exploratory Data Analysis (EDA)** – Identifying patterns and insights

## 📂 Project Files

- `SpendDNA.ipynb` – Jupyter Notebook containing the project code and analysis.
- `rahul_transactions.csv` – Synthetic bank and UPI transaction dataset used for analysis.
- `final_report.txt` – Text file containing the final financial analytics report, including spending summaries, transaction patterns, anomaly detection results, and key insights.

## ⚙️ How to Run the Project

1. Download or clone this repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Upload the `rahul_transactions.csv` dataset to the notebook environment.
4. Ensure the dataset file path in the code matches the uploaded file.
5. Run all notebook cells in order to perform the financial transaction analysis and view the results.

## 📊 Expected Outcomes

- A summary of financial transactions.
- Total credit and debit analysis.
- Spending breakdown by category and vendor.
- Monthly spending trends.
- Time-of-day spending insights.
- Identification of potentially unusual transactions.
- Spending personality archetypes.
- A structured report highlighting key financial insights.

## 📋 Project Constraints

This project follows the restrictions specified in the project brief.

### Allowed

- Python fundamentals
- Pandas
- NumPy
- Datetime
- String methods
- Manual statistical calculations

### Not Allowed

- Machine learning, AI, or GenAI libraries
- Scikit-learn, SciPy Stats, or Statsmodels
- Matplotlib, Seaborn, or Plotly
- Regular expressions using the `re` module
- `collections.Counter`
- Automated data-profiling libraries
- External transaction-parsing libraries

The project emphasizes implementing the analysis using the permitted tools rather than relying on automated libraries.

## 📈 Key Insights

The project aims to reveal:

- Which spending categories account for the largest share of expenditure.
- How spending changes from month to month.
- Which vendors receive the most transactions or spending.
- When transactions are most frequently made.
- Which transactions are unusual compared with others in the same category.
- What spending archetypes best describe the observed transaction patterns.

## ⚠️ Disclaimer

This project uses synthetic financial transaction data for educational purposes. Transactions flagged as unusual are not necessarily fraudulent. The results are intended to demonstrate data analytics and statistical analysis techniques, not to provide financial advice.

## 🏁 Conclusion

SpendDNA demonstrates how Python-based data analytics can transform raw financial transaction data into meaningful insights. Through data cleaning, expense categorization, trend analysis, anomaly detection, and spending archetype identification, the project provides a structured understanding of financial behavior.

## 👩‍💻 Author

**Srusti Shree K H**

## 📑 Project Information

- **Project Name:** SpendDNA – Financial Transaction Analytics
- **Project Type:** Minor Project
- **Domain:** Data Analytics
- **Dataset:** Synthetic bank and UPI transaction data (`rahul_transactions.csv`)
- **Purpose:** Academic learning and analysis of financial transactions, spending patterns, expense categories, and unusual transactions.

---

*This project is intended for educational purposes and uses synthetic financial transaction data.*
