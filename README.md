# 🛒 E-commerce Data Analysis & Cleaning Challenge (Olist Brazil)

## 📌 Project Overview
This project focuses on performing a comprehensive **Exploratory Data Analysis (EDA)** and **Data Cleaning** on the real-world Olist E-commerce dataset from Brazil. The goal was to transform messy, raw data into an analysis-ready format to uncover business insights regarding delivery performance and customer payment behavior.

## 🛠️ Tech Stack & Tools
* **Language:** Python 3.x
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Advanced EDA:** Sweetviz (Automated Data Profiling)
* **Environment:** Jupyter Notebook / Anaconda

## 🧹 Key Data Cleaning Steps
* **Data Integration:** Merged multiple relational tables (Orders, Payments, Products, and Category Translations) into a master dataframe.
* **Handling Missing Values:** Identified and treated null values in delivery timestamps and product details.
* **Data Type Correction:** Converted date-related columns from string objects to `datetime` objects for time-series analysis.
* **Outlier Management:** Filtered out logical inconsistencies, such as orders with delivery times exceeding 100 days or negative durations.

## 📊 Business Insights & Findings
* **Delivery Performance:** The average delivery time is **12.11 days**. Significant delays were noted in specific product categories like 'Office Furniture'.
* **Payment Trends:** Over **75%** of customers prefer **Credit Cards**, with a high volume of transactions involving multiple installments.
* **Customer Satisfaction:** A clear negative correlation was identified between delivery delays and customer review scores.

## 📂 Repository Structure
* `Python_analysis.ipynb`: The complete Jupyter Notebook containing data cleaning, merging, and visualization logic.
* `Final_Report.html`: An interactive, automated EDA report generated using Sweetviz for a 360-degree data overview.
* `olist_data/`: (Not uploaded due to size) Dataset sourced from [Kaggle - Olist Brazilian E-Commerce](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).

## 🚀 How to Run
1. Clone the repository.
2. Install dependencies: `pip install pandas numpy seaborn matplotlib sweetviz`.
3. Open `Python_analysis.ipynb` in Jupyter Notebook and run all cells.
