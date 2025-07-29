This project presents a complete sales analysis using SQL Server. It includes deep exploration and performance breakdown of a retail dataset stored in a relational database. The goal was to derive insights about sales trends, customer behavior, and product performance over time.

🔍 Key Components:
🗃️ **Database Exploration**
Explored key tables: fact_sales, dim_products, and dim_customers.
Validated data types, identified null values and duplicates.
Ensured relational integrity using appropriate joins and keys.


📅**Changes in Sales Over Time**
Analyzed yearly sales trends.
Identified performance patterns across different years.


📈 **Cumulative Sales Analysis**
Calculated cumulative sales year-over-year.
Compared each year’s sales against the sum of all previous years.


📊 **Performance Analysis**
Computed average sales per product.
Measured differences in average sales over time.
Tracked yearly changes in total and average sales.

🧩 **Part-to-Whole Analysis**
Analyzed sales distribution by product category and subcategory.
Identified which categories contributed the most to overall revenue.

📐 **Data Segmentation**
Segmented data by customer age, sales frequency, and product variety.
Created grouped insights based on customer and product-level metrics.


 **Customer Report**
🎯 **Purpose:**
To consolidate key customer metrics and behavioral insights.
🔍 **Highlights:**
Extracts essential customer fields: name, age, transaction details.

**Segments customers into:**
VIP, Regular, and New
Age groups (e.g., <25, 25–40, 40+)

**Aggregates customer-level metrics:**
-Total number of orders
-Total sales value
-Total quantity purchased
-Customer lifespan (in months)

**Calculates valuable KPIs:**
-Recency: Months since last order
-Average Order Value (AOV)
-Average Monthly Spend

📦 **Product Report**
🎯 **Purpose:**
To consolidate product-level performance insights and segment products by contribution to revenue.

🔍 **Highlights:**
Extracts product attributes: name, category, subcategory, and cost.
Segments products into:
High-Performance
Mid-Range
Low-Performance (based on total revenue)

**Aggregates product-level metrics:**
Total orders
Total sales
Total quantity sold
Product lifespan (in months)

**Calculates key KPIs:**
Recency: Months since last sale
Average Order Value (AOV)
Average Monthly Revenue

🛠️ **Tools & Technologies:**
**SQL Server** – Database management and querying
**T-SQL** – Data analysis and aggregations
**GitHub** – Version control and project documentation

