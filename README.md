# Introduction
:mega: 

:computer: Check out my Tableau profile here: [Tableau Profile](https://public.tableau.com/app/profile/mei.liu4813/vizzes)
# Background
### This Tableau portfolio records my learning journey following Kirill Eremenko's [course](https://www.udemy.com/course/tableau10).
# Tools I Used
- **Tableau Desktop and Public:**
- **Microsoft Excel:**Sourcedata in this project are spreadsheets. I use Excel to examine raw data as its the first step of ETL.
- **Git and Github:** My go-to for version control and tracking my project progress.

# The Vizzes

### 1. Basic Bar Charts

Datasource: [Office_Supplies](Datasources/OfficeSupplies.csv)

This bar chart shows which sales representatives generated the highest sales, categorized by region.

![Total_Sales](https://github.com/user-attachments/assets/6647d108-67f9-492a-84c5-f7fe7d929025)
*Bar chart with total sales by sales representatives categorized by region* 

### 2. Time series, Aggregation, and Filters

Datasource: [Long_term_unemployment_statistics](Datasources/Long-Term-Unemployment-Statistics.xlsx)

![Long_Term_Unemployment_Analysis](Assets/Long_Term_Unemployment_Analysis.png)
*Area chart aggregating number of umployment filtered by age groups*


### 3. Dashboards
Datasource: [AmazingMartEU2](Datasources/AmazingMartEU2.xlsx)

Here are my findings:
- This dashboard features a map of Europe alongside scatterplots that visualize customer margins, segmented by performance. Margins below 50% are displayed in red to indicate underperformance, while margins above 50% appear in blue, representing satisfactory performance.
- A Year filter is available and applies to all worksheets across the workbook, allowing users to focus on specific time periods. Additionally, an action filter enables users to interact with the dashboard, dynamically updating the customer scatter plot based on their selections
  
![Dashboard](Assets/Customer%20Margin%20Dashboard.png)

*Dashboard filtered by country with customer margin scatter plots*

### 4. Joining and Blending Tables

Datasource: [AmazingMartEU2](Datasources/AmazingMartEU2.xlsx)

Here are my findings:
- The furniture department follows a linear target, while the office supplies department has a quarterly target. In contrast, the technology department reviews and sets its target annually for the following year.

- The furniture department has consistently underperformed, suggesting their target may need to be reassessed. The technology department shows clusters of underperformance, indicating that a quarterly or monthly target may be more appropriate. The office supplies department has the fewest underperforming months, suggesting that a quarterly target is well-suited for this department.

![Dual Axil Chart](Assets/Department_Performance_Review.png)
*Dual axis chart to visualize monthly department performances*

### 5. Relationships

Datasource: [Brazilian_E-Commerce_Public_Dataset_by_Olist](/https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

Here is the task: Create a street map to illustrate seller geographic information.

![Street_Map](Assets/Seller_Geo_Map.png)
*Street map showing sellers' geo location*

### 6. Storytelling from Dashboards 

Datasource: [UK_Bank_Customers](Datasources/UK_Bank_Customers.csv)

Here are some insights derived from this dashboard:

- The majority of customers in Scotland are male, blue-collar workers aged 40-50, while in England, customers are predominantly white-collar workers aged 30-40, with an equal gender distribution. This difference may be influenced by London’s status as an economic hub of Europe. Customers from Wales aging between 30 - 40 has above average mid-sized balances. Lastly, in Northern Ireland, customers are dominantly females in young age groups. Consequently, marketing strategies should be tailored for each region according to this analysis.

- This dashboard helps the bank better understand its customer base, enabling it to offer more relevant, customized products based on customer demographics.

![Customer_Demographic_Scotland](Assets/Customer_Demographic_Dahsboard.png)
*Interative dashboard illustrating customer demographic in Scotland*

![Customer_Demographic_England](Assets/Customer_Demographic_Dahsboard_England.png)
*Interative dashboard illustrating customer demographic in England*

![Customer_Demographic_Wales](Assets/Customer_Demographic_Dahsboard_Wales.png)
*Interative dashboard illustrating customer demographic in Wales*

![Customer_Demographic_Northern_Ireland](Assets/Customer_Demographic_Dahsboard_Northen_Ireland.png)
*Interative dashboard illustrating customer demographic in Northern Ireland*

### 7. Data Cleaning and Preparation

Datasource: [Personal_Vehicle_Sales_Global](Datasources/PersonalVehicleSalesGlobal.xlsx)

Cleaned source data after examination with the aid of Tableau *Data Interpreter*. Connected Tableau with sourcedata and *pivoted* year and vehicles sold columns. Updated columns with *MetaData Grid* and fixed geographical data errors in maps.

![Map](Assets/Map.png)
*Vehicles sold map*

### 8. Clusters, Custom Territories, Desgin Features

### 9. Tableau Toolkit



# What I Learned
- :eight_spoked_asterisk: **Data roles in Tableau:**
- :black_nib: **Difference between Action-Highlight and Action-Filter:**
- :date: **When to Blend or Join datasources:** Blend when datasources have different level of granularity or datasources are from different systmes. While join is used when combing data at row level.
- :flashlight: **Dashboard presentation:**

# Conclusion

### Insights
