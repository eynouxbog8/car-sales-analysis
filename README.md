# Car Sales Analysis: Market Demand, Pricing & Sales Concentration

## Project Overview
This project analyses car sales data using SQL and Excel to identify key performance drivers across manufacturers. The focus is on understanding **sales volume, pricing strategy, and product mix**, and evaluating how these factors influence company performance.

A key part of the analysis is measuring **sales concentration**, highlighting the extent to which companies rely on a single body style to drive total sales.

---

## Key Business Questions
- Which companies drive the highest sales volume and pricing power?  
- Which body styles dominate overall market demand?  
- What body styles drive sales at a company level?  
- To what extent do companies rely on a single body style for total sales?  

---

## Dashboard Preview
![Dashboard Preview](images/dashboard-preview.png)

---

## Key Insights
- SUVs are the most popular body style, with **6,374 units sold**, closely followed by hatchbacks at **6,128 units**, indicating strong demand for both utility and compact vehicles across the market.  
- Sales concentration varies significantly across manufacturers, with **Jaguar deriving 100% of its sales from a single body style**, highlighting extreme product dependency.  
- In contrast, **Ford shows a much more diversified portfolio**, with its top body style contributing only **27% of total sales**, indicating lower exposure to demand shifts.  
- The wide range in concentration levels suggests that while some companies pursue **focused product strategies**, others benefit from **portfolio diversification**, reducing risk.  

---

## Business Implications
- Manufacturers with high concentration (e.g. Jaguar) face **significant revenue risk** if demand for their primary body style declines.  
- Strong demand for SUVs and hatchbacks suggests opportunities for **production prioritisation and targeted marketing strategies**.  
- Diversified companies (e.g. Ford) may be better positioned to **withstand changes in consumer preferences**.  
- Understanding product dependency can support **strategic decisions around product development and market positioning**.  

---

## Methodology
- Aggregated sales data by **company and body style**  
- Used **SQL (T-SQL)** to calculate total sales and average price  
- Applied **DENSE_RANK()** to identify top-selling body styles per company  
- Calculated **Sales Concentration (%)** to measure dependency on top-performing products  
- Built a structured **Excel dashboard** to visualise KPIs and insights  

---

## Key Metric
**Sales Concentration (%) = Top Body Style Sales / Total Company Sales**

This metric is used to quantify how dependent each company is on a single product category.

---

## Tools Used
- SQL (T-SQL)  
- SQL Server Management Studio (SSMS)  
- Microsoft Excel (dashboard & visualisation)  
- Kaggle (data source)  

---

## Project Structure
car-sales-analysis/
│
├── data/
├── sql/
├── dashboard/
│   └── car-sales-dashboard.xlsx
├── images/
│   └── dashboard-preview.png
└── README.md

---

## Future Improvements
- Add interactive filters (slicers) to the dashboard  
- Extend analysis to include time-based trends  
- Enhance dashboard design and user experience  
- Incorporate additional metrics such as revenue and profitability  
