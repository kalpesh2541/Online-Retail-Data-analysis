Online Retail Data Analysis (Power BI / Tableau)

## Project Overview
This project focuses on analyzing an online retail dataset using **Power BI** or **Tableau** to address key questions posed by the CEO and CMO.  
The analysis aims to provide insights into revenue trends, top-performing countries, high-value customers, and product demand across regions.

---

## Data Preparation & Cleaning
Before creating the visuals, the dataset was cleaned to ensure accurate analysis:
- **Quantity Check:** Excluded records where `Quantity < 1` (negative or invalid entries).
- **Unit Price Check:** Excluded records where `Unit Price < 0`.  
- Data transformation methods and conditional logic were applied to filter out bad data.

---

## Visualizations

### **Question 1: Revenue Time Series (2011)**
- **Objective:** CEO wanted to analyze seasonal trends in revenue for 2011.  
- **Visual:** A time series line chart displaying **monthly revenue** for 2011.  
- **Insight:** Helps identify seasonal patterns and supports forecasting for the upcoming year.

<img width="1290" height="729" alt="Answer 1" src="https://github.com/user-attachments/assets/e268f2e3-3ded-416b-ba74-c128c4c0923b" />
## **Answer 1**
- Monthly revenue fluctuated throughout 2011, starting at $0.56M in January and peaking at $1.46M in November.
- The highest seasonal demand occurred in Q4 (September–November), highlighting strong holiday-driven sales.
- Revenue declined significantly in December ($0.3M), likely due to data capture timing or reduced post-holiday demand.
- Insight: Clear seasonality exists, with sales momentum building toward the yearend holiday season. This trend can be leveraged for forecasting and future promotional campaigns.
  
---

### **Question 2: Top 10 Countries by Revenue (Excluding UK)**
- **Objective:** CMO wanted to view the **top 10 revenue-generating countries**, along with quantities sold.  
- **Visual:** A bar chart showing revenue by country, with quantity as an additional metric.  
- **Note:** United Kingdom was excluded to highlight international performance.  
- **Insight:** Provides a clear view of the most profitable global markets.

<img width="1290" height="727" alt="Answer 2" src="https://github.com/user-attachments/assets/213caae2-54ee-4a2e-ab87-d69bfd637c2e" />
## **Answer 2**
-The top-performing countries were:
  --Netherlands: $0.28M
  -- EIRE (Ireland): $0.26M
  -- Germany: $0.22M
  -- France: $0.20M
  -- Australia: $0.20M
- These markets also showed strong demand in terms of quantities sold, not just revenue.
- Insight: Western Europe and Australia present solid, consistent markets outside the UK, with potential for targeted marketing and expansion strategies.

### **Question 3: Top 10 Customers by Revenue**
- **Objective:** CMO wanted to identify high-value customers.  
- **Visual:** A descending bar chart with the top 10 customers ranked by revenue.  
- **Insight:** Allows the company to target and retain its most valuable customers.

---

### **Question 4: Product Demand by Country (Excluding UK)**
- **Objective:** CEO wanted to evaluate product demand across all countries to identify expansion opportunities.  
- **Visual:** A map or heatmap visualization showing **demand intensity by country**, excluding the UK.  
- **Insight:** Provides a global view of demand, highlighting regions with potential for growth.

---

## Tools Used
- **Power BI** or **Tableau** (Free trial versions available)  
- Data cleaning and transformation using built-in features  

---

## Deliverables
- Power BI File: `Online_Retail_Analysis.pbix`  
- Tableau File: `Online_Retail_Analysis.twbx`  

---

## Conclusion
This analysis provides actionable insights for both the CEO and CMO:
- **CEO:** Can track seasonal revenue trends and identify expansion opportunities.  
- **CMO:** Gains visibility into top-performing countries and high-value customers.  

By leveraging these insights, the retail store can make informed strategic decisions to drive growth and customer satisfaction.
