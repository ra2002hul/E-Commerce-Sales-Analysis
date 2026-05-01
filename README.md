# E-Commerce-Sales-Analysis
📊 Product Line and Sales Trends Dashboard


📌 Project Overview

This project demonstrates an end-to-end retail sales analytics workflow, covering data preparation, transformation, modeling, and visualization.
Raw transactional sales data was cleaned and transformed using Excel and Power Query, then analyzed and visualized through an interactive Power BI dashboard.

The dashboard uncovers key business insights related to product line performance, customer behavior, city-wise sales trends, revenue patterns, and profitability, enabling stakeholders to make data-driven decisions.

🏷️ Domain

Retail Sales Analytics | Business Intelligence | Consumer Behavior Analysis

🎯 Project Objectives
Convert raw sales data into meaningful business insights
Analyze product line performance across revenue, profit, and ratings
Understand customer behavior by gender, customer type, city, and payment method
Identify top-performing cities, branches, and categories
Build an interactive Power BI dashboard with KPIs, slicers, and drill-throughs
Demonstrate strong data modeling, DAX, and visualization skills
📂 Dataset Overview
Source: Retail Supermarket Sales Data (2025)
Format: CSV / Excel transactional data
Transactions: 1,000
Units Sold: 5,510
Revenue: 322.97K
Cities: Yangon, Mandalay, Naypyitaw
Branches: A, B, C
🧾 Key Attributes
Invoice ID
Branch, City
Customer Type (Member / Normal)
Gender
Product Line
Unit Price, Quantity
Tax (5%), Total
COGS, Gross Income
Rating
Date, Payment Method
🛠️ Tools & Technologies
Excel – Data cleaning, validation, duplicates removal
Power Query – Advanced transformations & calculated columns
Power BI – Data modeling, DAX measures, dashboard creation
🔄 Project Workflow
1. Data Cleaning & Preprocessing (Excel / Power Query)
Removed duplicate records using Invoice ID
Handled missing values in ratings and customer fields
Standardized date and numeric formats
Validated tax calculations (5%)
Converted data types for numerical accuracy
Calculated Columns Created:
Gross Profit per Unit
Revenue per Unit
Profit Margin (%)
Rating Category (Excellent / Good / Poor)
Branch–City Combination
Product Line Performance Index
Customer Category (Gender + Type)
2. Data Modeling & DAX (Power BI)
Implemented star schema with Fact and Dimension tables
Created a Date table for time intelligence
Established one-to-many relationships
Key DAX Measures:
Total Revenue
Total Quantity
Total Tax
Total Gross Income
Cost of Goods Sold (COGS)
Average Transaction Value
Profit Margin %
Average Rating
Revenue Growth %
Gender-wise customer count
📊 Dashboard Pages & Visuals
🔹 Overview Page
KPI Cards (Revenue, Quantity, Tax, Transactions)
Gross Income trend (Area Chart)
Product Line comparison (Clustered Column Chart)
City, Customer Type & Payment slicers
🔹 Gender Analysis Page
Gender-wise KPIs
Gender distribution (Pie Chart)
Payment preference by gender
Product line popularity by gender
🔹 City Analysis Page
City-wise revenue & quantity
Product line performance by city (Matrix)
Sales trends over time
Gross margin comparison
🔹 Revenue Analysis Page
Quantity vs Revenue comparison
Unit price vs tax by product line
Gross income distribution
🔹 Rating Analysis Page
Rating by product line
Rating vs COGS relationship
Rating trends over time
🔍 Key Insights & Findings
Strong Overall Sales Performance
Revenue: 322.97K
Transactions: 1,000
Profit Margin: ~4.7%
Balanced Customer Demographics
Male: 51.98%
Female: 48.02%
Opportunity to increase loyalty conversions
City-Level Dominance
Naypyitaw leads with 34.24% of total revenue
Highest quantity sold and stable margins
Product Line Performance
Fashion accessories: highest unit price & tax contribution
Food & beverages: consistently high demand
Electronic accessories: stable performance across all cities
Payment Behavior
Cash, Credit Card, and E-wallet used almost evenly
Indicates strong digital payment adoption
Seasonal & Time Trends
Sales peaks around specific transaction periods
Ideal windows for promotions and campaigns
📈 Business Impact
Identifies top revenue drivers by product and city
Highlights inventory optimization opportunities
Enables city-specific marketing strategies
Supports pricing, promotion, and cost optimization decisions
✅ Conclusion

This project successfully transforms raw retail sales data into actionable business intelligence using Excel, Power Query, and Power BI.
The interactive dashboard empowers stakeholders to analyze sales performance across products, customers, cities, and time, leading to smarter operational and strategic decisions.

🚀 Future Enhancements
Integrate competitor pricing & market trend data
Add demand forecasting models
Enable real-time data refresh
Expand dashboard with profitability simulations

