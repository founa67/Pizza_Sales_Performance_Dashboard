# 📘 Data Dictionary — Pizza Sales Dataset

| Column Name     | Data Type | Description |
|-----------------|------------|-------------|
| order_id        | INT        | Unique identifier for each order |
| order_date      | DATE       | Date when the order was placed |
| order_time      | TIME       | Time when the order was placed |
| pizza_name      | VARCHAR    | Name of the pizza sold |
| pizza_category  | VARCHAR    | Category of the pizza (Classic, Supreme, etc.) |
| pizza_size      | VARCHAR    | Size of the pizza (S, M, L, XL, XXL) |
| quantity        | INT        | Number of pizzas sold in the order |
| total_price     | DECIMAL(10,2) | Total price for that order line |
| revenue_per_order | DECIMAL(10,2) | Average revenue per unique order ID |
