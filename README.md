# Customer Shopping Analysis

# Project Overview

This project performs exploratory data analysis (EDA) on a customer shopping dataset obtained from Kaggle. The goal is to uncover patterns in sales, customer behavior, and payment preferences across multiple shopping malls in Istanbul, Turkey.

# Dataset

- Source: Kaggle
- Dataset Name: Customer Shopping Dataset
- Link: https://www.kaggle.com/datasets/mehmettahiraslan/customer-shopping-dataset
- Size: 99,457 rows and 10 columns
- Time Period: January 2021 to March 2023

# Columns Description

| Column | Description |
| invoice_no | Unique invoice number |
| customer_id | Unique customer identifier |
| gender | Gender of the customer |
| age | Age of the customer |
| category | Product category purchased |
| quantity | Number of items purchased |
| price | Price of the product |
| payment_method | Mode of payment used |
| invoice_date | Date of purchase |
| shopping_mall | Name of the shopping mall |

# Tools and Libraries Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

# Key Steps Performed

1. Loaded and explored the dataset using ds.info() and ds.describe()
2. Checked for null values and confirmed no missing data
3. Performed category-wise, mall-wise, gender-wise, and age group-wise sales analysis
4. Extracted month from invoice date for monthly trend analysis
5. Created visualizations using Matplotlib

# Key Findings

- Total revenue generated across all malls was approximately 68.5 million
- Clothing was the highest revenue-generating category at over 31 million, followed by Shoes and Technology
- Mall of Istanbul and Kanyon were the top two performing malls
- Female customers contributed approximately 59.7 percent of total sales
- Senior customers (age 50 to 70) spent the most compared to other age groups
- Cash was the most preferred payment method at 44.8 percent, followed by Credit Card at 35.1 percent
- January recorded the highest monthly sales, suggesting seasonal demand at the start of the year

# Visualizations

The following charts are included in the notebook:

- Bar chart: Total sales by product category
- Bar chart: Sales comparison across shopping malls
- Pie chart: Payment method distribution
- Line chart: Monthly sales trend
- Bar chart: Category-wise quantity sold
- Pie chart: Gender-wise sales distribution

# How to Run

1. Clone this repository
2. Download the dataset from the Kaggle link above and place it in the project folder
3. Open PROJECT_1_Python.ipynb in Jupyter Notebook
4. Update the file path in pd.read_excel() to match your local dataset location
5. Run all cells sequentially


# Author

Tanishq Solanki
Data Analyst | Fresher
