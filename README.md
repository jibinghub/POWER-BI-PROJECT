# 📊 Project: Superstore Sales Analysis

## 📝 Project Description
The **Superstore Sales Analysis Dashboard** is a Power BI project designed to analyze and visualize business performance across multiple dimensions such as **sales, profit, customer segments, product categories, and shipping methods**.

The project uses a **cleaned Superstore dataset** containing detailed information about orders, customers, geography, and products.  
The data was modeled into a **star schema**, enabling efficient analysis through relationships between key tables — *Orders, Customers, Products, Geography,* and *Shipping*.  

Through interactive Power BI visualizations, the dashboard provides insights into **regional performance**, **top-selling products**, **profitability trends**, and **customer behavior**.  
It also highlights key performance metrics such as **Total Sales**, **Profit Margin**, and **Average Order Value**, helping stakeholders make **data-driven business decisions** to improve efficiency and profitability.

---

## 📂 Dataset
- **Source:** [Kaggle – Superstore Dataset](https://www.kaggle.com/)  
- **Rows / Columns:** Approximately **9,994 records** and **21 columns**  
- **Key Columns:** `Order ID`, `Order Date`, `Customer ID`, `Region`, `Product ID`, `Sales`, `Profit`, and `Ship Mode`

---

## 📁 Folder Structure
📦 Superstore_Sales_Analysis
┣ 📜 BRD/ # Business Requirements Document
┣ 📜 FRD/ # Functional Requirements Document
┣ 📊 Data/ # Cleaned and raw datasets
┣ 📈 Visuals/ # Dashboard screenshots and visuals
┣ 🧩 PowerBI/ # Power BI (.pbix) file
┣ 📑 Reports/ # Analysis and summary reports
┣ 💻 Scripts/ # Data cleaning or DAX calculation scripts
┗ 📄 README.md # Project overview and documentation


## 🧩 Steps to Reproduce
1. **Assess & Clean Dataset**  
   - Reviewed the Superstore dataset for missing values, duplicates, and inconsistencies.  
   - Cleaned data using Power Query by standardizing column names, removing blanks, and ensuring correct data types.  

2. **Design Dashboard Mockups**  
   - Planned dashboard layouts for key analytical areas: *Customer & Segment Analysis*, *Sales & Profit Analysis*, and *Shipping & Delivery Analysis*.  

3. **Build Power BI Dashboard & Data Model**  
   - Created a relational model connecting **Orders**, **Customers**, **Products**, **Geography**, and **Shipping** tables.  
   - Developed calculated measures (e.g., *Total Sales*, *Total Profit*, *Quantity*, *Discount*).  
   - Built visuals, KPIs, and interactive filters for user-driven insights.  

4. **Export Reports & Prepare Analysis Report**  
   - Published dashboards, exported final reports, and documented the findings and recommendations.

---

## 📊 Key Insights / Learnings
- **Customer Segmentation:** The *Consumer* segment generated the highest sales and profit, indicating strong demand from individual customers.  
- **Regional Performance:** The *West* region showed the highest sales, while *South* performed comparatively lower — potential for growth initiatives.  
- **Top Products:** *Cisco TelePresence System EX90 Videoconferencing Unit* was identified as the top-selling product.  
- **Profitability Trends:** *Technology* category products provided the highest profit margins compared to *Office Supplies*.  
- **Shipping Efficiency:** *Standard Class* was the most used mode but had lower profit margins due to higher discounts.  
- **Customer Insights:** A small group of top customers contributed significantly to overall profit — focus on loyalty strategies.

---

### 🧠 Key Learnings Summary
This Power BI project demonstrated the complete data analysis workflow — from data cleaning and modeling to dashboard creation and business insight generation.  
Through visual analytics, key performance trends and improvement areas across sales, customers, and shipping were effectively identified.


