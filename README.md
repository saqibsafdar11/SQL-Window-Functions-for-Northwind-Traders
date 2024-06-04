## SQL Window Functions for Northwind Traders
SQL Window Functions used for analysing the database 

**Project: SQL Window Functions for Northwind Traders**
**Description**
This project aims to provide valuable insights to the management of [Northwind Traders](https://github.com/pthom/northwind_psql/tree/master) by leveraging [PostgreSQL window functions](https://www.postgresql.org/docs/current/tutorial-window.html) on the Northwind database. The focus areas include:

- Evaluating Employee Performance: Recognizing top-performing employees and identifying those needing support.
- Understanding Product Sales and Category Performance: Optimizing inventory and marketing strategies.
- Analyzing Sales Growth: Identifying trends, monitoring progress, and making accurate forecasts.
- Evaluating Customer Purchase Behavior: Targeting high-value customers with promotional incentives.

A database schema diagram is provided within the notebook for reference.

**Sections**
1. Exploring the Northwind Database: Initial data exploration and combining various tables to gather detailed information.
2. Ranking Employee Sales Performance: Using CTEs and the RANK function to rank employees based on total sales.
3. Running Total of Monthly Sales: Monitoring sales growth by calculating the running total of monthly sales.
4. Month-over-Month Sales Growth Rate: Using the LAG function to calculate month-over-month growth rates.
5. Identifying High-Value Customers: Targeting customers with above-average order values for promotional incentives.
6. Percentage of Sales for Each Category: Understanding sales composition to guide inventory and marketing strategies.
7. Top Products Per Category: Identifying and ensuring stock of star performers within each product category.

**Libraries Used**
- os: To access environment variables.