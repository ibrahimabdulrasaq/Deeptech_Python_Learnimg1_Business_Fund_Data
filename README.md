# Deeptech_Python_Learnimg1_Business_Fund_Data
This repository demonstrates how I cleaned business funding data in Python as part of my learning journey as a 3MTT fellow

# 🧹 Business Funding Data Cleaning & Preparation (Python)

## 📌 Project Overview

This project focuses on cleaning and preprocessing a business funding dataset to improve data quality and prepare it for analysis.

The dataset contains information on funding activities such as investors, funding amounts, financing types, and dates. However, the raw data contains inconsistencies, missing values, and formatting issues that require cleaning before meaningful analysis can be performed.

---

## 🎯 Objective

To transform raw, messy funding data into a clean, structured dataset suitable for analysis and business insights.

---

## 📂 Dataset Description

The dataset includes the following key fields:

* Website Domain
* Effective Date
* Found At (Timestamp)
* Financing Type
* Investors & Investor Count
* Funding Amount (Raw & Normalized)
* Source URLs

---

## 🛠 Tools & Libraries Used

* Python
* Pandas
* NumPy

---

## 🧽 Data Cleaning Process

### 1. Data Loading

* Imported dataset from Excel into a Pandas DataFrame

---

### 2. Data Inspection

* Checked dataset structure using `.info()`
* Reviewed first few rows using `.head()`
* Assessed dataset size and column data types

---

### 3. Missing Value Analysis

* Calculated percentage of missing values across columns
* Identified high-missing columns:

  * Effective Date (~77%)
  * Financing Type (~69%)
  * Investors (~50%)

---

### 4. Handling Missing Values

* Filled missing values in **Effective Date** using the most frequent value (mode)
* Left some fields (e.g., Financing Type, Investors) unchanged due to lack of reliable replacement values

---

### 5. Data Consistency Checks

* Reviewed unique values in key columns
* Ensured consistency in categorical fields

---

### 6. Data Integrity Improvements

* Verified numerical columns such as **Amount Normalized**
* Ensured proper data types across columns

---

## 📊 Key Observations

* A significant portion of funding records lacked structured financing type information
* Investor-related fields were incomplete in ~50% of records
* Funding amounts were provided in mixed formats (e.g., $, £, million, billion) but normalized into a consistent numeric column

---

## ✅ Outcome

* Cleaned dataset with improved consistency and reduced missing values
* Standardized structure ready for:

  * Exploratory Data Analysis (EDA)
  * Visualization
  * Dashboard development (e.g., Power BI)

---

## 🚀 How to Run the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/business-funding-cleaning.git
   ```

2. Install dependencies:

   ```bash
   pip install pandas numpy
   ```

3. Open the notebook:

   ```bash
   jupyter notebook
   ```

---

## 📸 Preview

(Add screenshots of your notebook output here)

---

## 🔮 Future Improvements

* Handle missing values in Financing Type using domain knowledge or external data
* Perform feature engineering (e.g., extract year/month from dates)
* Build interactive dashboards using Power BI or Python libraries
* Integrate with live funding APIs

---

## 💡 Author

Ibrahim 
Data & BI Analyst

