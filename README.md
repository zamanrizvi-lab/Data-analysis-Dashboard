# Data-analysis-Dashboard
I developed a comprehensive project in excel, creating multiple dashboards and table to analyze the data. this process involved several stages, including data preprocessing, data cleaning and data visualization.
Description of "Attrition Rate by gender for Different Age Group"

MIN(1) and MIN(1) for each CF age band.  For pane MIN(1):  Color shows details about Gender.  The marks are labeled by % of Total ATTRITION count and sum of ATTRITION count. The data is filtered on Action (Department), Action (Gender) and Action (Job Role,Job Satisfaction). The Action (Department) filter keeps 3 members. The Action (Gender) filter keeps 2 members. The Action (Job Role,Job Satisfaction) filter keeps 36 members.

MIN(1) Properties

Marks

The mark type is Pie.
The marks are labeled by % of Total ATTRITION count and sum of ATTRITION count.
Stacked marks is off.

Shelves

Rows:	MIN(1), MIN(1)
Columns:	CF age band
Filters:	Action (Department), Action (Gender), Action (Job Role,Job Satisfaction)
Text:	% of Total ATTRITION count and sum of ATTRITION count
Color:	Gender

MIN(1) (2) Properties

Marks

The mark type is Pie.
The marks are labeled by sum of ATTRITION count.
Stacked marks is off.

Shelves

Rows:	MIN(1), MIN(1)
Columns:	CF age band
Filters:	Action (Department), Action (Gender), Action (Job Role,Job Satisfaction)
Text:	Sum of ATTRITION count

Dimensions

CF age band has 5 members on this sheet
Members: 25 - 34; 35 - 44; 45 - 54; Over 55; Under 25
CF age band is sorted manually.
Gender has 2 members on this sheet
Members: Female; Male

Measures

% of Total ATTRITION count ranges from 1.27% to 29.11% on this sheet.
The formula is 
IF [Attrition]='yes' THEN 1 ELSE 0 END
Computes the current value as a percentage of the total.  Totals summarize values from CF age band, Gender.
1 logical table used to determine value:
Sheet1
Sum of ATTRITION count ranges from 3 to 112 on this sheet.
The formula is 
IF [Attrition]='yes' THEN 1 ELSE 0 END
1 logical table used to determine value:
Sheet1
MIN(1) has the value 1 on this sheet.
The formula is 
MIN(1)

Data Source Details

Data Source:	Sheet1 (ceo_king.xls)
Type:	Hyper
Version:	2
Database:	C:/Users/Lenovo/Documents/My Tableau Repository/Datasources/Sheet1 (ceo_HR.xls).hyper
Table:	Extract (Extract.Extract)

1 Logical table:

Sheet1
