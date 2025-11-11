# Election Analytics Dashboard (Power BI)

## 📌 Problem Statement
Understanding election dynamics requires analysing vast amounts of historical voting data across multiple geographic levels  
Traditional spreadsheets make it hard to spot trends or shifts in political patterns over time  

This project aims to visualise election data through an interactive Power BI dashboard — allowing users to explore party performance, competitiveness, and voter trends across states and counties

---

## Objectives
- Analyse voting trends and voter composition across U.S. states and election years  
- Compare party performance (Democrat, Republican, Other) over time
- Visualise state-level results, including vote share, winning margins, and loyalty patterns
- Present insights through interactive dashboards using KPI cards, maps, and charts

---

## Approach
1. **Data Cleaning (Excel):**  
   - Cleaned and standardisesd historical U.S. election data across multiple years
   - Remove duplicate entries and unified inconsistent state/ county names
   - Create a new 'State + Party' field to enable accurate geo-mapping  
   - Calculated turnout rates and normalized results for fair comparison

2. **Modeling (Power BI):**  
   - Built measures for KPIs such as total voters, party percentages, and year-over-year change
   - Used DAX to calculate vote differences, winning margins, and party loyalty metrics

3. **Visualisation & Interactivity:**  
   - Designed dynamic dashboards with filters for State, Year and Party
   - Created KPI cards, stacked bar charts, geo-maps and trend visuals for interactive storytelling 
   - Organised insights across four main pages — Home, Timeline, State and Loyalty — to explore results from multiple perspectives

---

## Key Insights
- Clear regional patterns of political stability and volatility
- Identification of states with increasing competitiveness
- Insights into how turnout correlates with margin of victory

---

## Tools & Technologies
- **Power BI**
- **DAX**
- **Excel** (for initial data cleaning)

---

## Dashboard Preview
![Election Dashboard Preview](assets/dashboard-preview.png)

*(Click the image to enlarge — or download the .pbix file from the `/reports/` folder.)*

---

## File Access
- [Download .pbix file](reports/dashboard.pbix)

---

> _Developed by Nathaniel Tan — exploring data through Python, SQL, and visualisation._
