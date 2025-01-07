# Pizza Sales Analysis

This project analyzes pizza sales data using SQL to uncover business insights. The dataset consists of four CSV files representing order details, orders, pizza types, and pizzas. The analysis includes queries to calculate revenue, popular pizzas, customer ordering trends, and other advanced metrics.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
  - [order_details.csv](#order_detailscsv)
  - [orders.csv](#orderscsv)
  - [pizza_types.csv](#pizza_typescsv)
  - [pizzas.csv](#pizzascsv)
- [Questions Addressed](#questions-addressed)
  - [Basic Questions](#basic-questions)
  - [Intermediate Questions](#intermediate-questions)
  - [Advanced Questions](#advanced-questions)
- [Technologies Used](#technologies-used)
## Project Overview

The Pizza Sales Analysis project leverages SQL queries to extract valuable insights from pizza sales data. It involves basic, intermediate, and advanced SQL queries to answer critical business questions and analyze trends.

## Prerequisites

Before you begin, ensure you have the following:
- MySQL Workbench installed on your computer.
- A MySQL server instance set up and running.
- The CSV files you want to upload.

---

## Steps to Import CSV Files

### 1. Create a Database
1. Open MySQL Workbench and connect to your server.
2. In the toolbar, click on the **`+`** icon to create a new database.
3. Use the following SQL command to create a database:
   ```sql
   CREATE DATABASE pizza_sales;
# Import the following data sets
## Dataset
The dataset includes the following CSV files:

### `order_details.csv`
Contains details about individual pizza orders:
- `order_details_id`:Counts the orders
- `order_id`: Unique identifier for each order.
- `pizza_id`: ID of the pizza ordered.
- `quantity`: Number of pizzas ordered.

### `orders.csv`
Contains details about orders:
- `order_id`: Unique identifier for each order.
- `order_date`: Date and time of the order.
- `order_date`: Time at which order is placed.

### `pizza_types.csv`
Contains details about pizza types:
- `pizza_type_id`: Unique identifier for each pizza type.
- `name`: Name of the pizza type.
- `category`: Category of the pizza (e.g., vegetarian, meat).
- `ingredients`: List of ingredients used in the pizza.

### `pizzas.csv`
Contains details about pizzas:
- `pizza_id`: Unique identifier for each pizza.
- `pizza_type_id`: ID linking to the pizza type.
- `size`: Size of the pizza (small, medium, large, etc.).
- `price`: Price of the pizza

## Questions Addressed

### Basic Questions:
1. Retrieve the total number of orders placed.<br/>
![1 results](../main/image/1.png)
   
2. Calculate the total revenue generated from pizza sales.<br/>
![1 results](../main/image/2.png)

4. Identify the highest-priced pizza.<br/>
![1 results](../main/image/3.png)
5. Identify the most common pizza size ordered.<br/>
![1 results](../main/image/4.png)
6. List the top 5 most ordered pizza types along with their quantities.<br/>
![1 results](../main/image/5.png)

### Intermediate Questions:
1. Join the necessary tables to find the total quantity of each pizza category ordered.<br/>
![1 results](../main/image/6.png)
2. Determine the distribution of orders by hour of the day.<br/>
![1 results](../main/image/7.png)
3. Join relevant tables to find the category-wise distribution of pizzas.<br/>
![1 results](../main/image/8.png)
4. Group the orders by date and calculate the average number of pizzas ordered per day.<br/>
![1 results](../main/image/9.png)
5. Determine the top 3 most ordered pizza types based on revenue.<br/>
![1 results](../main/image/10.png)

### Advanced Questions:
1. Calculate the percentage contribution of each pizza type to total revenue.<br/>
![1 results](../main/image/11.png)
2. Analyze the cumulative revenue generated over time.<br/>
![1 results](../main/image/12.png)
3. Determine the top 3 most ordered pizza types based on revenue for each pizza category.<br/>
![1 results](../main/image/13.png)

## Technologies Used

- **SQL**: For querying and analyzing the data.
- **Power Point**: For creating the PPT.


