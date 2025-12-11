# 🚀 E-Commerce Sales Performance Dashboard

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/0fdbd75f-5b24-413e-89ef-23c60afff4e7" />

This project delivers a comprehensive, interactive dashboard built entirely in **Microsoft Excel**. It is designed to analyze over one year of raw online retail transaction data, employing advanced **Power Query (M-Language)** for robust data cleansing and **Pivot Tables/DAX** for detailed sales, customer, and product trend analysis. The goal is to enhance business understanding by providing actionable insights into seasonal variations and customer purchasing behavior.

---

## Project Overview

This dashboard serves as a complete solution for understanding the sales performance of an e-commerce operation. By transforming complex transactional data into clear, actionable visualizations, it allows stakeholders to quickly identify top-performing areas and critical business periods.

### **Tools and Technologies**

| Tool | Purpose | Key Functionality |
| :--- | :--- | :--- |
| **Microsoft Excel** | Primary Visualization Tool | Dynamic Charts, Slicers, and Timelines. |
| **Power Query** | Data Preparation & ETL | M-Language for robust data cleaning, merging, and shaping. |
| **Pivot Tables** | Data Aggregation | Summarizing sales metrics by dimension (Customer, Country, Month). |
| **DAX** | Calculated Measures | Defining complex business metrics like AOV. |

### **Key Performance Indicators (KPIs) Tracked**

* **Total Sales:** Aggregate revenue ($\sum \text{Quantity} \times \text{Unit Price}$).
* **Total Orders:** Count of unique invoices (transactions).
* **Average Order Value (AOV):** Total Sales / Total Orders.
* **Total Quantity Sold:** Sum of all individual items purchased.

---

# 🛠️ Skills Demonstrated

This project showcases end-to-end expertise in the data analysis workflow, emphasizing cleanliness, accuracy, and visualization.

### **1. Advanced Data Cleaning and Transformation (Power Query)**

* **Robust Data Cleansing:** Implemented M-Language logic to handle dirty data, specifically by **removing returns** (InvoiceNo starting with 'C') and filtering out records with **missing Customer IDs**.
* **Data Standardization:** Utilized a mapping table and merge operations to **standardize inconsistent country names** (e.g., mapping `EIRE` to `Irlandia`, `USA` to `United States of America`), ensuring accurate geographic analysis.
* **Feature Engineering:** Calculated critical new columns: `Total Sales`, `YearMonth`, and `HourOfDay` to facilitate deep time-series analysis.

### **2. Data Modeling and Business Intelligence (DAX & Pivot Tables)**

* **DAX Measure Definition:** Defined custom business logic (e.g., AOV) using Data Analysis Expressions to provide meaningful, calculated metrics in the report.
* **Dimensional Analysis:** Constructed multiple Pivot Tables to slice data across different dimensions (time, geography, customer ID) to generate specific reports like **monthly trends** and **customer leaderboards**.

### **3. Dynamic Reporting and Visualization**

* **Interactive Dashboard Design:** Designed a professional, single-view dashboard that provides a clear and concise summary of business performance.
* **User Controls:** Successfully integrated **Slicers** (for Country and Year-Month) and a **Timeline** to allow users to interactively filter all linked charts and KPIs, demonstrating the ability to build flexible, **self-service reports**.

---

# 📁 Files Included

| File Name | Description |
| :--- | :--- |
| `Project Online Retail Final.xlsx` | The main Excel dashboard containing the Power Query steps, Pivot Tables, and final interactive visualization. |
| `Project Online Retail Final.xlsx - Raw Data.csv` | The original, unfiltered transactional dataset. |
| `Project Online Retail Final.xlsx - Data Cleaning (Power Query).csv` | An intermediary file showing the dataset after Power Query transformation and feature engineering. |
| `Project Online Retail Final.xlsx - Mapping.csv` | The lookup table used to standardize country names. |
| `Project Online Retail Final.xlsx - Data Analysis (Pivot Tables).csv` | The underlying aggregated data used to drive the charts. |
| `Project Online Retail Final.xlsx - Guide.csv` | The internal documentation and KPI definitions. |
