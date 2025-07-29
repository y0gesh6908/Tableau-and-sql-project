
---

### 🍕 **Pizza Sales Dashboard | Tableau + SQL Project**

🔗 [Dashboard Link](https://public.tableau.com/app/profile/yogesh.bijarniya/viz/PIZZADASHBOARD_17518935175070/home)

---

### 📌 **Project Overview**

* Built an interactive Tableau dashboard to analyze pizza sales data from a fictional restaurant.
* Used SQL for data cleaning, transformation, and metric calculation before importing into Tableau.
* Aimed to extract actionable business insights related to revenue, order trends, and product performance.
* Focused on enabling data-driven decisions for operations and marketing teams.

---

### 🗃️ **Dataset**

* Source: Raw transaction-level data with fields like `order_id`, `order_date`, `pizza_name`, `pizza_size`, `pizza_category`, `quantity`, and `total_price`.
* Cleaned and transformed using SQL to generate summarized views and KPIs.
* Exported cleaned data into CSV format for use in Tableau.

---

### 🧮 **Data Preparation (SQL)**

* Calculated key performance indicators:

  * Total Revenue, Average Order Value, Total Pizzas Sold, Total Orders.
* Derived additional insights:

  * Average Pizzas per Order.
  * Hourly sales trends by extracting hours from `order_time`.
  * Weekly trends using `WEEK()` and `YEAR()` functions on `order_date`.
* Calculated sales contribution breakdowns:

  * % of total sales by pizza category (e.g., Classic, Supreme, Veggie).
  * % of total sales by pizza size (Small, Medium, Large, XL).
* Identified:

  * Top and bottom 5 pizzas by revenue.
  * Top and bottom 5 pizzas by quantity sold.
  * Top and bottom 5 pizzas by total number of orders.

---

### 📊 **Dashboard Features**

* **KPI Cards**: Total Revenue, Total Orders, Total Pizzas Sold, Average Order Value.
* **Trend Visuals**:

  * Hourly pizza sales to detect peak times.
  * Weekly order trends to track business growth.
* **Category/Size Breakdown**:

  * Donut charts for % sales by pizza category and size.
* **Performance Visuals**:

  * Bar charts for top and bottom pizzas based on revenue, orders, and quantity sold.
* Interactive filters for deeper data exploration.

---

### ✅ **Business Questions Answered**

* What is the total revenue, and how many orders were placed?
* Which pizza categories and sizes contribute most to revenue?
* What are the most and least popular pizzas?
* During which hours and weeks do most orders occur?
* How do different products perform across key sales metrics?

---

### 🛠️ **Tools & Skills Used**

* **SQL**: Data cleaning, aggregation, and performance metric calculation.
* **Tableau Public**: Visualizing KPIs, trends, and product performance.
* **Data Modeling**: Creating structured datasets for BI tools.
* **Business Intelligence**: Answering real-world operational questions using data.
* **Dashboard Design**: Building intuitive, insightful, and interactive dashboards.

---

### 📷 **Dashboard Preview**

* Explore all insights and visuals on Tableau Public:
  [Pizza Dashboard – Yogesh Bijarniya](https://public.tableau.com/app/profile/yogesh.bijarniya/viz/PIZZADASHBOARD_17518935175070/home)

---


