# HR Data Analytics
Designed a Power BI dashboard to track employee data including attendance, workingdays and leaves. Dashboard streamlined the HR processes and increased efficiency. This dashboard can save the hours of work for HR.

## Table of Contents
- [Project Overview](#project-overview)
- [Business Task](#business-task)
- [Data Sources](#data-sources)
- [Data Cleaning/Preparation](#data-cleaningpreparation)
- [Result/Findings](#resultfindings)
- [Limitations](#limitations)

### Project Overview
The HR Data Analytics Dashboard uses Power BI,Power Query and DAX Query to analyze employee attendance data and provide insights into attendance patterns. The data is  cleaned and transformed using Power Query and DAX Query. Dashboard is created with  visualizations, measures, KPIs and slicers to help HR identify areas for improvement.

### Business Task
To understand the Presence,Work From Home and Sick Leave Percentage over the period of time and on different days of week.

### Data Sources
Attendance Data: The primary dataset used for this analysis is the "Attendance Sheet 2022-2023_Masked.xlsx" file, containing detailed information about employees attendance.

### Data Cleaning/Preparation
In the initial data preparation phase, I performed the following tasks:
- Removed unwanted columns.
- Changed the datatypes.
- Checked for duplicate values and removed them.
- Formatted date data into DD/MM/YYYY date format.
- Formatted all numerical data into Number format with either no decimals or up to 2 decimals.
- Sorted by date to find the first and last date of the dataset, which indicated that 3 months of activity were captured.
- Removed the errors.

![HR_Data_Analytics](https://github.com/rohanyg/HR_Data_Analytics/assets/136742005/50ca7c3f-e098-4fe4-a2a9-7956085862c7)

### Result/Findings
The analysis results are summarized as follows:
- Around 11% of employees prefer to work from home on Thursday and Friday.
- Around 93% of employees will be present on Monday and Tuesday.
- Sick leave percentage on some days is above 5%, helping in finding reasons for sick leaves. It also enables the company to take better measures for sanitization.
- It helps in better utilisation of the resources like doing team meeting on a day when majority of the people are present in the company.

### Limitations 

- Human behavior is complex and influenced by numerous factors. While data analytics can reveal correlations, it might not always provide a complete understanding of the underlying causes. 
- It might not always accurately predict future behavior. For instance, trends observed in the past might not hold in the future due to changing circumstances within the organization or external factors.
- Misinterpretation of results can lead to inappropriate decision-making.
