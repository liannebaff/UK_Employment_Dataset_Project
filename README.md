# 💼 UK Employment Dataset Project

### 📝 Project Summary
This Tableau project visualises employment trends across the UK from 2011 until 2014 using the EMSI Job Change UK Dataset. The dashboard allows users to explore employment levels, percentage changes and patterns across cities, industies and sub-industries. 

The aim of this project was to identify key shifts in employment during this period, identify the industrues and regions with the largest growth or decline, and provide an interactive tool for comparing employment patterns across sectors and locations. Users can filter by city, industry, or sub-industry, making it easy to uncover insights and understand historical labour market dynamics.

[Link to Dashboard](https://public.tableau.com/app/profile/liannebaff/viz/Employmentdataset_17604337489870/UKEmploymentData2011-2014#1)

### 🎯 Key Skills Demonstrated:
`TABLEAU DESKTOP` `TABLEAU PUBLIC` `CALCULATED FIELDS` `TREND ANALYSIS` `INTERACTIVE DATABASE DESIGN` `USE OF FILTERS`

### 🗂️ Dataset Overview
The dataset contains UK employment statistics for 2011 and 2014 and includes employment counts and the change in employment between 2011 and 2014 and the % change in employment by industry, sub-industry and location.

---
### 🧩 Data Preparation
No data cleaning required. Most of the preparation, such as renaming columns for clarity, defining data types and creating calculated fields were completed in Tableau. The dataset was already structured in a suitable format for analysis.

---
### 📊 Dashboard Overview
An overview of the charts within the dashboard is included below. In order to make the dashboard interactive, filters have been applied to the charts, this allows users to explore UK employment patterns efficiently.

**1) Average Change in Employment by City (%)**
A geographical map displaying the average change in employment (%) for each UK city. Highlighting regional differences in employment distribution.

**2) Employment by Industry (2014)**
A treemap chart showing the amount of people employed per industry in 2014, identifying the leading industries by employment in 2014.

**3) Top 10 Sub-industries by Change in Employment**
A packed bubble chart illustrating the sub-industries with the highest changes in employment, between 2011 and 2014, providing a detailed breakdown of sector performance.

**4) Change in Employment by Industry**
A bar chart highlighting the industries that experienced the largest changes in employment (increase or decrease) over the period from 2011 to 2014.

[![UK Employment Dashboard](https://github.com/user-attachments/assets/5da39151-7c11-4029-ba95-3f99f23f093d)](https://public.tableau.com/app/profile/liannebaff/viz/Employmentdataset_17604337489870/UKEmploymentData2011-2014#1)

---
### 🪞 Reflections
- The dashboard enables users to quickly identify trends, compare categories and extract insights to support data-driven interpretation of historical employment changes.
- London had the highest change in employment (%) whereas Aberdeen and Edinburgh had the lowest.
- Professional, Scientific and Technical Activities experienced the largest change in employment whereas the Information and Communication industry experienced the lowest change.
- The top sub-industry by employment change was Real Estate Activities.
- There are some limitations in the dataset, it only covers 2011 to 2014 and it does not provide demographic and wage information, which limits analysis of workforce composition and job quality.

  ---
  ### 📁 Files in This Repository  
- **[EMSI_JobChange_UK.xlsx](EMSI_JobChange_UK.xlsx)** 
&nbsp;  
  **Worksheet(s):**
  - <small><strong>1 digit:</strong> change in employment at the industry level</small> 
  - <small><strong>2 digit:</strong> change in employment at the sub-industry level</small> <br> <br>
 

### 📋 Dataset Structure

**Worksheet 1: 1 digit**

| Column Name           | Description                                                |
|-----------------------|------------------------------------------------------------|
| City                  | City in the United Kingdom (UK)                            |
| Country               | Country name                                               |
| SIC Code              | Standard Industrial Classification code, Industry          |                                                 
| Industry              | Title of Industry                                          |
| Jobs 2011             | Employment count in 2011                                   |
| Jobs 2014             | Employment count in 2014                                   |
| Change                | Difference in Employment between 2011 and 2014             |
| % Change              | Difference in Employment between 2011 and 2014 (%)         |


**Worksheet 2: 2 digit**

| Column Name           | Description                                                |
|-----------------------|------------------------------------------------------------|
| City                  | City in the United Kingdom (UK)                            |
| Country               | Country name                                               |
| SIC-1                 | Standard Industrial Classification code, Industry          |                                                                                                                              | SIC-1 name            | Title of Industry                                          |      
| SIC-2                 | Standard Industrial Classification code, Sub-industry      |
| Industry              | Title of Sub-industry                                      |
| Jobs 2011             | Employment count in 2011                                   |
| Jobs 2014             | Employment count in 2014                                   |
| Change                | Difference in Employment between 2011 and 2014             |
| % Change              | Difference in Employment between 2011 and 2014 (%)         |
