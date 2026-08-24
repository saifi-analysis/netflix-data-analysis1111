# netflix-data-analysis1111

Exploratory Data Analysis (EDA) Report
Insurance Sales & Customer Analysis
## 1. Project Overview
This project focuses on analysing insurance sales data by integrating multiple datasets, cleaning inconsistent records, performing feature engineering, and conducting Exploratory Data Analysis (EDA). The objective is to understand customer behaviour, product performance, sales trends, and business performance through data visualization and KPI analysis.
________________________________________
## 2. Project Objectives
•	Clean and pre-process raw insurance datasets.
•	Merge multiple tables into a single analytical dataset.
•	Perform feature engineering.
•	Calculate important business KPIs.
•	Visualize business performance using charts.
•	Identify business patterns to support decision-making.
________________________________________
3. Dataset Description
The project uses four datasets:
Dataset	Description
Customers	Customer information including demographic details.
Orders	Order details such as payment method, order date, and status.
Order Items	Product quantity, unit price, and order-level sales information.
Products	Product information including category and product name.
________________________________________
4. Libraries Used
•	Pandas
•	NumPy
•	Matplotlib
•	Seaborn
________________________________________
5. Data Loading
The datasets were imported using Pandas and stored in separate Data Frames before pre-processing.
 
________________________________________
6. Data Cleaning
The following pre-processing steps were performed: 
•	Removed duplicate records
 
 
•	Handled missing values
 
 
 
 
•	Corrected inconsistent data types
 
•	Cleaned categorical values
 
 
•	Converted date columns into datetime format
 
 
•	Removed unnecessary spaces and formatting issues
 
 
________________________________________
7. Data Integration
All four datasets were merged using appropriate keys to create a single dataset suitable for analysis.
Merged Tables:
•	Customers
•	Orders
•	Order Items
•	Products
 
________________________________________
8. Feature Engineering
Additional columns were created to improve analysis, including:
•	Revenue
 
•	Month
 
•	Year
 
•	Order Year
 
•	Session
 
________________________________________
9. Business KPIs
The following KPIs were calculated:
•	Total Revenue
 
•	Total Orders
 
•	Total Customers
 
•	Total Quantity Sold
 
•	Average Order Value
 
•	Average Quantity Per Order
 
•	Total Categories 
 
•	Repeat Customers
 
•	Average Product Price
 
•	Highest Single Order Value
 
•	Customer who Generate the highest Revenue
 
________________________________________
10. Exploratory Data Analysis
The following visualizations were created:
Revenue Trend over Time
Purpose:
To analyse monthly revenue growth and business performance over time.
 
________________________________________
Revenue by Product Category
Purpose: 
To compare sales performance across different product categories.
 
________________________________________
Top Revenue Generating Products
Purpose:
To identify the highest-performing products.
 
________________________________________
Top Customers by Revenue
Purpose:
To identify customers contributing the highest revenue.
 
________________________________________
Payment Method Distribution
Purpose:
To analyse customer payment preferences.
 
________________________________________
Customer Distribution by City
Purpose:
To identify cities with the highest customer concentration.
 
________________________________________
Quantity vs Revenue
Purpose:
To examine the relationship between quantity sold and generated revenue.
 
________________________________________
Repeat vs One-Time Customers
Purpose:
To understand customer retention and loyalty.
 
________________________________________
Product Price Distribution
Purpose:
To analyse the pricing distribution of products.
 
________________________________________
Revenue by Season
Purpose:
To evaluate seasonal sales performance.
 
________________________________________
11. Insights
Insights have been documented separately and are intentionally omitted from this report to avoid duplication.
• Overall Business Performance
The Company has generated a total revenue of ₹15 Cr by selling approximately 3,372 products across 1.2k orders, indicating strong overall business performance. 

• Customer Purchasing Behaviour
A total of 500 customers placed orders, with a Repeat Customer Rate of 72%, showing the company's ability to retain existing customers. 

• Average Order Analysis	
The Average Order Value (AOV) is ₹ 92k, while customers purchase an average of 2 products per order, reflecting the typical customer spending pattern. 

• Category Performance
Among 5 product categories, Accessories generated the highest revenue of ₹ 4, 00, 91,156, making it the company's best-performing category. 

• Top Selling Products
The Top 10 products contributed significantly to total revenue, with Dell Inspiron leading the list by generating approximately ₹ 2, 02, 57,133 in sales. 

• Customer Revenue Contribution
Customer C0142 generated the highest revenue of ₹ 14, 88,442, highlighting the importance of high-value customers in overall business growth. 

• Geographical Performance
Delhi emerged as the highest revenue-generating city with total sales of ₹ 4, 37, 46,782, indicating a strong customer base in that region. 

• Payment Method Preference
The most preferred payment method was UPI, accounting for approximately 523 orders (26.2%), suggesting customer preference toward this payment option.
 
• Seasonal Sales Trend
Sales peaked during the spring season with total revenue of ₹ 5, 21, 18,192, while the autumn season recorded the lowest revenue, indicating seasonal demand fluctuations. 

• Revenue Trend & Product Pricing
Monthly revenue showed a fluctuating trend with an overall decline throughout the year. The average product price was ₹46,635, and the highest single order value reached ₹10, 52,486, demonstrating the company's capability to generate high-value transactions.
________________________________________
12. Conclusion
The EDA successfully transformed raw insurance datasets into a structured analytical dataset through data cleaning, integration, and feature engineering. Business KPIs and visualizations provided a comprehensive understanding of customer behavior, product performance, revenue trends, payment preferences, and seasonal patterns. The analysis establishes a solid foundation for future predictive modeling, dashboard development, and data-driven business decision-making.
________________________________________

