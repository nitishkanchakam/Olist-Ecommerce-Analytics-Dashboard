📊 Olist E‑Commerce Analytics Dashboard  
End‑to‑end analytics project using PostgreSQL + Power BI

This project analyzes the Olist e‑commerce dataset using SQL, PostgreSQL, and Power BI.  
It includes data cleaning, modeling, dashboard development, and business insights.


🚀 Tech Stack

- PostgreSQL – data storage, cleaning, modeling  
- SQL – transformations, fact/dimension modeling, business logic  
- Power BI Desktop – DAX, visuals, relationships  
- GitHub – version control & documentation


📁 Repository Structure

 The repository can include:

sql folder
- 01_staging_tables.sql  
- 02_fact_tables.sql  
- 03_dimension_tables.sql  
- 04_data_validation.sql  

model folder
- star_schema.png  
- relationships.png  

dashboard folder
- screenshots  
- dax_measures.txt  

docs folder
- project_overview.md  
- business_insights.md  


🗄️ Data Modeling

⭐ Star Schema (E‑Commerce Domain)

This project uses a star‑schema model to support fast analytics and clear relationships between tables.

Fact Table
- fact_order_items

Dimension Tables
- dim_customers  
- dim_sellers  
- dim_products  
- dim_orders  
- dim_payments  
- dim_reviews  
- dim_geolocation

This structure helps Power BI perform efficient joins and enables clean, scalable reporting.


📈 Power BI Dashboard Features

This dashboard provides a complete view of Olist’s e‑commerce performance through interactive visuals and KPIs.

Key Metrics
- Total Orders  
- Total Revenue  
- Average Review Score  
- Total Customers  

Trend Analysis
- Orders by Month  
- Revenue by Month  

Product Insights
- Top Product Categories  
- Best‑selling Products  

Customer Insights
- Customer distribution by state  
- Payment method breakdown  

Seller & Delivery Insights
- Seller revenue performance  
- Delivery delays  
- Estimated vs actual delivery time


🔍 Business Insights

This project uncovers several important business insights from the Olist dataset:

Customer Behavior
- Customers from major urban states place the highest number of orders.
- Payment installments are commonly used, showing flexible buying behavior.

Product Performance
- Certain product categories consistently drive high sales volume.
- Niche categories show lower demand but higher average prices.

Seller Performance
- A small group of sellers contribute a large share of total revenue.
- Seller performance varies significantly by product category.

Delivery Insights
- Delivery delays impact customer review scores.
- Actual delivery time often exceeds estimated delivery time.

These insights help identify opportunities to improve customer satisfaction, optimize logistics, and strengthen seller performance.


🔧 Project Workflow

This project follows a complete end‑to‑end analytics workflow used in real data teams:

1. Data Extraction
- Loaded the Olist e‑commerce dataset into PostgreSQL.
- Reviewed raw tables such as orders, customers, sellers, products, payments, and reviews.

2. Data Cleaning & Preparation
- Removed duplicates and invalid records.
- Standardized date formats and categorical fields.
- Validated relationships between tables.

3. SQL Data Modeling
- Designed a star‑schema model.
- Created fact and dimension tables using SQL transformations.
- Ensured referential integrity and optimized joins.

4. Power BI Development
- Imported modeled tables into Power BI.
- Built relationships based on the star schema.
- Created DAX measures for KPIs and calculations.
- Designed interactive visuals and slicers.

5. Insight Generation
- Analyzed customer behavior, product performance, seller trends, and delivery delays.
- Identified business opportunities and operational bottlenecks.

This workflow demonstrates real‑world analytics engineering, BI development, and business analysis skills.


🧠 Key Skills Demonstrated

This project showcases practical, job‑ready skills used in real analytics roles:

🔹 SQL & Data Engineering
- Writing complex SQL queries  
- Building fact and dimension tables  
- Cleaning and transforming raw datasets  
- Designing scalable data models  

🔹 Business Intelligence (Power BI)
- Creating interactive dashboards  
- Building DAX measures for KPIs  
- Designing clear, professional visuals  
- Establishing relationships using star schema  

🔹 Analytical Thinking
- Identifying trends in customer behavior  
- Understanding product and seller performance  
- Evaluating delivery delays and operational bottlenecks  
- Translating raw data into actionable insights  

🔹 Real‑World Project Execution
- End‑to‑end workflow from raw data → SQL → BI dashboard  
- Documentation and storytelling through README  
- Presenting insights clearly for business stakeholders  

This project demonstrates the full analytics lifecycle and highlights your ability to work with data from extraction to insight.


🏁 Conclusion

This project demonstrates a complete end‑to‑end analytics workflow using SQL, PostgreSQL, and Power BI.  
From raw data to a fully interactive dashboard, it highlights strong skills in data modeling, BI development, and business insight generation.

The Olist e‑commerce dataset provides a rich foundation for understanding customer behavior, product performance, seller trends, and delivery operations.  
This analysis showcases how structured data modeling and clear visual storytelling can support better business decisions.

Thank you for visiting this project!  
