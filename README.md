# Palmoria-Group-HR-Analysis Using Power BI
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools Used](#tools-used)
- [Process](#process)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Skills](#skills)
- [Conclusions](#conclusions)
- [Recommendations](#recommendations)
- [Acknowledgement](#acknowledgement)
- [links](#links)


### Project Overview
Palmoria Group is a manufacturing company based in Nigeria that has an embroided issues about gender inequality in its 3 regions where there businesses are located. Unfortunately, the media recently published in the news with the headline “Palmoria, the Manufacturing Patriarchy” this doesn’t look good to the owner of the business on their ambition to scale the business to other regions and even overseas. "Disclaimer": All datasets and reports do not represent any company, institution or country, but just a dummy datasets to demonstrate capabilities of Power BI
This project analyses the company's data (Palmoria-Group-HR data) to uncover possible issues and patterns, providing actionable insights that the Palmoria management team would need to address for strategic planning. It focuses more on resolving issues like gender inequality within the organization and its region, and creating meaningful visualizations for the management team.
![PALMORIA GROUP](https://github.com/nanya96/Palmoria-Group-HR-Analysis-using-Power-BI/blob/0bb10c08c632d8d2caa8d84bd19dad7fb7de2e79/PALMORIA%20GROUP.png)

### Data Source
The primary source of the data used here is Palmoria Group Emp-data.csv and Palmoria Group Bonus Rules. xlxs, which was gotten from Incubator Hub for the DSA Data Analysis Capstone Project. The Palmoria Group manufacturing company gave out a data set of 3 different tables which are the bonus mapping, bonus rules and the Palmoria Group emp-data. The bonus mapping and bonus rules consists of 12 rows and 6 columns while the Palmoria Group emp_data consists of 6 columns and 1015 rows. The Palmoria Group emp_data table contains a range of the employees details related to the Palmoria company staffs, such as Employees name, Gender, department, salary, location and rating While the bonus rules and mappings which are the same which consists of 12 rows and 6 columns with the columns which consists of the department and the ratings i.e; very poor, poor, very good, good and average.


### Tools Used 
- Power BI (Data Manipulation and creating reports)


### Process
1.  Data Collection
    - Data loading and inspection.
2.  Data Cleaning:
    - Assigned a generic gender status to some employees that refuse to disclose their gender (text cleaning).
    - Removed some employees without a salary because they are no longer with the company.
    - Removed some departments indicated as “NULL”.
    - Modelling, adjusted the model to the right relationship which is many to many cardinality.
    - Cleaned the Palmoria Group Bonus Rules by data manipulation.
    - Merged the tables; Palmoria Group emp_data table and Palmoria Group Bonus Rules by joining their unique identifier which is the “Department” and "Rating" column so that it gives          the Bonus Rate column.
3.  Analysis and Visualization:
    -	Gender distribution, ratings and salary structure in the company's data were analyzed.
    -	Created dashboards in Power BI.

  
### Exploratory Data Analysis
EDA involved the exploring of the Data to answer some questions about the Data such as;
   - What is the gender distribution in the organization? Distil to regions and departments.
   - Show insights on ratings based on gender
   - Analyse the company’s salary structure. Identify if there is a gender pay gap. If there is, identify the department and regions that should be the focus of management
   - A recent regulation was adopted which requires manufacturing companies to pay employees a minimum of $90,000
       - Does Palmoria meet this requirement?
       - Show the pay distribution of employees grouped by a band of $10,000. For example: How many employees fall into a band of $10,000 – $20,000, $20,000 – $30,000, etc.?
       - Also visualize this by regions.
   - Calculate the amount to be paid as a bonus to individual employees.
   - Calculate the total amount to be paid to individual employees (salary inclusive of bonus).
   - Total amount to be paid out per region and company-wide.


### Skills
- Grouping
- Quick Measures,
- Page Navigation
- Modelling
- Filters

### Conclusions
1. Gender Distribution
   - The gender distribution is most prominent in the Kaduna (Male_182, Female_165, and Not disclosed_14) region followed by Lagos (Male_124, Female_118, and Not disclosed_8) and then Abuja ((Male_159, Female_158, and Not disclosed_18). In the 12 departments, 7 have a higher Male head count, with the Legal department leading (Male_49 and Female_34). Hence, the gender distribution across the company is considered ‘Minimal’.

2. Salary Structure
   - A gender pay gap exists across all regions of the company; at an average Male and Female salary ratio of $74.8k — $72.1k, male employees were noted to earn slightly more in all           regions. Male employees earned more in total terms across 7 (out of 12) departments. On an average salary basis, Male employees earned more in 9 (out of 12) departments across the        company. Given the minimal pay gap, there isn’t sufficient evidence based on available data to conclude if the distribution is reflective of patriarchy. The management needs to get       detailed informations of their employees, in order to get accurate result.

3. Performance Ratings & Bonuses
   - Female employees in overall performed better in the analysis (reflected in higher overall bonuses).

### Recommendations
1. Given the minimality of the gender distribution & pay gap, PALMORIA should consider reviewing its employment, remuneration policy and gathering a well detailed information of their employees, to close the inherent gender gaps and neutralize current negative opinions. 
2. PALMORIA should consider reviewing the salary structure across the company to meet the minimum wage requirement.
3. PALMORIA should consider conducting role-level analysis, are women clustered in junior roles while men dominate senior roles?
4. PALMORIA should consider promoting more females in high-growth roles especially in Accounting and Marketing departments.

### Acknowledgement 
Thank you Incubator Hub DSA (Digital Skillup Africa) for this wounderful experience and insights in learning Data Analysis.

### Links
These are the linkes to my datasets and Power BI report. Please feel free to view the Power BI report to interact with my dashboard.
  - [Palmoria Group emp-data.csv](https://github.com/nanya96/Palmoria-Group-HR-Analysis-using-Power-BI/blob/b51ab0a5ae40c89a5ea60552933902290d266103/Palmoria%20Group%20emp-data.csv)
  - [Palmoria Group Bonus Rules.xlsx](https://github.com/nanya96/Palmoria-Group-HR-Analysis-using-Power-BI/blob/fb1257debed19891e034aca4bb027a1f5b2812bb/Palmoria%20Group%20Bonus%20Rules.xlsx)
  - [Palmoria Group HR Analysis_DSA_Project.pbix](https://github.com/nanya96/Palmoria-Group-HR-Analysis-using-Power-BI/blob/b5d330a8aa0b634cc302aeacc1f53e75a1c5cce4/Palmora%20Group%20HR%20Analysis_DSA_Project.pbix)
