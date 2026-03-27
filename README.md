# Sales-Data-Analysis-Dashboard-Power-BI-
This project showcases an interactive Power BI dashboard designed to analyze sales performance across regions and products. It includes KPI tracking, trend analysis, and dynamic filtering to derive actionable business insights.



---

Objectives

* Analyze overall sales performance
* Track profit and profitability (Profit Margin)
* Identify top-performing regions and products
* Understand sales trends over time
* Provide interactive filtering for better insights



<img width="1918" height="1022" alt="image" src="https://github.com/user-attachments/assets/f8d86b72-dc51-4f2a-9428-3d2f78a742ec" />

---

 Key Features

*  Trend Analysis: Line chart showing sales over time
*   KPI Cards: Total Sales, Total Profit, Profit Margin
*  Region-wise Analysis: Bar chart comparing sales across regions
* Product Analysis: Sales distribution by product category
* Interactive Filters: Region, Product, and Date slicers
* Custom DAX Measure: Profit Margin calculation

---

<img width="1920" height="1017" alt="image" src="https://github.com/user-attachments/assets/b074c312-2567-4e18-a073-e0a14b81c874" />





 Tools & Technologies

* Power BI (Data Visualization)
* Power Query (Data Cleaning & Transformation)
* DAX (Data Analysis Expressions)
* Excel/CSV Dataset

<img width="1920" height="1017" alt="image" src="https://github.com/user-attachments/assets/75e3fc01-971d-4aa2-b8ec-0f1ccbf6788c" />


 Dataset

The dataset used in this project contains:

* Order ID
* Date
* Region
* Product
* Sales
* Profit
* Quantity

<img width="1920" height="1017" alt="image" src="https://github.com/user-attachments/assets/5e2f8732-a114-4b21-9b26-405f3b01d6da" />






 Key Insights

* North region generates the highest sales among all regions
* Sales show fluctuating trends with peak periods during certain months
* Profit margin is approximately **19.6%**, indicating moderate profitability
* Product categories contribute almost equally to total sales

<img width="1920" height="1017" alt="image" src="https://github.com/user-attachments/assets/1c120ee4-e5d3-40ed-820a-0e9c1009d3fa" />






 DAX Formula Used

<img width="1920" height="1017" alt="image" src="https://github.com/user-attachments/assets/1ffec437-90cd-43c1-ba0e-455cda21bf83" />



```DAX
Profit Margin = DIVIDE(SUM(sales_data[Profit]), SUM(sales_data[Sales]))
---






Future Improvements

* Add advanced KPIs (YoY growth, MoM growth)
* Implement drill-through analysis
* Improve UI/UX with better design themes



