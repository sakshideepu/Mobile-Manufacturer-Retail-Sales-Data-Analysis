Mobile Manufacturer Retail Sales SQL Analysis

Project Overview

This project analyzes a retail mobile phone sales dataset using Microsoft SQL Server. The objective is to transform transactional sales data into meaningful business insights through SQL-based analysis. The project focuses on sales performance, customer behavior, product performance, manufacturer contribution, and geographic trends to support data-driven business decisions.



Business Objective

The primary objective of this project is to answer key business questions, including:

- How much revenue has the business generated?
- Which manufacturers and products perform the best?
- Who are the most valuable customers?
- How do sales change over time?
- Which geographic regions contribute the most revenue?
- What business recommendations can be made based on the analysis?


Dataset Overview

The dataset follows a star schema and consists of one fact table and five dimension tables.

Fact Table

- "fact_transactions" – Stores transaction-level sales data.

Dimension Tables

- "dim_customer" – Customer information
- "dim_model" – Mobile model details
- "dim_manufacturer" – Manufacturer information
- "dim_location" – Country, state, city, and ZIP code
- "dim_date" – Date, month, quarter, and year information



Database Schema

The project uses a star schema, where the fact table is connected to multiple dimension tables through primary and foreign key relationships. This structure is commonly used in data warehousing because it simplifies analytical queries and improves reporting efficiency.



Data Validation

Before performing analysis, the dataset was validated by:

- Checking row counts
- Identifying NULL values
- Detecting duplicate records
- Verifying key relationships
- Checking invalid or negative values



SQL Skills Demonstrated

- INNER JOIN
- GROUP BY
- HAVING
- ORDER BY
- Aggregate Functions
- CASE Expressions
- Subqueries
- Common Table Expressions (CTEs)
- Window Functions
- ROW_NUMBER()
- DENSE_RANK()
- NTILE()
- LAG()
- Date Functions



Project Analysis

The project is divided into the following analytical sections:

1. Business KPI Analysis

- Total Revenue
- Total Quantity Sold
- Total Transactions
- Total Customers
- Average Order Value
- Average Selling Price per Unit

2. Sales Performance Analysis

- Revenue by Year
- Revenue by Quarter
- Revenue by Month
- Month-over-Month Revenue Growth
- Best Performing Time Period

3. Product & Manufacturer Analysis

- Revenue by Manufacturer
- Quantity Sold by Manufacturer
- Top Performing Models
- Lowest Performing Models
- Revenue Contribution by Manufacturer
- Best Model within Each Manufacturer

4. Customer Analysis

- Top Customers by Revenue
- Customer Lifetime Value
- Average Customer Spend
- Purchase Frequency
- Customer Spending Segmentation

5. Geographic Analysis

- Revenue by Country
- Top Performing Cities
- Average Revenue by State
- Revenue Contribution by State
- Best Performing City within Each State



Key Business Insights

The analysis provides insights into:

- Revenue trends over time
- High-performing manufacturers and mobile models
- Customer purchasing behavior
- High-value customer segments
- Geographic sales performance
- Product performance across different business dimensions



Business Recommendations

- Increase inventory for consistently high-performing products.
- Strengthen partnerships with top-performing manufacturers.
- Develop loyalty programs for high-value customers.
- Focus marketing efforts on high-performing regions.
- Review low-performing products for pricing or promotional improvements.
- Use sales trends to improve inventory planning and forecasting.



Project Structure

Retail-Sales-SQL-Analysis

---Dataset
---SQL Scripts
  ├── 01_Create_Tables.sql
  ├── 02_Data_Validation.sql
  ├── 03_KPI_Analysis.sql
  ├── 04_Sales_Performance_Analysis.sql
  ├── 05_Product_Manufacturer_Analysis.sql
  ├── 06_Customer_Analysis.sql
  └── 07_Geographic_Analysis.sql
├── Outputs/
├── Images/
├── README.md
├── Business_Report.md



Tools Used

- Microsoft SQL Server
- SQL Server Management Studio (SSMS)
- GitHub


How to Run the Project

1. Create the database in SQL Server.
2. Execute the table creation script.
3. Import or load the dataset into the tables.
4. Run the SQL analysis scripts in sequence.
5. Review the generated outputs and business report.


Author

Sakshi Deepu
