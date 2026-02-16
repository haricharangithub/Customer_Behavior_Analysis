📊 Customer Shopping Behavior Analysis
📌 Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories.

The goal is to understand how customers shop, identify spending patterns, analyze product preferences, and uncover factors that influence purchasing decisions such as discounts, subscriptions, age groups, and shipping preferences.

This project demonstrates an end-to-end data analytics workflow using Python, MySQL, and Power BI.

🎯 Business Problem

A retail company wants to better understand customer shopping patterns to:

Increase sales

Improve customer satisfaction

Strengthen customer loyalty

Optimize marketing and product strategies

The key question addressed in this project is:

How can the company use customer shopping data to identify trends, improve engagement, and make better business decisions?

📂 Dataset Information

Total Records: 3,900

Total Columns: 18

Missing Values: 37 missing values in the review_rating column

Key Features

Customer Details

Age

Gender

Location

Subscription Status

Purchase Details

Item Purchased

Category

Purchase Amount

Season

Size

Color

Shopping Behavior

Discount Applied

Promo Code Used

Previous Purchases

Purchase Frequency

Review Rating

Shipping Type

🐍 Data Cleaning & Preparation (Python)

The following steps were performed:

Loaded dataset using pandas

Checked data structure using df.info() and describe()

Handled missing values (filled review ratings using median by category)

Standardized column names to snake_case

Created new features:

age_group

purchase_frequency_days

Removed redundant column (promo_code_used)

Connected Python to MySQL

Uploaded cleaned dataset into the database for SQL analysis

🗄️ Data Analysis (MySQL)

Structured business queries were written to answer key questions:

Revenue by Gender

High-Spending Discount Users

Top 5 Products by Rating

Shipping Type Comparison

Subscribers vs Non-Subscribers

Discount-Dependent Products

Customer Segmentation (New, Returning, Loyal)

Top 3 Products per Category

Repeat Buyers & Subscriptions

Revenue by Age Group

These queries helped identify revenue drivers, customer loyalty patterns, and product performance.

📊 Power BI Dashboard

An interactive Power BI dashboard was created to visualize:

Total Customers

Average Purchase Amount

Average Review Rating

Revenue by Category

Sales by Category

Revenue by Age Group

Subscription Distribution

Shipping Type Insights

The dashboard enables stakeholders to easily explore trends and make data-driven decisions.

💡 Business Recommendations

Boost subscription programs with exclusive benefits

Strengthen loyalty programs for repeat buyers

Review discount strategy to balance profit and sales

Promote top-rated and best-selling products

Use targeted marketing for high-revenue age groups

📈 Key Insights

Certain age groups contribute more revenue

Loyal customers form a significant customer base

Express shipping users tend to spend slightly more

Some products heavily depend on discounts

Subscriptions influence long-term customer value

🛠️ Tools & Technologies Used

Python (Pandas, NumPy)

MySQL

Power BI

GitHub

📌 Conclusion

This project demonstrates how raw transactional data can be transformed into meaningful business insights.

By analyzing customer behavior, the company can improve marketing strategies, enhance customer loyalty, optimize pricing strategies, and drive long-term revenue growth.
