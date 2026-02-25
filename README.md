

# **Customer Churn Analysis (SQL & Power BI)**

## **Business Context**  
Customer retention is essential for subscription‑based and service‑driven businesses. Understanding why customers leave helps organizations reduce churn, improve customer experience, and protect recurring revenue.

## **Problem Statement**  
Analyze customer data to identify key drivers of churn and provide actionable recommendations to improve retention and reduce revenue loss.

## **Dataset Overview**  
- ~5,000 customer records  
- Customer demographics  
- Tenure and contract type  
- Service usage metrics  
- Support interaction history  
- Monthly and total charges  
- Churn indicator (Yes/No)

## **Tools Used**  
- **SQL Server**  
- **Python (Pandas)** for cleaning and feature engineering  
- **Power BI** for interactive dashboards and visual analysis  
- **Excel** for validation and quick summaries  

## **Methodology**  
1. **Data Exploration & Validation**  
   - Inspected dataset structure, missing values, and data types.  

2. **Data Cleaning (Python)**  
   - Converted numeric fields, handled missing values, standardized categories, and removed duplicates.  

3. **Feature Engineering**  
   - Created **Tenure Groups**, **Monthly Charge Bands**, and a **ChurnFlag (0/1)** for analysis.  

4. **SQL Analysis**  
   - Segmented churn by tenure, monthly charges, and contract type.  
   - Calculated churn rates across customer segments.  

5. **Power BI Visualization**  
   - Built interactive dashboards to visualize churn patterns, customer segments, and risk indicators.  

## **Key Insights**  
- **Short‑tenure customers** showed the highest churn rates.  
- **Month‑to‑month contracts** had significantly higher churn than long‑term contracts.  
- **High support interaction + low service usage** strongly correlated with churn.  
- **Higher monthly charges** were associated with increased churn likelihood.  

## **Business Recommendations**  
- Introduce **loyalty incentives** for early‑tenure customers.  
- Promote **discounted annual or multi‑year contracts**.  
- Improve **support response times** and reduce wait durations.  
- Launch **proactive engagement campaigns** for low‑usage customers.  

## **Project Structure**  
```
├── data_cleaning.py
├── feature_engineering.py
├── churn_by_tenure.sql
├── churn_by_monthly_charges.sql
├── churn_by_contract.sql
├── powerbi_dashboard.pbix
├── README.md
```

---


