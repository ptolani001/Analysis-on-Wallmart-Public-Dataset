# Analysis-on-Wallmart-Public-Dataset
SQL Project Overview

The primary objective of this project is to delve into the Walmart Sales data, with the goal of comprehending the performance of top branches and products, analyzing the sales trends of various products, and understanding customer behavior. The project aims to identify opportunities for enhancing and optimizing sales strategies. The dataset utilized for this exploration originates from the Kaggle Walmart Sales Forecasting Competition.

Project Objectives

The central focus of this project is to gain insights into Walmart's sales data, aiming to comprehend the diverse factors influencing the sales of different branches.

Data Information

The dataset, acquired from the Kaggle Walmart Sales Forecasting Competition, encompasses sales transactions from three Walmart branches situated in Mandalay, Yangon, and Naypyitaw. The dataset comprises 17 columns and 1000 rows, providing detailed information about various aspects of each transaction.

Column Descriptions:

invoice_id: Invoice of the sales made (VARCHAR(30))
branch: Branch at which sales were made (VARCHAR(5))
city: The location of the branch (VARCHAR(30))
customer_type: The type of the customer (VARCHAR(30))
gender: Gender of the customer making a purchase (VARCHAR(10))
product_line: Product line of the product sold (VARCHAR(100))
unit_price: The price of each product (DECIMAL(10, 2))
quantity: The amount of the product sold (INT)
VAT: The amount of tax on the purchase (FLOAT(6, 4))
total: The total cost of the purchase (DECIMAL(10, 2))
date: The date on which the purchase was made (DATE)
time: The time at which the purchase was made (TIMESTAMP)
payment_method: The total amount paid (DECIMAL(10, 2))
cogs: Cost Of Goods sold (DECIMAL(10, 2))
gross_margin_percentage: Gross margin percentage (FLOAT(11, 9))
gross_income: Gross Income (DECIMAL(10, 2))
rating: Rating (FLOAT(2, 1))
Analysis Overview

Product Analysis: Conduct an analysis to understand the different product lines, identify the best-performing product lines, and pinpoint areas for improvement.
Sales Analysis: Investigate sales trends to evaluate the effectiveness of each sales strategy and determine necessary modifications to boost sales.
Customer Analysis: Uncover various customer segments, analyze purchase trends, and assess the profitability of each customer segment.
Approach Used

Data Wrangling: Initial data inspection to detect and handle NULL values using data replacement methods.
Feature Engineering: Generate new columns like time_of_day (Morning, Afternoon, Evening), day_name (extracted days of the week), and month_name (extracted months of the year) for deeper insights.
Exploratory Data Analysis (EDA): Perform EDA to answer project objectives and questions.
