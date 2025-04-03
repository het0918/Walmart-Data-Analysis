# Walmart-Data-Analysis

Data Analysis on Walmart sales dataset.
<br>
Author - Het Shah

Overview

This project analyzes Walmart sales data to uncover business insights, sales trends, and profitability patterns across different product categories and cities. The analysis includes data cleaning, exploratory data analysis (EDA), data visualization, and correlation analysis using Python.

Objectives

Clean and preprocess the dataset (handle missing values, remove duplicates, fix data types).
Perform exploratory data analysis (EDA) to understand sales distribution across categories, cities, and time.
Identify top-selling products and most profitable cities.
Analyze sales trends over time using time-series visualizations.
Compute and visualize correlations between numerical features.
Generate business insights to optimize sales and inventory management.

Dataset

Source: Walmart Sales Transactions (sample dataset).
Size: 9,969 records, 11 columns.

Features:

category: Product category (Fashion, Electronics, etc.)
city: City where the transaction occurred
unit_price: Price per unit of the product
quantity: Number of units purchased
date: Date of purchase
time: Time of purchase
payment_method: Payment type (Cash, Credit Card, Ewallet)
rating: Customer rating of the purchase
profit_margin: Profit percentage per product
total_revenue: Revenue per transaction (calculated)
total_profit: Profit per transaction (calculated)

Methodology

Step 1: Data Cleaning

Removed duplicate records.
Handled missing values.
Converted date and time columns to appropriate formats.
Removed currency symbols from unit_price and converted it to numerical format.

Step 2: Exploratory Data Analysis (EDA)

Identified most popular product categories and cities.
Analyzed payment method distribution.
Examined busiest sales days and peak hours.

Step 3: Sales Trends Analysis

Grouped sales by date to analyze daily trends.
Created a line plot for daily revenue trends.

Step 4: Profitability Analysis

Identified top categories and cities by profit.
Created a bar chart to visualize profitability by category.

Step 5: Correlation Analysis

Computed correlation between unit price, quantity, revenue, rating, and profit.
Created a heatmap to visualize feature correlations.

Key Insights

Fashion Accessories and Home & Lifestyle are the highest revenue-generating product categories.
Weslaco, Waxahachie, and Plano are the most profitable cities.
Tuesday and Thursday are the busiest sales days.
Credit card payments are the most common payment method, accounting for approximately 42 percent of transactions.
Strong positive correlation exists between total revenue and total profit.

Visualizations

Bar Charts: Most profitable categories and cities.
Line Plot: Sales trends over time.
Heatmap: Feature correlations.

Technologies Used

Python (Pandas, NumPy) – Data cleaning and transformation.
Matplotlib and Seaborn – Data visualization.

