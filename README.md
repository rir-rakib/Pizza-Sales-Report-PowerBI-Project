#  Power BI Pizza Sales Report Dashboard

This Power BI dashboard visualizes and analyzes pizza sales data using various KPIs and charts. The dashboard is built using a dataset named `Pizza_sold.csv` and focuses on uncovering trends, top-performing items, and customer ordering patterns.

---

##  Key KPIs (DAX Measures)

```DAX
-- Total Revenue
Total Revenue = SUM(Pizza_sold[Total Price])

-- Average Order Value
Avg Order Value = DIVIDE([Total Revenue], [Total Orders], 0)

-- Total Pizzas Sold
Total Pizza Sold = SUM(Pizza_sold[Quantity])

-- Average Pizzas per Order
Avg Pizzas Per Order = DIVIDE([Total Pizza Sold], [Total Orders], 0)

-- Total Orders
Total Orders = DISTINCTCOUNT(Pizza_sold[Order ID])


---
##  **Business Questions Answered**
This dashboard helps to answer the following questions:

- What is the total revenue, order count, and average pizza per order?
- Which pizza category contributes the most to sales?
- Which pizza size is most preferred by customers?
- Which pizzas generate the highest and lowest revenue?
- Which pizzas are sold the most and least in terms of quantity?
- What are the daily and monthly order trends?
- Which pizzas are ordered the most and the least?

---
## **Visuals in the Dashboard**
The dashboard includes the following charts:

- Percentage of Sales by Pizza Category – Donut Chart
- Percentage of Sales by Pizza Size – Donut Chart
- Total Pizza Sold by Category – Bar Chart
- Daily Trend for Total Orders – Column Chart
- Monthly Trend for Total Orders – Area Chart
- Top 5 Pizzas by Revenue – Bar Chart
- Lowest 5 Pizzas by Revenue – Bar Chart
- Top 5 Pizzas by Quantity Sold – Bar Chart
- Bottom 5 Pizzas by Quantity Sold – Bar Chart
- Top 5 Pizzas by Total Orders – Bar Chart
- Bottom 5 Pizzas by Revenue – Bar Chart

---
## **Tools Used**
  - Power BI Desktop
  - Power Query (for pre-processing)
  - DAX (Data Analysis Expressions)

---
## **How to Use**
  -Clone or download this repository.
  -Open the Pizza_Sales_Report.pbix file using Power BI Desktop.
  -Ensure the Pizza_sold.csv file is available in the same folder or update the data source path.
  -Explore and interact with the dashboard visuals.

👤 Author
Rakibul Islam
rir.rakibulislam@gmail.com

