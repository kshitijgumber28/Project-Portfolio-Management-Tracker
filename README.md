# Project Portfolio Management Dashboard

## Overview

This project is a **Project Portfolio Management Dashboard** developed in **Power BI** to monitor project performance, resource allocation, and project risks through a centralized reporting system. The dashboard enables project managers and stakeholders to track project progress, employee workload, task completion, and risk exposure while supporting data-driven decision-making.

---

## Business Problem

Organizations managing multiple projects often struggle to track project progress, resource utilization, and risk exposure in a centralized manner. This makes it difficult to identify delays, workload imbalances, and critical risks before they impact project delivery.

---

## Solution

Developed a **Power BI dashboard** using a **Star Schema Data Model** to analyze project performance, employee workload, and project risks. The dashboard combines KPI tracking, interactive visualizations, and management insights to provide a comprehensive view of project portfolio health.

---

## Dashboard Pages

### 1️ Executive Summary
- Portfolio-level KPIs
- Project completion tracking
- Task status distribution
- High-risk project monitoring

### 2️ Project Performance
- Project-wise completion rates
- Task distribution by project
- Risk exposure by project
- Performance comparison across projects

### 3️ Resource Analytics
- Employee workload analysis
- Task allocation tracking
- Completion rate by employee
- Workload vs. performance analysis

### 4️ Risk Dashboard
- Risk severity distribution
- Risk type analysis
- Risk trends over time
- Project-level risk monitoring

### 5️ Insights & Recommendations
- Key project observations
- Executive insights
- Risk mitigation recommendations
- Portfolio-level findings

---

## Data Model

The dashboard follows a **Star Schema** design.

### Fact Tables
- `Fact_Tasks`
- `Fact_Risks`

### Dimension Tables
- `Dim_Projects`
- `Dim_Employees`
- `Dim_Status`
- `Dim_Priority`

Relationships were established using **Primary Keys** and **Foreign Keys** to ensure efficient reporting and filtering.

---

## Key Features

- Interactive Power BI Dashboard
- Star Schema Data Modeling
- DAX-Based KPI Calculations
- Project Completion Tracking
- Resource Utilization Analysis
- Risk Monitoring & Management
- Executive Reporting
- Business Intelligence Storytelling

---

## Key Insights

- Only one project crossed the **50% completion mark**, indicating that most projects remain in the early-to-mid stages of execution.
- **Scope Creep** emerged as the most common project risk, highlighting the impact of expanding project requirements on timelines and resources.
- Employee workload and completion rates did not show a strong relationship, suggesting that workload optimization alone may not improve performance.
- Overall project progress remains moderate, emphasizing the need for continued monitoring of high-risk and low-completion projects.

---

## Skills Demonstrated

- Power BI
- Data Modeling
- DAX
- Business Intelligence
- Project Analytics
- Risk Analytics
- KPI Design
- Data Visualization
- Dashboard Development
- Analytical Storytelling

---

## Tools & Technologies

| Tool | Purpose |
|--------|----------|
| Power BI | Dashboard Development |
| DAX | KPI & Measure Calculations |
| CSV Files | Data Storage |
| Star Schema | Data Modeling |

---

## Dashboard Preview


```text
screenshots/
├── Schema Structure.png
├── Executive Summary.png
├── Project Performance.png
├── Resource Analytics.png
├── Risk Dashboard.png
└── InsightsPage.png
```

---

## Future Improvements

- Integration with real project management datasets
- Automated data refresh
- Advanced risk scoring model
- Schedule variance and delay tracking

---

## Note

This project uses a **synthetic dataset** created for learning and portfolio purposes. The dashboard is intended to demonstrate skills in **Power BI, data modeling, project analytics, and business intelligence reporting**.

---

- Power BI
- Python
- SQL
- R
- Data Analytics
- Business Intelligence
