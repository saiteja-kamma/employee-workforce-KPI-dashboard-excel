# employee-workforce-KPI-dashboard-excel
End-to-end HR workforce and KPI analytics dashboard built entirely in Excel using pivot tables, charts, and formulas to analyse headcount, attrition, performance, attendance, and training impact.
Employee Workforce & KPI Analytics Dashboard (Excel)
Project Overview

This project combines workforce analytics and employee KPI performance analysis into a single, structured Excel-only dashboard solution.

All analyses and visualisations were created manually using Pivot Tables, Pivot Charts, slicers, and Excel formulas, without Power BI or external BI tools.
The dashboards are designed to mirror real HR reporting used by management and HR teams.

Tools Used

Microsoft Excel

Pivot Tables & Pivot Charts

Slicers and filters

Calculated fields and KPI logic

Conditional formatting

Manual dashboard layout

Data Preparation (Excel)

Generated employee-level HR data (ID, name, department, job title, goals achieved%, attendance%, client feedback, training completed, overall kpi score, normalised kpi score).

The overall kpi score was calculated using the following logic:
=(E2*0.4)+(F2*0.2)+(G2*1)+IF(H2="Y",0.5,0)

The normalized kpi is calculated using the following logic:
=(E2*0.4)+(F2*0.2)+((G2/6)*30)+IF(H2="Y",10,0)

Workforce Analytics Coverage

Total employees and active vs inactive split

Department-wise employee distribution

Age-wise and gender-wise workforce breakdown

Exit count by age group, gender, and department

Average years of service by role and gender

Top 10 highest-paying employees

KPI & Performance Analytics Coverage

Overall KPI score and normalised KPI

Goals achieved %, attendance %, and client feedback

KPI comparison by department and job title

KPI score distribution (bins)

Individual employee KPI tracking

Training completed vs not completed impact on KPI

Key Insights Enabled

Clear visibility into workforce structure and stability

Identification of departments with higher exits and tenure gaps

Comparison between raw and normalised KPI performance

Relationship between attendance, KPI score, and goals achieved

Evaluation of training completion impact on employee performance

Why This Project

Demonstrates advanced Excel analytics capability

Shows ability to build management-ready dashboards without BI tools

Reflects real-world HR reporting combining people metrics + performance KPIs

Strong example of Excel being used as a full analytics tool, not just spreadsheets

Notes

Data is simulated for learning and portfolio purposes.

All visuals are manually built inside Excel, similar to corporate HR MIS dashboards.
