# Revenue Intelligence : Sales, Profit & Discount Analysis
A dynamic, interactive data visualization tool built to analyze revenue, profitability, discount impact, and product performance—focusing on time-based comparisons, regional trends, and growth insights to support data-driven decision-making.

## Project Objective
The Revenue Intelligence Dashboard is an interactive Power BI report designed to analyze sales performance, profitability, and discount impact across products, regions, and time. It enables stakeholders to monitor growth trends, compare performance between periods, and identify revenue drivers to support data-driven pricing and strategic decisions.

---

## 3. Tech Stack
The dashboard was built using the following tools and technologies:
- • 📊 **Power BI Desktop** – Primary data visualization platform used to design interactive reports and dashboards.
- • 📂 **Power Query** – Data cleaning, transformation, and preprocessing of transactional datasets.
- • 🧠 **DAX (Data Analysis Expressions)** – Developed calculated measures including time intelligence, period comparison , KPI metrics, and profitability analysis.
- • 📝 **Data Modeling (Star Schema)** – Structured the data into a star schema by organizing the existing fact table and connecting it to relevant dimension tables (Product, Customer, Promotion, Date)..
- • 📁 **File Format** – `.pbix` for development and `.png` for dashboard previews.

---
## 4. Data Source
- Source: Simulated retail sales dataset created for analytical and reporting purposes.
The dataset represents transactional sales data including product details, customer information, promotional campaigns, pricing, discounts, and profit metrics.
---

## Key Features
- Interactive filters for Year, Quarter, and Month
- Drill-down analysis by product, promotion, and location
- Executive KPIs including Total Revenue, Total Profit, Average Discount %, and Return on Discount (ROD) , Sales , Profit Growth. 
- Time-series trend analysis for sales performance
- Comparative visuals for sales vs profit across states and promotions


---
## Walkthrough of Key Visuals

#### 1. Key KPIs Panel (Top Section)  
Shows Total Revenue, Net Sales, Profit, Units Sold, Total Orders, Average Discount (27%), and Return on Discount (1.70).  
Gives a quick summary of overall business performance and how effective discounts are.

#### 2. Time Filters Panel  
Year, Quarter, and Month slicers allow users to filter the entire dashboard and analyze performance across different time periods.

#### 3. Sales Trends Over Time (Line Chart)  
Displays how sales change over time (daily, monthly, quarterly, yearly).  
Helps identify busy seasons and slow periods.

#### 4. Top / Bottom 5 Products (Stacked Bar Chart)  
Shows the top and bottom 5 products based on Sales, Profit, and Quantity Sold.  
Helps identify best-performing products and those that may need attention.

#### 5. Period-over-Period Comparison (Column Charts & KPI Cards)  
Compares Sales, Profit, and Quantity between two selected time periods.  
Also shows the difference in sales and the percentage growth to measure improvement or decline.

#### 6. Discount Impact Analysis (Column Chart & KPI Cards)  
Displays average discount by promotion category and calculates Return on Discount (ROD).  
Helps understand whether discounts are increasing profits or reducing margins.


#### 7. Regional Performance (Column Chart)  
Compares Sales and Profit across cities.  
Helps identify strong and weak markets.

#### 8. Order-Level Detail View (Table Visual)  
Shows detailed transaction-level data including Sales, Profit, Discount, and Net Sales.  
Allows deeper analysis of individual orders.

---
## Business Impact & Insights  

**1. Improving Revenue Decisions:**  
Management can identify top-performing and low-performing products, enabling better pricing and product strategy decisions.

**2. Discount Impact:**  
The Return on Discount (ROD) metric helps evaluate whether promotional campaigns are generating profit or simply reducing margins.

**3. Performance Tracking:**  
Period-over-period comparison allows leadership to measure growth, decline, and the impact of strategic decisions over time.

**4. Regional Performance:**  
City-level sales and profit analysis helps prioritize strong markets and improve performance in weaker regions.

**5. Transactional Level details:**  
Order-level insights support deeper investigation into unusual discounts, low-profit transactions, or customer behavior patterns.

 ## Report Snapshot (Power BI DESKTOP)
 <img width="1788" height="736" alt="Image" src="https://github.com/user-attachments/assets/65b78ffb-7af6-4fed-b804-6366b6beb8ef" />
 <img width="1432" height="798" alt="Image" src="https://github.com/user-attachments/assets/a69fb2d0-fe3c-418a-b19e-892694921034" />
<img width="1425" height="792" alt="Image" src="https://github.com/user-attachments/assets/c7c17ff2-f24a-49e6-87b2-06e39c162dcb" />
<img width="1430" height="797" alt="Image" src="https://github.com/user-attachments/assets/9a1cae07-140f-4304-9131-fdad70f489b3" />
<img width="1430" height="806" alt="Image" src="https://github.com/user-attachments/assets/4acd4b5e-4072-4d89-9903-8ac411d92b8d" />
<img width="1432" height="801" alt="Image" src="https://github.com/user-attachments/assets/8de51005-31ea-4790-b702-a6debf5f3f60" />
