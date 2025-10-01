
# 🍕 Pizza Sales Analysis Dashboard in Power BI

This project analyzes pizza sales data and presents insights through an interactive Power BI dashboard. The goal is to explore sales patterns, customer behavior, and key performance metrics to support data-driven decision-making.



## 📊 DAX Measures Used

Avg Order Value = DIVIDE([Total Revenue],[Total No of Orders])  
Avg Pizza Per Order = DIVIDE([Total Pizza Sold],[Total No of Orders])  
Total No of Orders = DISTINCTCOUNT(pizza_sales[order_id])  
Total Pizza Sold = SUM(pizza_sales[quantity])  
Total Revenue = SUM(pizza_sales[total_price])  

## 📈 Dashboard Visuals

The dashboard provides the following visual insights:

📅 Total Number of Orders by Weekday – identifies the busiest days

📆 Monthly Trend for Total Orders – tracks seasonality and demand

💵 Total Revenue by Pizza Category – highlights revenue contribution by type

🥧 Total Orders by Pizza Size – compares customer size preferences

🔝 Top 5 Best-Selling Pizzas – identifies popular menu items

🔻 Bottom 5 Least-Selling Pizzas – identifies underperforming products
   
## 🚀 How to Use

- Install Power BI Desktop from Official Power BI Download Site.
- Download the pbix file from this repository.
- Open it in Power BI Desktop.
- Explore the interactive dashboard and insights.

