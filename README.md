# FoodHub Data Analytics

This project focuses on analyzing FoodHub’s order and customer data stored in **CSV files**.  
The goal is to uncover insights into customer behavior, order trends, and delivery performance.

---

## 📂 Project Structure

- `data/foodhub_orders.csv` → Raw dataset containing order-level information.
- `notebooks/` → Jupyter notebooks for exploratory data analysis (EDA).
- `scripts/` → Python scripts for data cleaning, transformation, and visualization.
- `reports/` → Generated charts, dashboards, and summary reports.

---

## 📊 Dataset Overview

The CSV file (`foodhub_orders.csv`) includes the following columns:

| Column Name       | Description                                    |
|-------------------|------------------------------------------------|
| `Order_ID`        | Unique identifier for each order               |
| `Customer_ID`     | Unique identifier for each customer            |
| `Restaurant`      | Name of the restaurant                        |
| `Cuisine`         | Cuisine type (e.g., Italian, Indian, Chinese) |
| `Order_Date`      | Date of the order                             |
| `Delivery_Time`   | Time taken to deliver (minutes)                |
| `Order_Value`     | Total value of the order (currency)            |
| `Payment_Method`  | Payment type (Cash, Card, Wallet)              |
| `Rating`          | Customer rating (1–5 scale)                   |

---

## ⚙️ Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/foodhub-analytics.git
   cd foodhub-analytics
