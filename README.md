# Airbnb NYC Data Cleaning Project

## Project Overview

This project focuses on cleaning and preprocessing the Airbnb NYC dataset containing 48,895 records and 16 features.

The objective was to improve data quality and prepare the dataset for reliable analysis and machine learning applications.

---

## Dataset Information

- Total Records: 48,895
- Total Features: 16
- Dataset Type: Airbnb Listings
- Tools Used: Python, Pandas, NumPy, Matplotlib, Seaborn

---

## Data Cleaning Tasks Performed

### Missing Value Handling

- Filled missing values in `name`
- Filled missing values in `host_name`
- Converted `last_review` to datetime format
- Filled missing values in `reviews_per_month`

### Duplicate Detection

- Checked for duplicate records

### Data Standardization

- Removed unwanted spaces from text columns
- Ensured consistent formatting

### Outlier Detection

- Applied IQR (Interquartile Range) Method
- Removed 2,972 price outliers

---

## Visualizations Generated

- Room Type Distribution
- Price Distribution
- Neighbourhood Group Distribution
- Correlation Heatmap

---

## Output

Generated a cleaned dataset ready for:

- Data Analysis
- Business Intelligence
- Machine Learning
- Predictive Modeling

---

## Project Structure

```text
Cleaning Data/
│
├── data/
│   └── customer_data.csv
│
├── notebooks/
│   └── data_cleaning.ipynb
│
├── outputs/
│   ├── cleaned_customer_data.csv
│   ├── room_type_distribution.png
│   ├── price_distribution.png
│   ├── neighbourhood_group_distribution.png
│   └── correlation_heatmap.png
│
├── README.md
└── requirements.txt