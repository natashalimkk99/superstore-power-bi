# 🛒 Superstore Dashboard Analysis – Power BI Capstone Project  

## 📌 Project Overview  
This repository contains my **Power BI Capstone Project** built using the **Superstore dataset**.  
The goal is to analyze sales, profit, customer segments, and delivery reliability, then present key insights through an **interactive dashboard**.  

## 🎯 Objectives  
- Explore sales and profit trends across time, cities, and product categories  
- Highlight how are profit margins and shipping performance are changing over time
- Measure delivery performance across shipping modes  
- Provide decision-makers with data-driven insights through interactive visuals  

## 📂 Dataset  
- **Source**: Sample Superstore Dataset  
- **Contains**:  
  - Orders → Order ID, Order Date, Ship Code, Ship Reference Number, Payment Method, Customer ID, Product Category ID, Sales, Quantity, Discount, Profit
  - Customers → Customer ID, Name, Gender, Segment
  - Product → Product Category ID, Category, Sub-Category
  - Shipping → Shipping ID, Ship Mode, Courier, Order Date, Delivered Date, Delivery Timing, City, State and Postal Code

## 📊 Dashboard Features  
1. Overview Dashboard
- Displays top-level KPIs: Sales, Profit, Profit Margin, and Delivery Reliability.
- Highlights the big picture: strong sales but thin profitability and poor delivery performance.
- Simplifies delivery status by grouping “Early” + “On Time” as On Time, vs “Delayed.”

2. Revenue & Profitability Dashboard
- Breaks down revenue vs profit margin by product category and sub-category.
- Identifies high-revenue products (Machines, Chairs, Tables, Phones) vs high-margin products (Paper, Copiers, Labels).
- Segmentation view: profit contribution by Customer Segment (Home Office, Consumer, Corporate).
- Geographic view: compares profitability by city, highlighting top (Kuching) and loss-making (Johor Bahru) markets.

3. Delivery Reliability Dashboard
- Tracks on-time vs delayed deliveries across shipping modes, couriers, and cities.
- Exposes systemic delivery challenges:
  - Standard Class (most used) = highest delays.
  - Same Day = most reliable but underutilized.
- Courier performance analysis: Hero Van, HomeLaju, Parcel Express averaging ~20 days delivery.
- Regional delivery punctuality: Kuala Lumpur best, Johor Bahru worst. 

## 🚀 Tools & Technologies  
- Power BI Desktop (report building)  
- DAX & Power Query (data modeling & transformation)  
- Excel / CSV (data source)  

## 📸 Dashboard Preview
![Dashboard Screenshot](https://github.com/natashalimkk99/superstore-power-bi/blob/main/Images/Superstore%20Overview%20Dashboard.png?raw=true)

![Dashboard Screenshot](https://github.com/natashalimkk99/superstore-power-bi/blob/main/Images/Superstore%20Revenue%20%26%20Profitability%20Dashboard.png?raw=true)

![Dashboard Screenshot](https://github.com/natashalimkk99/superstore-power-bi/blob/main/Images/Superstore%20Delivery%20Reliability%20Dashboard.png?raw=true)

## 🔍 Key Insights  
1. Sales & Profitability
- Sales strong (RM344k) but profit thin (RM25k, 7.38% margin).
- Reliance on low-margin products drags down profitability.
- High-margin products (Paper, Copiers, Labels) underutilized.

2. Customer Segments
- Home Office: 53% of profit (key growth driver).
- Consumer: 43% of profit (solid support).
- Corporate: only 4% (low strategic value).

3. Geography
- Kuching leads in profit (+RM20.8k).
- KL & George Town moderate performers.
- Johor Bahru loss-making (-RM1.5k) with poor delivery reliability.

4. Delivery Reliability
- 69% on-time, 31% delayed (1 in 3 orders late).
- Standard Class worst performer; Same Day most reliable but underused.
- Couriers average ~20 days → systemic issue.
- Johor Bahru worst delays (53% late), KL best (58% on time).

📌 Overall: Strong sales, but thin margins and delivery problems are eroding profitability and customer trust.

## 📌 How to Use  
1. Clone this repository  
2. Open the `.pbix` file in **Power BI Desktop**  
3. Interact with the dashboard to explore insights  

## 📬 Contact  
👩‍💻 **Natasha Lim Kar Khee**  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/natashalimkarkhee)  
📧 natasha.limkk@gmail.com 

---
⭐ If you found this project helpful, don’t forget to give it a star!

