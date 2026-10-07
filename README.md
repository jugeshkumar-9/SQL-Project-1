# 🍕 Pizza Sales Analysis using SQL

A MySQL project that answers 13 business questions about pizza sales: how many orders came in, how much revenue they earned, which pizzas sell best and when customers order the most.

## 📂 Database

Database name: `pizzahut`

| Table | Description |
| `orders` | One row per order (order_id, order_date, order_time) |
| `order_details` | Pizzas in each order (order_details_id, order_id, pizza_id, quantity) |
| `pizzas` | Pizza sizes and prices (pizza_id, pizza_type_id, size, price) |
| `pizza_types` | Pizza names and categories (pizza_type_id, name, category, ingredients) |

## ❓ Questions Answered

### Basic
1. Total number of orders placed
2. Total revenue from pizza sales
3. Highest-priced pizza
4. Most common pizza size ordered
5. Top 5 most ordered pizza types with quantities

### Intermediate
6. Total quantity of each pizza category ordered
7. Distribution of orders by hour of the day
8. Category-wise distribution of pizzas
9. Average number of pizzas ordered per day
10. Top 3 pizza types by revenue

### Advanced
11. Percentage contribution of each pizza type to total revenue
12. Cumulative revenue over time
13. Top 3 pizza types by revenue within each category

## 🛠️ SQL Concepts Used

- `JOIN` across up to three tables
- Aggregate functions: `SUM`, `COUNT`, `AVG`, `ROUND`
- `GROUP BY`, `ORDER BY`, `LIMIT`
- Date and time function: `HOUR()`
- Subqueries
- Window functions: `SUM() OVER()`, `SUM() OVER (ORDER BY ...)`, `RANK() OVER (PARTITION BY ...)`
