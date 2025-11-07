# Executive Sales & Customer Dashboard | Case Study

## Overview  
This project involves the creation of **two interactive dashboards** — an **Overview Dashboard** and an **Employees Dashboard** — designed to provide clear visibility into business performance and workforce productivity.  
The goal: empower decision-makers with **data-driven insights** on sales, customers, and employee performance through a clean, intuitive visual interface.

The dataset was **synthetically generated using the Python Faker library**, ensuring realistic but privacy-safe data for analysis.  
The dashboards were developed in **Tableau**, delivering a dynamic, insightful, and interactive experience.

---

## Business Problem  
The company lacked a **unified system** to monitor critical business metrics like total sales, customer distribution, and employee performance.  
With reports scattered across departments, management struggled to make timely, informed decisions.

The objective was to build **centralized dashboards** that simplify performance tracking, identify bottlenecks, and reveal cross-department patterns across sales and workforce data.

---

## Process  

### Data Generation  
- Used the **Python Faker library** to simulate realistic data covering: regions, product categories, sales amounts, customers, and employee performance metrics.  
- Created synthetic datasets for both sales/customer metrics and employee performance.

### Data Cleaning & Preparation  
- Cleaned and structured the generated data to ensure accurate data types and consistent formats.  
- Defined clear relationships between sales/customers and employee datasets to support dashboard analytics.

### Dashboard Design & Development (Tableau)  
Two dashboards were built in Tableau:  
- **Overview Dashboard:** Focuses on high-level company metrics including total sales, customer segmentation, profit distribution, and product category performance.  
- **Employees Dashboard:** Highlights employee productivity—sales by employee, regional contributions, performance rankings, and monthly trends.

---

## 🛠 Technology Used  
| Tool / Library        | Purpose                                   |
|------------------------|-------------------------------------------|
| **Python (Faker library)** | Synthetic, realistic data generation       |
| **Tableau**             | Interactive data visualization and dashboards |

---
#### Sales Dashboard 
![Sales Dashboard](Dashboard/sales_dashboard.png)

## Insights  
- Strong total sales and profit trends in key regions.  
- Top-performing regions contribute majority revenue; other regions show growth potential.  
- Customer segmentation reveals that **loyal** and **returning customers** significantly stabilize profits.  
- Product-category analysis indicates **Technology** leads in sales, followed by **Office Supplies** and **Furniture**.

### Recommendations  
- Reinforce inventory and marketing strategies in top-performing regions.  
- Launch loyalty programs to increase repeat-customer engagement.  
- Revise pricing and promotions for underperforming categories to boost growth.

---

#### Customers Dashboard  
![Customers Dashboard](Dashboard/customer_dashboard.png)

## Insights  
- The **top 5 employees** consistently achieve above-average sales targets.  
- Regional sales distribution shows workforce concentrated in certain areas — indicating potential staffing imbalances.  
- Monthly performance tracking highlights peaks and troughs, offering opportunities for planning and resource re-allocation.

### Recommendations  
- Recognize and reward high performers to sustain motivation and results.  
- Rebalance staff assignments to strengthen under-performing regions.  
- Implement monthly training or review cycles to smooth out performance variability.

---

## Next Step  
The upcoming phase will focus on:  
- Automating data updates to enable near-real-time dashboards.  
- Integrating **predictive analytics** to forecast future sales, workforce performance, and customer behavior.  
- Connecting live business systems (CRM, HR, sales platforms) for production-grade dashboard integration and enhanced decision-making accuracy.

---

### 📁 Repo Structure (suggested)  
├── Dashboard/
│ └── Sales & Customer Dashboard.twbx
| └── customer_dashboard.png
| └── sales_dashboard.png
├── Dataset/
│ ├── Customers.csv
| └── Location.csv
| └── Orders.csv
| └── Products.csv
├── Images/
│ └── Icons
└── README.md
