# Business User Service Availability Dashboard Using Power BI
## Table of Contents
1. Project Objective
2. Dataset Description
3. Preparing Data for Analysis
4. Visualizations
5. Project Insights
   
The objective of this dashboard is to monitor the business user service availability, specifically focusing on tracking no-shows, planned and unplanned leaves, and attrition. This dashboard provides a detailed breakdown of service availability, identifying trends across regions, sites, and managers, as well as offering insights into reasons for no-shows. It enables stakeholders to make data-driven decisions to improve service availability and optimize workforce management.

## Dataset Description
Planned Leave: Total number of planned leaves taken by employees.
Un-Planned Leave: Total number of unexpected leaves taken.
Attrition: The number of employees who have left the company (attrition rate).
Skill: Tracks the total number of employees with the required skillsets for the service.
No Show: The number of instances where employees did not show up for work.
Availability: Total service availability in relation to the committed hours.
Committed: Total number of hours employees were committed to work.
This dataset tracks data continuously over a specified period, allowing for up-to-date monitoring of KPIs.

## Preparing Data for Analysis
Data Cleaning: Filtered for incorrect or missing entries such as incorrect dates or data mismatches.

Calculated Fields:

Created new fields such as the percentage of no-shows, service availability rates, and trends based on time (e.g., weekly or monthly).
Data Transformation:

Used Power Query to clean and shape the data.
Created date fields for tracking no-show trends over time, region, site, and manager.
Data Filters: Implemented filters such as Month, Region, Customer, Location, and Central Account Manager for customized analysis.

## Visualizations

### Business User Service Availability Dashboard – Main View Summary
This Business User Service Availability Dashboard provides a powerful overview of service-related metrics for business users, highlighting availability, leave, no-shows, and regional or site-based insights. The dashboard integrates a variety of visualizations to help managers and decision-makers monitor the health of their workforce in real-time and spot trends that impact service delivery.

![image](https://github.com/user-attachments/assets/03e7571d-e068-47a7-812a-e642328327d2)

---

### 1. KPI Cards (Top Row)
Planned Leave (126): Shows the total planned leave taken by employees, with a no-show rate of 26.75%.
Unplanned Leave (87): Represents the number of unplanned leave instances with an 18.47% no-show rate.
Attrition (258): Total employee attrition with 54.78% no-show rate, a significant factor to monitor.
Skill (0): Indicates no employees currently available with specific skills (if applicable).
Total No Show (471): Cumulative no-show count, tracking a 100.00% no-show rate.
Availability (1202): Total available hours, equating to 71.85% of committed hours.
Committed (1673): Total committed hours, indicating 100.00% service commitment.

![image](https://github.com/user-attachments/assets/fc0a982d-f0c3-4885-aec9-b653760c9a87)

---

### 2. No Show Reason (Bar Chart)
Objective: A breakdown of the reasons for no-shows across various categories such as Remote Location, Resource Shortage, Late Reporting, and Accident.
Key Insights: The most frequent reasons for no-shows are Remote Location (153) and Resource Shortage (124), highlighting areas that require intervention.

![image](https://github.com/user-attachments/assets/282e6c25-398c-4602-8130-b8ddba1ff2d9)

---

### 3. No Show - Manager Wise (Bar Chart)
Objective: This bar chart shows no-shows categorized by individual managers.
Key Insights: Vinod Bhan (164) has the highest no-show count, followed by Avadhesh Jha (102) and Kunal Sapre (60). Managers with higher no-show counts may need to investigate reasons or implement changes to improve attendance.

![image](https://github.com/user-attachments/assets/0aa3c4fa-01be-4bcf-8897-661caeb4653c)

---

### 4. No Show - Region Wise (Donut Chart)
Objective: This donut chart shows the percentage distribution of no-shows across different regions.
Key Insights: The West region accounts for the largest percentage of no-shows (43.9%), followed by the North (28.2%) and South (25.7%), indicating a potential regional issue in these areas.   

![image](https://github.com/user-attachments/assets/f82adb80-c8b9-47e3-9f79-1bacc68e0925)

---

### 5. No Show Trend - Region Wise (Area Chart)
Objective: Displays monthly trends of no-shows broken down by region.
Key Insights: Peaks in no-shows are visible in August and September, particularly in the West region, indicating seasonal trends or specific issues in these months.


![image](https://github.com/user-attachments/assets/f1f16d47-3617-41ba-a285-d92b098f09ad)

---

### 6. No Show - Site Wise (Bar Chart)
Objective: This chart provides a breakdown of no-shows based on various sites or client locations.
Key Insights: Suzlon (196) and MAX (66) have the highest no-show rates among sites. Further analysis may be needed to address site-specific issues that contribute to no-shows.

![image](https://github.com/user-attachments/assets/48586c8f-51bd-474d-9632-e77cb7babde4)

---

### 7. No Show Continuity - Location Wise (Line Chart)
Objective: This chart is activated when clicking the replace icon on the Site Wise chart. It provides a breakdown of no-show continuity across various locations, tracking when no-shows started, how they continued over time, and when they ended.

![image](https://github.com/user-attachments/assets/93a0b1ab-10ee-482f-a4b7-854bf4d84ef3)

---

## Project Insights
High No-Show Rates in Specific Regions:
The West region consistently shows the highest no-show rates, indicating potential logistical or workforce management challenges that need attention.

Manager-Specific No-Show Trends:
Certain managers such as Vinod Bhan and Avadhesh Jha have notably higher no-show counts, potentially due to team-specific challenges. Stakeholders may need to work with these managers to improve team performance.

Seasonal Trends in No-Shows:
The area chart reveals an increasing trend of no-shows during August and September, particularly in the West region. This could be due to seasonal factors or external issues such as vacations or health concerns.

Site-Specific Challenges:
Some sites like Suzlon and MAX experience significantly higher no-show rates compared to others, suggesting that site-specific interventions are necessary to address potential issues like poor working conditions, commute challenges, or resource shortages.
