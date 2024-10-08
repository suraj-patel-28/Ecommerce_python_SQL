# E-commerce Data Analysis

This repository contains a comprehensive analysis of an e-commerce dataset. The analysis is performed using Python libraries such as Pandas, Matplotlib, Seaborn, and MySQL Connector. The goal is to gain insights into customer behavior, sales trends, and product performance.

## Project Overview

The project involves several SQL queries and data visualizations to answer various business questions and perform statistical analyses. Below is a summary of the key analyses performed:

1. **Unique Cities**: List of all unique cities where customers are located.
2. **Orders in 2017**: Count of orders placed in 2017.
3. **Total Sales by Category**: Total sales per product category.
4. **Percentage of Orders Paid in Installments**: Percentage of orders that were paid in installments.
5. **Customers by State**: Count of customers from each state, visualized as a bar chart.
6. **Orders per Month in 2018**: Number of orders placed each month in 2018, visualized with a bar plot.
7. **Average Products per Order by City**: Average number of products per order, grouped by customer city.
8. **Revenue Contribution by Category**: Percentage of total revenue contributed by each product category.
9. **Correlation between Price and Order Count**: Correlation between product price and the number of times a product has been purchased.
10. **Total Revenue by Seller**: Total revenue generated by each seller, ranked by revenue.
11. **Moving Average of Order Values**: Moving average of order values for each customer.
12. **Cumulative Sales per Month**: Cumulative sales per month for each year.
13. **Year-over-Year Growth Rate**: Year-over-year growth rate of total sales.
14. **Customer Retention Rate**: Retention rate of customers who make another purchase within 6 months of their first purchase.
15. **Top 3 Customers by Year**: Top 3 customers who spent the most money in each year.
16. **Customer Lifetime Value (CLV)**: CLV for each customer, visualized for the top 10 customers.
17. **Order Distribution by Hour**: Analysis of the time of day when orders are most frequently placed.

## Getting Started

### Prerequisites

- Python 3.x
- MySQL Server
- Required Python Libraries: `pandas`, `matplotlib`, `seaborn`, `mysql-connector-python`

You can install the required Python libraries using pip:

```bash
pip install pandas matplotlib seaborn mysql-connector-python
```

### Database Setup

Ensure that you have a MySQL database named `ecommerce` and that the following tables are available:

- `customers`
- `orders`
- `order_items`
- `payments`
- `products`
- `sellers`

### Running the Analysis

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/repository.git
    cd repository
    ```

2. Modify the database connection settings in the script as needed:

    ```python
    db = mysql.connector.connect(
        host="localhost",
        username="root",
        password="YourPassword",
        database="ecommerce"
    )
    ```

3. Run the Python script:

    ```bash
    python your_script_name.py
    ```

## Code Overview

The Python script includes the following main sections:

- **Database Connection**: Connect to the MySQL database.
- **SQL Queries**: Execute various SQL queries to fetch data from the database.
- **Data Processing**: Process and analyze the fetched data using Pandas.
- **Data Visualization**: Create visualizations using Matplotlib and Seaborn.

## Acknowledgements

- MySQL Connector for Python
- Pandas for data manipulation
- Matplotlib and Seaborn for data visualization

---
