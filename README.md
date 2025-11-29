# Power-BI-_Employee-Performance-Analytics-Himanshu-Bhatt-
The goal of this project was to analyze employee performance data to identify trends in:
- Productivity
- Training effectiveness
- Promotion readiness
- Retention risk
The dataset contained 5,000 employee records with attributes such as Employee ID, Department, Job Role, Performance Score, KPI Score, Attendance, Peer Rating, Task Completion, Work Hours Logged, Manager Feedback, Training Hours, and Promotion Eligibility.

**Data Modeling**
I structured the dataset into five tables:
- DepartmentTable → Departments (Sales, Marketing, Finance, HR, IT)
- Employee_Performance_Dataset → Main fact table with KPIs, scores, flags, readiness, risk, etc.
- JobroleTable → Job roles (Accountant, Auditor, etc.)
- PerformancebandTable → Performance categories
- RetentionriskTable → Retention risk categories
  I created 4 relationships between these tables to ensure proper filtering and aggregation.
   I also defined 10 DAX measures such as Avg Working Hours, Avg KPI Score, Promotion Rate, Training Efficiency, Engagement Score, etc., to make the analysis dynamic.

**Dashboard Design**
The dashboard was designed with business storytelling in mind:
- Top KPIs (cards): Avg working hours, performance score, KPI score, peer rating, promotion rate
- Pie chart: Leadership potential (Need Development vs High Potential)
- Bar chart: Performance band distribution
- Donut chart: Training level distribution
- Clustered chart: Promotion readiness by job role
- Filters: Department, retention risk, employee name

 **Storytelling Flow**:
At the top, I placed key metrics for quick insights. Then I used charts to break down leadership potential, performance bands, and training levels. Finally, I added filters so managers can drill down by department, job role, or retention risk.

**Business Insights**
The dashboard provides actionable insights for HR managers and leadership teams:
- Identify departments with high retention risk
- Measure whether training hours are translating into better performance
- Track promotion readiness to ensure high performers are considered for career growth
- Visualize leadership potential for succession planning

 **Key Steps in the Project**
- Data Cleaning & Preparation → Ensured consistency and accuracy across 5,000 records
- Data Modeling & Relationships → Built a star schema with fact and dimension tables
- DAX Measures → Created advanced calculations for KPIs and efficiency metrics
- Visualization Best Practices → KPIs at the top, charts below, filters for interactivity
- Business Storytelling with Data → Designed the dashboard to support HR decision-making
