# MySQL-Project-for-Pizza-Sales-Analysis

## MySQL Project for Pizza Sales Analysis

This MySQL project focuses on analyzing pizza sales data, allowing us to gain insights into customer preferences, revenue distribution, and ordering patterns. Using SQL queries, we explore several key performance indicators (KPIs) to understand the pizza business better. The analysis includes retrieving order data, aggregating sales information, and calculating various metrics such as total orders, top-selling pizza types, and revenue contributions.

### **Project Overview**

The project involved creating a **MySQL database** and designing a set of tables to store and analyze pizza sales data. Using SQL queries, we were able to answer key business questions and provide valuable insights into the pizza ordering trends. The steps are outlined as follows:

1. **Database Setup**
    - Created a new MySQL database named **pizza_sales** to store sales and product data.
    - Designed and populated tables with relevant data, including tables for pizza types, orders, sales, and categories.

2. **SQL Queries and Analysis**
    - Various SQL queries were written to solve the following business questions:
      
      1. **Retrieve the Total Number of Orders Placed**: A query was executed to count the total number of orders in the database.
      2. **Identify the Most Common Pizza Size Ordered**: A query was written to find which pizza size is ordered the most.
      3. **List the Top 5 Most Ordered Pizza Types Along with Their Quantities**: A query was written to find the top 5 pizza types based on order frequency and their corresponding quantities.
      4. **Category-Wise Distribution of Pizzas**: Relevant tables were joined to analyze how pizzas are distributed across different categories (e.g., Veg, Non-Veg, etc.).
      5. **Average Number of Pizzas Ordered per Day**: Orders were grouped by date, and the average number of pizzas ordered per day was calculated.
      6. **Top 3 Most Ordered Pizza Types Based on Revenue**: A query was used to determine which pizza types generated the most revenue.
      7. **Percentage Contribution of Each Pizza Type to Total Revenue**: The percentage of total revenue contributed by each pizza type was calculated using SQL aggregation.

3. **Further Analysis**
    - Additional queries were written to explore trends and insights, such as:
      - **Total Revenue by Pizza Type**: Querying revenue generated for each type of pizza.
      - **Orders by Time of Day**: Analyzing which times of the day have the highest volume of orders.
      - **Customer Preferences**: Identifying preferences based on the number of orders placed by customers for different pizza types and sizes.
      - **Regional Analysis**: If applicable, analyzing sales data based on regions or stores to identify regional preferences.

4. **Data Modeling and Relationships**
    - Tables were designed with proper relationships to represent the structure of the data, including:
      - **Pizza Types Table**: Contains information about different pizza types, sizes, and categories.
      - **Orders Table**: Contains data about each order, including customer information, order date, and pizza types ordered.
      - **Sales Table**: Contains information on the revenue generated per pizza type for each order.

5. **Advanced SQL Techniques**
    - Joins: Various types of joins (INNER JOIN, LEFT JOIN) were used to combine data from multiple tables and analyze it.
    - Aggregations: SUM, COUNT, and GROUP BY clauses were used to calculate key metrics, such as total orders, average pizzas per day, and total revenue.
    - Subqueries: Some queries were optimized with subqueries to derive insights based on specific conditions.

### **Key Features**
- **SQL Querying**: SQL queries were used to retrieve, aggregate, and analyze sales data.
- **Joins and Aggregations**: Data from multiple tables were combined and analyzed using SQL join operations and aggregate functions.
- **Data Modeling**: Designed tables and established relationships to ensure a robust and efficient database structure.
- **Business Insights**: Provided actionable insights on top-selling pizzas, order volume, and revenue distribution.

### **Key Queries and Insights**
- **Total Number of Orders**: Easily retrieve the total number of orders placed in the database.
- **Most Common Pizza Size Ordered**: Identified the most popular pizza size across all orders.
- **Top 5 Most Ordered Pizza Types**: Lists the top 5 pizza types ordered and their quantities.
- **Category-Wise Pizza Distribution**: Analyzed pizza sales based on categories (e.g., Veg, Non-Veg).
- **Average Orders Per Day**: Provides insights into the average pizza orders placed each day.
- **Top 3 Pizza Types by Revenue**: Identifies the pizza types generating the most revenue.
- **Revenue Contribution by Pizza Type**: Calculates the percentage revenue contribution of each pizza type.

### **Technologies Used**
- **MySQL Workbench**: Used for creating and managing the database, executing queries, and visualizing results.
- **SQL**: Used to write complex queries to retrieve, filter, and analyze the sales data.
- **Data Modeling**: Designed database tables with the correct relationships to enable efficient querying.

### **How to Use**
1. Open MySQL Workbench and connect to the **pizza_sales** database.
2. Use the SQL queries to analyze different aspects of the pizza sales data.
3. Run queries to answer business questions, such as identifying the most common pizza sizes or analyzing the top 5 pizza types based on quantity and revenue.
4. Modify or extend the queries to explore additional insights, such as customer behavior and regional sales analysis.

### **Conclusion**
This MySQL project provides a comprehensive analysis of pizza sales data, helping businesses gain insights into customer preferences, product performance, and revenue generation. The SQL queries and database structure enable efficient data retrieval and analysis, offering valuable information for optimizing pizza sales strategies.
