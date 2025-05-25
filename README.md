# A/B Testing Statistical Analysis and Visualization

📋 **Project Description**  
This project presents a comprehensive statistical analysis of A/B test results using Python and visualizes key conversion metrics in Tableau. The primary goal is to evaluate the statistical significance of four important metrics:

- `add_payment_info / session`  
- `add_shipping_info / session`  
- `begin_checkout / session`  
- `new_accounts / session`  

The analysis covers both the overall test and detailed segmentation by various dimensions such as test groups, countries, and device types. Unlike manual methods, this approach automates significance testing using z-tests with dynamically processed data arrays, enabling scalable analysis for multiple metrics without hardcoding each case.

---

### 🛠️ Tools and Technologies
  
- SQL (for data extraction and aggregation in Google BigQuery)  
- Google BigQuery (data warehouse)
- Python (for statistical significance calculation) 
- Tableau (visualization dashboard)  

---

### 📈 Project Workflow

1. **Statistical Significance Calculation**  
   A Python script calculates z-statistics and p-values for the specified metrics by aggregating data from Google BigQuery. The script efficiently processes the data using loops and array operations to handle multiple metrics and segments. The output is a structured dataset ready for visualization.

2. **Visualization in Tableau**  
   The Tableau dashboard presents the calculated metrics and highlights where statistically significant changes occur. It includes filters to explore results by test number and segments, with a custom color palette and layout to differentiate it from standard dashboards.

---

### 📊 Conclusion

The code and methodology are documented clearly, explaining the logic behind the statistical calculations and the interpretation of results.

---

### 🔗 Dashboard Link  
[View Tableau Dashboard](https://public.tableau.com/views/ABTestAnalysis_17459432485280/ABtest?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

