# Project2_Data_Analysis_With_Python
## E-Commerce Revenue Generation Analysis 
### Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Recommendations](#recommendation)

### Project Overview

This data analysis project aims to make inferences from the company data of year 2019 to 2024. By analyzing various aspects of the data to identify relationships and make data-driven recommendations

### Data Sources

Primary dataset used for this analysis which are provided in the files attached to this project are:
-	customer.csv
-	marketing_campaigns.csv
-	transactions.csv
-	web_sessions.csv 

### Tools

- SQL Server: Data extraction 
- Excel: Data cleaning
- Python: Data Analysis
- Tableau: Creating dashboards and reports

### Data Cleaning/Preparation

In the initial data preparation phase, we performed the following tasks:
1. Data loading and inspection,
2. Handling missing values,
3. Data cleaning, formatting, pivoting
4. Putting columns in correct data type and labelling properly

### Exploratory Data Analysis (EDA)

EDA involves exploring the data to answer key questions, such as:

- Do male and female customers differ in average purchase value?
- Is time on site dictating how much is purchase value?
- Do discounted purchases differ in average value from non-discounted purchases?

### Data Analysis

Include some interesting code/ features worked with

```python
customers_transactions.groupby(['gender','product_category'])['purchase_value'].max()
```

### Result/Findings

The analysis results are summarized as follows:
1. There is no significant difference in mean purchase value of the male and female
2. There is no significant relationship between time on site and purchase value
3. There is a significant difference in mean purchase value of the discounted and non-discounted
	
### Recommendations

Based on the analysis, we recommend the following actions:
- Company should not focus their spending on one gender than the other as gender differences does not influence purchase value
- The company should spend less on making client spend more on site as time on site does raise purchase value
- Use of discount with adequate advertisement to create awareness will be effective.

### Limitations

- The data is limited to a sum up in each of the countries involved. There is no detail data about the activities of customers in each country this is a limiting factors as each of the country will differ in many ways. Otherwise, we could explore each country separately
- I had to remove all missing values from the data because they would have affected the accuracy of my conclusions from the analysis. There are still a few outliers but then we can still see that there are correlation between the variables in the data
	
### References
	
- [stack Overflow](https://stack.com)
- Statistics for Data Analysis by Using Python:	Dr. Sandeep Kumar (Quality Guru Inc.) - UDEMY
- Complete SQL Bootcamp - Go from Zero to Hero:     Dr. Jose Portilla (Pierian Training) - UDEMY
- Complete Microsoft Power BI:  By Nikolai Schuler, (Ligency, SuperDataScience Team) - UDEMY
- Microsoft Excel – Excel from Beginner to Advanced:	By Kyle Pew - UDEMY
- Tableau A-Z - Hands-on Tableau:	By Kirill Eremenko, (SuperData ScienceTeam, Ligency)
- Python for Time Series Data Analysis:		By Dr. Jose Portilla (Pierian Training) - UDEMY
- Complete KoboToolbox (ODK), google form Training:	By Alexander Mtembenuzeni - UDEMY
- Map Academy: Get mapping quickly, with QGIS:	By Professor Alasdair Rae - UDEMY
- Map Academy: Taking QGIS to the next level: 		By Professor Alasdair Rae - UDEMY
- The Supervised Machine Learning Bootcamp:		By 365 Careers - UDEMY
