# Customer Data Cleaning

## Project Overview

This project focuses on identifying and cleaning data quality issues in a customer dataset containing approximately 10,108 customer records.

The dataset was cleaned using Python and Pandas.

## Objectives

The main objectives were to identify and fix:

- Missing values
- Duplicate records
- Incorrect data types
- Inconsistent categorical values
- Invalid numerical values

## Dataset

File:

customer_data.csv

The dataset contains customer-related information such as:

- Customer ID
- Customer Age
- Gender
- Dependent Count
- Education Level
- Marital Status
- State
- Zipcode
- Car Ownership
- House Ownership
- Contact Information
- Customer Income
- Customer Satisfaction Score

## Data Cleaning Performed

### 1. Missing Values

Missing values were identified using:

`df.isnull().sum()`

Numerical missing values were handled using the median.

Categorical missing values were handled using the mode.

### 2. Duplicate Records

Duplicate records were identified using:

`df.duplicated().sum()`

Duplicate records were removed using:

`df.drop_duplicates()`

### 3. Data Types

Numerical columns such as:

- Customer Age
- Dependent Count
- Zipcode
- Customer Income
- Customer Satisfaction Score

were converted to appropriate numeric data types.

### 4. Inconsistent Values

Categorical values were standardized.

For example:

Male, male and M were standardized to:

Male

Yes, yes and Y were standardized to:

Yes

No, no and N were standardized to:

No

Extra spaces were also removed from text fields.

### 5. Validation

The cleaned dataset was checked again for:

- Missing values
- Duplicate records
- Data types
- Invalid age values
- Invalid satisfaction scores

## Tools Used

- Python
- Pandas
- VS Code
- Git
- GitHub

## Project Structure

```text
Customer-Data-Cleaning/
│
├── raw_data/
│   └── customer_data.csv
│
├── cleaned_data/
│   └── customer_data_cleaned.csv
│
├── reports/
│   └── data_quality_report.csv
│
├── Data_Cleaning.py
│
└── README.md
```
## Output

The cleaned dataset is available in:

cleaned_data/customer_data_cleaned.csv

A data quality report is available in:

reports/data_quality_report.csv

## Conclusion

The customer dataset was inspected and cleaned for missing values, duplicate records, incorrect data types, inconsistent categorical values and invalid numerical values. The final cleaned dataset is ready for further analysis and visualization.

## 🚀 Successfully Completed My Data Cleaning Project 🧹!
Worked on a customer dataset and performed data quality checks, missing-value treatment, duplicate removal, data-type correction, and value standardization using 🐍Python & Pandas 📊💻.
📌 Project successfully uploaded to GitHub.
One more project added to my Data Analytics portfolio! 📊✨
🚀 Another step forward in my Data Analytics journey!
