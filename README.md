Amazon Sales Analytics (SQL Project)

This project demonstrates the creation of a complete end-to-end SQL database system for an Amazon-style e-commerce platform.
It includes database design, data insertion, and advanced analytical queries to extract business insights.

Project Overview

This SQL project simulates a mini Amazon system with:
Customers

Orders

Products

Order Details

Product Reviews

The goal is to analyze sales performance, customer behavior, product demand, and revenue trends using SQL queries.

Database Structure

The project contains 5 main tables:

Table Name	Description
Customers	Stores customer info including name, email, and location
Products	Contains product details such as price, category, and stock
Orders	Stores order-level information like status & total amount
OrderDetails	Line-item details for each order, including quantity & subtotal
Reviews	Customer product reviews with ratings

All tables include primary keys and realistic sample data.
(You can add foreign keys as an optional improvement.)

Key Insights Generated

Using SQL queries, the project answers various real-world business questions:

1. Top 5 Best-Selling Products

Based on quantity sold.

2. Revenue by Category

Measures which product categories generate the highest revenue.

3. Top 5 Customers by Spending

Identifies high-value customers.

4. Average Rating per Product

Shows product satisfaction levels.

5. Low Stock Products

Helps identify restocking needs.

6. Most Cancelled Orders

Finds products linked to cancellations.

7. Customer Loyalty Analysis

Counts orders per customer.

8. Highest Value Categories

Based on average subtotal per product category.

9. Highest Rated Categories

Uses review data to determine customer satisfaction.

10. Top 5 Products by Revenue

Shows which products generate the most money.

11. Sales Ranking of Products

Uses ROW_NUMBER() window function.

🧠 Key SQL Concepts Used

Database & table creation

INSERT statements

JOINs (INNER JOIN)

GROUP BY, ORDER BY

Aggregate functions: SUM, AVG, COUNT

Window functions: ROW_NUMBER()

Subqueries

Update operations
