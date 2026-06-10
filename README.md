
https://github.com/user-attachments/assets/3aae6063-cce7-4b11-8be8-163a17e15d9d

📊 E-Commerce Sales Dashboard | Power BI

📌 Project Overview

The E-Commerce Sales Dashboard is an end-to-end Business Intelligence solution built using Power BI to analyze sales performance, customer behavior, product demand, and geographical distribution of sales. The dashboard transforms raw transactional data into actionable insights through interactive visualizations, KPI tracking, and advanced data modeling techniques.

Designed using a Star Schema Data Model, this project demonstrates industry-standard BI practices, including DAX calculations, data transformation, and dashboard storytelling to support data-driven decision-making.

🎯 Business Problem		  		    

E-commerce businesses generate large volumes of transactional data daily. Without proper analysis, identifying sales trends, customer behavior, and growth opportunities becomes challenging.
This dashboard helps stakeholders:
Monitor overall business performance
Track sales and revenue trends
Identify top-performing products
Understand customer purchasing patterns
Analyze geographical sales distribution
Measure Year-over-Year (YoY) growth


📊 Key Performance Indicators (KPIs)
KPI	Value
Revenue	$105M
Quantity Sold	6M
Average Unit Price	$17.6
Customer Insights	9.191K
YoY Growth Analysis	Dynamic
Geographical Analysis	Global

✨ Features
📈 Sales Performance Analysis
Revenue Monitoring
Quantity Sold Tracking
Average Unit Price Analysis
Monthly Sales Trends

👥 Customer Insights
Customer Spending Analysis
Top Customers Identification
Customer Growth Monitoring

📦 Product Analysis
Top 5 Products by Quantity Sold
Product Performance Comparison

🌍 Geographic Analysis
Country-wise Sales Distribution
Interactive Global Sales Map

📅 Time Intelligence
Year-over-Year (YoY) Comparison
Historical Trend Analysis

🎛 Interactive Reporting
Dynamic Filters
Slicers
Drill-Down Analysis
Responsive Visualizations

🏗 Data Model Architecture
This project follows a Star Schema Data Model consisting of one central fact table connected to multiple dimension tables.
Fact Table

fact_table

Column Name

customer_key

item_key

payment_key

quantity

sales

store_key

time_key

unit

unit_price

Dimension Tables

customer_dim

Column

customer_key

item_dim

Column

item_key

store_dim

Column

store_key

time_dim

Column

time_key

Date

Trans_dim

Column

payment_key

bank_name

trans_type

📐 Data Modeling Approach
Implemented a Star Schema architecture for optimized query performance.
Established one-to-many relationships between dimension and fact tables.
Utilized surrogate keys for efficient joins.
Built dedicated measure tables for better DAX organization.
Applied best practices for scalable reporting and maintainability.

🛠 Tools & Technologies
Tool	Purpose
Power BI Desktop	Dashboard Development
DAX	Business Calculations
Power Query	Data Transformation
Data Modeling	Relationship Management
Business Intelligence	Insight Generation

📚 DAX Measures Implemented
Revenue Metrics
Total Revenue
Previous Year Revenue
Revenue Growth %
Sales Metrics
Total Quantity Sold
Average Unit Price
Customer Metrics
Total Customers
Customer Growth %
Time Intelligence
YoY Sales %
Previous Year Comparison

📈 Business Insights Generated
Identified top-selling products contributing most to revenue.
Analyzed customer purchasing patterns.
Measured Year-over-Year business growth.
Evaluated regional sales performance across countries.
Monitored monthly sales fluctuations and trends.
Tracked overall business health using KPI indicators.

🎓 Skills Demonstrated
Data Analytics
Data Cleaning
Data Transformation
Exploratory Data Analysis
Power BI
Dashboard Design
Data Modeling
DAX Development
KPI Creation
Business Intelligence
Performance Monitoring
Trend Analysis
Executive Reporting
Data Storytelling

📂 Repository Structure
E-Commerce-Sales-Dashboard/
│
├── Dataset/
│   └── Ecommerce_Data.xlsx
│
├── Dashboard/
│   └── Ecommerce_Sales_Dashboard.pbix
│
├── Screenshots/
│   ├── Dashboard.png
│   └── Data_Model.png
│
├── README.md
└── LICENSE

🚀 Future Enhancements
Profitability Analysis
Customer Segmentation
RFM Analysis
Sales Forecasting
Category Performance Dashboard
Executive Summary Page
Advanced Drill-through Reports

Acknowledgements:
Special thanks to Freedom Oboh for his insightful Power BI tutorials and guidance, which played a significant role in my learning journey.

Connect With Me

🔗 LinkedIn: www.linkedin.com/in/tharunbandaru Email: bandarutharunkumar0@gmail.com

