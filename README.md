
# 🚀 Business Insights 360 – Power BI End-to-End Project

## 🧠 Project Summary

**AtliQ Hardware** has been expanding rapidly, but recent decisions based on gut instinct and Excel analysis led to financial losses—especially in their U.S. operations. To stay competitive and data-driven, they’ve decided to adopt **Power BI** as their business intelligence platform.

This project aims to provide a 360° view of business performance across departments—**Sales, Finance, Marketing, and Supply Chain**—through interactive dashboards. 

🔗 You can find the Live Report here :[Report](https://app.powerbi.com/view?r=eyJrIjoiMGMxNjg1MzMtMDI1Yi00YjI0LWE5MzQtYzJmMzc4ZGJjZjVjIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

## 🔧 Tech Stack & Tools

- **SQL** – For querying and preparing data  
- **Power BI Desktop** – Dashboard design and data modeling  
- **DAX & DAX Studio** – For writing optimized measures  
- **Excel** – Data verification   
- **M Language** – For creating custom date tables  

## 📊 Key Power BI Concepts Practiced

- Asking the **right stakeholder questions** before development  
- Creating **calculated columns** and **DAX measures**  
- Effective **data modeling** using the **Snowflake schema**  
- **Bookmarks & buttons** for page navigation  
- **Dynamic titles** based on filter context  
- **KPI indicators** and **conditional formatting**  
- Building a **date table** with M language  
- **Validating data** using Excel for accuracy  
- Publishing and managing reports via **Power BI Service**  
- Setting up **scheduled refreshes** with a personal gateway  
- Managing access through **workspaces and permissions**  

## 🧠 Business Concepts Covered

- Net Sales, Gross Margin, Net Profit  
- Pre-/Post-Invoice Deductions  
- COGS (Cost of Goods Sold), YTD (Year-to-Date), YTG (Year-to-Go)  
- Customer Channels: **Retailers**, **Direct**, and **Distributors**

## 🏢 Company Background – AtliQ Hardware

A global seller of computer hardware and accessories, AtliQ Hardware operates via three main channels:

- Retailers  
- Direct-to-Customer  
- Distributors

After a costly misstep expanding into the U.S. market, the company committed to making **data-driven decisions** through analytics. This project is a key step in that transformation.

## ❓ Pre-Project Questions – Aligning with Stakeholders

Before building the dashboard, it's crucial to ask:

- What’s the objective of this dashboard?  
- How will we define project success?  
- Who are the end users and what are their goals?  
- Are preview demos needed before final delivery?  
- What fears or expectations do stakeholders have?  
- What resources, datasets, or design inputs are required?

## 🗃️ Data Understanding

The datasets were provided post-kickoff and stored in **MySQL**, accessed directly from Power BI.

### 📦 gdb041 – Core Tables

- `dim_customer` – Customer details (75 customers, 27 markets, 3 channels)  
- `dim_market` – Market zones and regions  
- `dim_product` – Product hierarchy: Division > Category > Variant  
- `fact_sales_monthly` – Monthly actual sales data  
- `fact_forecast_monthly` – Forecasted demand, helpful for planning

### 💰 gdb056 – Financial Tables

- `gross_price` – Product-wise pricing  
- `manufacturing_cost` – Production cost per year  
- `freight_cost` – Transportation costs by region  
- `pre_invoice_deductions` & `post_invoice_deductions` – Discounts and other deductions

## 🔌 Data Import & Modeling

- Connected directly to **MySQL** with login credentials  
- Used the **Snowflake schema** to model relationships between dimension and fact tables  
- Ensured clean joins and optimized relationships for performance  

![Data Model](https://github.com/varun0906-da/BI-360-Insights/blob/main/Data_Model_Page.png)

## 🎨 Dashboard Design

The design is inspired by stakeholder mockups. Navigation is button-driven, allowing users to switch between key business areas.

Quick-access buttons to navigate to:

- Info Page  
- Executive Summary  
- Sales View  
- Finance View  
- Marketing View  
- Supply Chain View  
- Product Analysis  
- Support  

## 📈 Report Previews
### 📍 Home Page
![Home Page](https://github.com/varun0906-da/BI-360-Insights/blob/main/Landing_Page.png)

### 🧭 Info Page  
![Info](https://github.com/varun0906-da/BI-360-Insights/blob/main/Info_Page.png)

### 💸 Finance View  
![Finance](https://github.com/varun0906-da/BI-360-Insights/blob/main/Finance_Page.png)

### 📊 Sales View  
![Sales](https://github.com/varun0906-da/BI-360-Insights/blob/main/Sales_Page.png)

### 📣 Marketing View  
![Marketing](https://github.com/varun0906-da/BI-360-Insights/blob/main/Marketing_Page.png)

### 🚚 Supply Chain  
![Supply Chain](https://github.com/varun0906-da/BI-360-Insights/blob/main/Supply_Chain_Page.png)

### 🧑‍💼 Executive View  
![Executive](https://github.com/varun0906-da/BI-360-Insights/blob/main/Executive_Page.png)

### 🖥️ Product Insights  
![Products](https://github.com/varun0906-da/BI-360-Insights/blob/main/Product_Page.png)

### ◼️ Support View  
![Support](https://github.com/varun0906-da/BI-360-Insights/blob/main/Support_Page.png)

## ✅ Project Outcome

This interactive report equips stakeholders to:

- Make faster and smarter decisions  
- Drill down into KPIs across departments  
- Answer “Why?” questions with data instead of guesswork  
- Track trends and identify problem areas with visual indicators

