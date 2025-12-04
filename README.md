# 📊 FUTURE_DS_01 – Business Sales Dashboard (E-commerce)

This repository contains **Task 1** of the **Future Interns – Data Science & Analytics Internship**.  
The objective of this task is to analyze an e-commerce dataset and build an interactive **Power BI dashboard** that highlights key business metrics and insights.

---

## 📁 Project Overview

In this project, I worked with a **350-row US e-commerce dataset** containing sales, product, customer, and category information.  
Using Power BI, I transformed, analyzed, and visualized the data to uncover business insights related to:

- Best-selling products  
- Monthly sales performance  
- Category-wise revenue  
- Customer behavior  
- High-level KPIs (Sales, Orders, Quantity, Customers)

---

## 📊 Dashboard Features

### 🔹 **1. KPI Cards**
- **Total Sales:** $781.99K  
- **Total Orders:** 350  
- **Total Quantity Sold:** 1030 units  
- **Total Customers:** 166  

These KPIs provide a high-level overview of business performance.

---

### 🔹 **2. Monthly Sales Trend (Line Chart)**
Shows seasonal behavior and monthly revenue changes.

**Key findings:**
- Sales rise steadily from **March to July**  
- **September** is the peak sales month  
- Sales decline after **October**, indicating seasonal patterns  

---

### 🔹 **3. Top Selling Products (Bar Chart)**
Ranks products by revenue contribution.

**Top performers include:**
- Dell Inspiron Laptop  
- L'Oréal Shampoo  
- Sony Headphones  
- iPhone 14  
- Nike Running Shoes  

---

### 🔹 **4. Sales by Category (Donut Chart)**
Provides a category-level breakdown of sales.

**Category revenue share:**
- **Electronics – 35.67% (Highest)**  
- Beauty – 17.97%  
- Clothing – 15.87%  
- Sports – 15.33%  
- Furniture – 14.93%  

Electronics is the dominant category in terms of revenue.

---

## 🗂 Dataset Information

The dataset contains 350 records with the following columns:

- **Order_ID**
- **Order_Date**
- **Product**
- **Category**
- **Subcategory**
- **Price**
- **Quantity**
- **Total_Sales**
- **City**
- **Customer**

This dataset was designed to closely resemble real-world e-commerce data.

---

## 🛠 Tools & Technologies Used

- **Power BI Desktop**  
- **DAX (Data Analysis Expressions)**  
- **Power Query**  
- **CSV Dataset**  

---

## 🧮 DAX Measures Used

```DAX
Total Orders = DISTINCTCOUNT('ecommerce_sales_dataset_us_350rows'[Order_ID])

Total Customers = DISTINCTCOUNT('ecommerce_sales_dataset_us_350rows'[Customer])

