# 📈 Sales Performance Analysis Dashboard – Power BI/ Excel/ Python

This dashboard delivers an end-to-end analysis of sales performance, customer behavior, product trends, and regional profitability using historical data and advanced segmentation techniques. Built in Power BI with Python-assisted data prep, it enables strategic decision-making through real-time KPIs and predictive insights.

![Sales_Performance_Analysis_Dashboard (1)_page-0002](https://github.com/user-attachments/assets/fba19855-3e3b-40c1-87cf-308f9a8a11c4)
![Sales_Performance_Analysis_Dashboard (1)_page-0003](https://github.com/user-attachments/assets/c8b5a129-841c-4305-bcf9-ba3f80d656ed)
![Sales_Performance_Analysis_Dashboard (1)_page-0004](https://github.com/user-attachments/assets/c2b3ef7e-8e22-48d1-b006-53890aa77cb4)
![Sales_Performance_Analysis_Dashboard (1)_page-0005](https://github.com/user-attachments/assets/319269e6-37d4-49e8-b118-6f9ff45edb4c)
![Sales_Performance_Analysis_Dashboard (1)_page-0006](https://github.com/user-attachments/assets/dc30a63b-9203-4fec-b61f-af31dcad177d)
![Sales_Performance_Analysis_Dashboard (1)_page-0007](https://github.com/user-attachments/assets/73560a43-20ba-42ed-b1ae-bc4578d3941d)
![Sales_Performance_Analysis_Dashboard (1)_page-0008](https://github.com/user-attachments/assets/2309efad-2755-470f-aa81-f144cbb60fa6)
![Sales_Performance_Analysis_Dashboard (1)_page-0009](https://github.com/user-attachments/assets/d4792925-40f2-43ec-a06e-6e55f502c92d)
![Sales_Performance_Analysis_Dashboard (1)_page-0010](https://github.com/user-attachments/assets/4073cad4-a1d4-436f-8352-2fd3fd78e5cd)

---

## 🔍 Purpose

The primary goal of this dashboard was to:
- Provide a **comprehensive overview of sales performance** across products, regions, and salespersons.
- Track **target vs actual sales**, profit margins, and YoY growth to assess team efficiency.
- Perform **deep customer segmentation** using RFM and CLV analytics.
- Identify **top-performing states, product sub-categories, and salespeople**.
- Enable **what-if simulations** to evaluate pricing and discounting strategies.

---

## 🎯 Business Impact

- Helped identify **top 35% of customers** who contribute **~67% of total sales**, aiding retention focus.
- Enabled **real-time sales target tracking**, with a 98.98% target achievement rate across 2021.
- Revealed high-return sub-categories and **states with below-average profit margins**, guiding inventory decisions.
- Assisted sales leaders in **ranking high/low performers**, refining incentive planning.
- Allowed scenario modeling with **discount simulations**, projecting margins under multiple conditions.

---

## 🛠️ How It Was Created

### 📊 Power BI Features
- **Interactive visuals** for sales by region, segment, sub-category, and customer
- **DAX measures** for:
  - Target vs Actual Sales
  - MoM/YoY growth
  - Profit margin calculations
  - RFM Score & CLV
- **Analysis tabs** included:
  - Sales Overview & Target Achievement
  - Customer Reports (RFM, CLV)
  - Product & Category Insights
  - What-If Analysis for discount impact
  - Pareto Analysis (top customer contribution)
  - Salesperson Performance
  - State- and Segment-level profit distribution

---

### 🐍 Python Integration

Python was used for **data preprocessing** and **feature engineering**, such as:
- RFM calculation (Recency, Frequency, Monetary value)
- CLV metrics (average purchase value × frequency × lifespan)
- Data cleanup (date parsing, null handling, duplicate removal)
- Segment tagging for customer health (Dormant, Loyal, At-Risk)

---

## 📌 Key Takeaways
- Total Sales in 2021: ~$657K | Target Achieved: 98.98%
- Top sales performers: Jackson Tracy, Matt DeCherney, Salem Turner
- Top-selling sub-categories: Binders, Paper, Phones, Furnishings
- Customer Segmentation:
    - Most Valued Customers: ~7%
    - At-Risk Customers: ~1.2%
- Top states by orders: California, New York, Texas
- Return rates flagged higher in categories like Binders & Appliances
- Some product categories (e.g., Tables, Fasteners) showed negative margins
- What-If Analysis: 10% discount forecasted a profit margin of 22.44%

---

## 🧰 Tools Used
- Power BI:	Dashboarding, DAX measures, KPI tracking
- Python: (pandas, numpy)	Data wrangling, RFM & CLV metrics, simulation logic
- Excel / CSV:	Raw data source imports
