                  People Analytics — Employee Attrition Analysis
                  

##  📌 **PROJECT OVERVIEW**

This project explores potential employee attrition patterns using a messy HR dataset and transforms the raw data into an interactive Power BI dashboard.

The goal was to identify patterns associated with employee exits and explore potential attrition drivers across areas such as department, job level, overtime, tenure, job role, promotions, compensation, and exit reasons.

### **⚠️ Dataset & Data Quality Context**: 

The dataset was intentionally designed with inconsistencies and data-quality issues to simulate challenges that can occur in real-world HR data.

The dataset contained issues such as:

- Missing values

- Duplicate records

- Inconsistent naming and capitalization across fields such as Department, Attrition, and Overtime

- Invalid or inconsistent dates

- Missing exit dates for active employees

- Missing exit reasons

- Exit dates outside the expected analysis period

- Formatting and validation inconsistencies

These issues were identified and documented during the data-cleaning process before the dataset was used for dashboard analysis.

## **🛠️ Tools & Technologies**

**Python / Pandas** — data cleaning, validation, and preparation

**Power BI** — data visualization and dashboard development

**DAX** — calculated measures and analytical metrics

###  **🧹 Data Cleaning**
Python/Pandas was used to inspect, clean, validate, and prepare the dataset before importing the cleaned data into Power BI.

The cleaning process included:

Inspecting missing and inconsistent values
Standardizing categorical fields
Validating date fields
Identifying duplicate records
Reviewing missing exit dates and exit reasons
Checking exit dates against the expected analysis period
Preparing the cleaned dataset for Power BI analysis

## **📊 DASHBOARD**

The Power BI dashboard consists of an overview of employee attrition and a dedicated Attrition Drivers page.

The analysis explores:

Total employees, 
Total exits, 
Attrition rate, 
Attrition by job level, 
Attrition by overtime, 
Exits by department, 
Exits by job role,
Exits by tenure band,
Exit reasons,
Compensation-related patterns
### Dashboard Overview

![Dashboard Overview](screenshots/dashboard-overview.png)

### Attrition Drivers

![Attrition Drivers](screenshots/attrition-drivers.png)


### **🔎 KEY FINDINGS**
Some of the patterns identified during the analysis included:

- The number of employee exits varied across different promotion histories.
  
- Employees with overtime showed a different distribution of exits compared with employees without overtime.
  
- Manager-related exits were the most frequently recorded exit reason in the dataset.
  
- Compensation-related exits were among the more frequently recorded exit reasons. The compensation-related analysis also identified employees meeting the project’s defined criteria involving salary, tenure, overtime, promotion history, and attrition.
  
- Career growth and better opportunities were also recorded as notable exit reasons.

- Workload appeared among the recorded reasons for employee exits.
  
- Exit patterns varied across departments and job roles.
  
- Average monthly salary among active and exited employees remained relatively similar in the dataset.
  
These findings describe patterns observed in the dataset and do not by themselves establish that a particular factor causes attrition.

## **💡 Business Questions**

The project was designed around questions such as:

* Which departments and job roles have the highest number of exits?

* How does overtime relate to employee attrition?
  
* Are certain job levels associated with higher attrition?
  
* How does tenure differ among employees who leave?
  
* What reasons for leaving appear most frequently?
  
* Are promotion history and compensation-related factors visible in exit patterns?
  
* What data-quality issues could affect the reliability of HR reporting?

  
## **📁 Project Structure**

```text
people-analytics-attrition-dashboard/  
│ 
├── README.md  
├── data/  
│   └── cleaned_dataset.csv 
│  
├── python/  
│   └── data_cleaning.ipynb  
│  
├── powerbi/  
│   └── attrition_dashboard.pbix  
│  
└── screenshots/  
    ├── dashboard_overview.png  
    └── attrition_drivers.png
```
    
##  **🎯 Skills Demonstrated**

Data Analysis  
Python, Pandas, data validation, exploratory analysis

Business Intelligence  
Power BI, DAX, dashboard design, interactive filtering

HR / People Analytics  
Employee attrition analysis, workforce metrics, exit analysis

Data Quality  
Missing-value handling, consistency checks, date validation, categorical standardization
