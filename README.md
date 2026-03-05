## Healthare Management Analytics Dashboard

![Power BI Dashboard](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Data Analytics](https://img.shields.io/badge/Data-Analytics-blue?style=for-the-badge)
![Healthcare Analytics](https://img.shields.io/badge/Healthcare-Analytics-0A66C2?style=for-the-badge)
![Business Intelligence](https://img.shields.io/badge/Business-Intelligence-purple?style=for-the-badge)

---

## Project Headline

An **interactive Power BI analytics solution** designed to analyze hospital financial performance, operational efficiency, and patient service utilization to support **data-driven healthcare management decisions**.

---

## Project Overview

Healthcare organizations operate with complex financial structures, operational workloads, and patient demand patterns.  
This project builds a **comprehensive hospital analytics dashboard** that enables hospital management to monitor performance across **financial, operational, and patient demographic dimensions**.

The dashboard provides a **centralized view of hospital performance** to help administrators identify revenue drivers, monitor operational efficiency, and improve resource allocation.

---

## Dashboard Preview

Below is a quick preview of the interactive Power BI dashboards.

![Dashboard Preview](https://github.com/the-abhradeep-banerjee/Healthcare-Management-Analytics-Dashboard/blob/main/Healthcare%20Dashboard.gif)

## Business Problem

Hospital administrators often struggle with fragmented healthcare data across multiple systems, making it difficult to answer critical management questions such as:

- Which hospital services generate the highest revenue?
- How dependent is the hospital on insurance vs out-of-pocket payments?
- What service lines generate the highest profit margins?
- How efficient is hospital capacity utilization?
- What patient demographics drive the highest service demand?

Without centralized analytics, decision-making becomes reactive rather than strategic.

---

## Goal of the Dashboard

The goal of this project is to build a **data-driven hospital performance monitoring system** that enables stakeholders to:

- Track financial performance and revenue growth
- Identify high-profit service lines
- Monitor patient flow and hospital workload
- Analyze insurance vs patient payment contribution
- Support operational planning and healthcare strategy

---

## Data Source

Dataset obtained from:

**Maven Analytics – Healthcare Dataset**

The dataset simulates real hospital operations and contains multiple related tables.

### Data Tables

| Table | Description |
|------|-------------|
| Patients | Patient demographic information |
| Encounters | Hospital visit details including admission type and cost |
| Payers | Insurance providers |
| Procedures | Medical procedures associated with encounters |
| Organizations | Healthcare providers |

The **Encounters table serves as the primary fact table** linking patient activity, financial transactions, and service utilization.

---

## Data Model

The report follows a **star schema data model** designed to efficiently analyze hospital performance across financial and operational dimensions.

### Data Model Diagram:

![Data Model](https://github.com/the-abhradeep-banerjee/Healthcare-Management-Analytics-Dashboard/blob/main/Screenshots/Data_Model_Diagram.png)

### Fact Table:
- Encounters

### Dimension Tables:
- Patients
- Payers
- Procedures

---

## Tech Stack

- **Power BI Desktop**
- **Power Query**
- **DAX (Data Analysis Expressions)**
- **Data Modeling**
- **Interactive Dashboard Design**

---

## Dashboard Features

This project consists of **three analytical dashboards**.

---

## 1️. Hospital Management Overview

### Purpose
Provides an **executive-level summary of hospital performance**.

### Key Metrics

- Total Patients
- Total Visits
- Total Revenue
- Net Revenue
- Insurance Coverage %
- Average Length of Stay
- Mortality Rate

### Key Visuals

- Revenue Trends (Total vs Net Revenue)
- Insurance Payment by Payer
- Revenue by Visit Type
- Patient Age Distribution
- Revenue Margin Breakdown

### Preview

![Dashboard](https://github.com/the-abhradeep-banerjee/Hospital-Management-Dashboard/blob/main/Screenshots/01_Healthcare_Performance_Executive_Overview.png)

---

## 2️. Financial Performance Dashboard

### Purpose
Analyzes hospital **financial sustainability and profitability**.

### Key Metrics

- Revenue Growth %
- Net Revenue Growth %
- Net Revenue Margin %
- Insurance YoY %
- Out-of-Pocket Expense
- Average Revenue per Patient

### Key Visuals

- Revenue Distribution by Payer (Treemap)
- Revenue vs Margin by Service Line (Scatter Plot)
- Insurance vs Patient Payment Breakdown
- Service Line Profitability Scorecard
- Net Revenue Margin Comparison

### Preview

![Dashboard](https://github.com/the-abhradeep-banerjee/Hospital-Management-Dashboard/blob/main/Screenshots/04_Hospital_Financial_Performance_Profitability_Dashboard.png)

---

## 3️. Operational Efficiency Dashboard

### Purpose
Evaluates hospital **patient flow, capacity utilization, and service demand**.

### Key Metrics

- Average Daily Visits
- Emergency Department Visit %
- Inpatient Admission Rate
- Bed Days
- Average Length of Stay

### Key Visuals

- Monthly Visit Trend
- Patient Flow Distribution
- Service Line Workload Analysis
- Admission Conversion Funnel
- Bed Utilization Gauge

### Preview

![Dashboard](https://github.com/the-abhradeep-banerjee/Hospital-Management-Dashboard/blob/main/Screenshots/05_Healthcare_Operational_Efficiency_Patient_Flow_Dashboard.png)

---

## Dashboard Walkthrough

Watch the full walkthrough of the interactive dashboards including navigation, slicers, and insights.

[Watch the Dashboard Walkthrough](https://github.com/the-abhradeep-banerjee/Healthcare-Management-Analytics-Dashboard/blob/main/Demo%20Video/Hospital_Management_Analytics_Dashboard_Demo.mp4)

---

## Business Impact & Insights

Key insights derived from the analysis include:

- **Self-pay patients represent the largest revenue contributor**, highlighting dependence on patient-funded payments.
- **Ambulatory and urgent care services generate the majority of hospital revenue**, reflecting an outpatient-driven care model.
- **Older patient groups (81–100 years)** contribute significantly to hospital visits, indicating rising demand from aging populations.
- **Urgent care and outpatient services demonstrate the highest profit margins**, making them strategically important service lines.
- **Operational metrics reveal stable emergency demand and efficient bed turnover**.

These insights help hospital leadership improve **financial planning, service prioritization, and operational efficiency**.

---

## Analytical Techniques Used

This project demonstrates several **advanced business intelligence techniques**:

- Data Modeling (Star Schema)
- KPI Performance Monitoring
- Financial Trend Analysis
- Service Line Profitability Analysis
- Patient Flow & Operational Analytics
- Interactive Drill-Down Analysis
- Conditional Formatting & Scorecards

---

## Repository Structure

Healthcare-Management-Analytics-Dashboard
│
├── Hospital Management.pbix
├── Healthcare Dashboard.gif
├── README.md
│
├── Screenshots
│   ├── 01_Healthcare_Performance_Executive_Overview.png
│   ├── 02_Healthcare_Performance_Yearly_Analysis_Dashboard.png
│   ├── 03_Service_Line_Performance_Analysis_Ambulatory.png
│   ├── 04_Hospital_Financial_Performance_Profitability_Dashboard.png
│   ├── 05_Healthcare_Operational_Efficiency_Patient_Flow_Dashboard.png
│   ├── 06_Operational_Efficiency_Yearly_Patient_Flow_Analysis.png
│   └── Data_Model_Diagram.png
│
├── Demo Video
│   └── Hospital_Management_Analytics_Dashboard_Demo.mp4
