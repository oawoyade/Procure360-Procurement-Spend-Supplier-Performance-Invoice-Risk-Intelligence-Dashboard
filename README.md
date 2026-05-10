# Procure360: Procurement Spend, Supplier Performance & Invoice Risk Intelligence Dashboard
---

# Project Links

## GitHub
[Insert GitHub Repository Link Here]

---

# Skills

- Data Intelligence
- Procurement Analytics
- Data Analysis
- Data Modelling
- DAX
- Power BI
- Data Visualisation
- Business Intelligence
- KPI Engineering
- HTML & CSS in Power BI
- Procurement Risk Analytics
- Supplier Performance Analysis

---

# About This Project

The **Procure360: Procurement Spend, Supplier Performance & Invoice Risk Intelligence Dashboard** was developed as a comprehensive procurement analytics and business intelligence solution designed to transform fragmented procurement, supplier and invoice data into meaningful, actionable insights for operational and strategic decision-making.

In many organisations, procurement and accounts payable data are often dispersed across multiple systems, making it difficult for procurement leaders, finance teams and operational stakeholders to monitor spend behaviour, supplier performance, invoice quality and compliance exposure in a single environment.

This project addresses that challenge by building an integrated analytical platform that provides a unified view of procurement operations using **Power BI, DAX, advanced HTML custom visuals and a robust star-schema modelling approach.**

The dashboard delivers a holistic overview of procurement performance by consolidating supplier transactions, invoice activities, budget data and operational KPIs into a single interactive reporting environment.

It enables users to:

- Analyse supplier spend across categories, departments, contract types and regions
- Monitor invoice governance and approval quality
- Evaluate procurement compliance exposure
- Track operational efficiency and supplier performance
- Support strategic procurement decision-making

Key metrics developed include:

- Total Spend
- Budget Variance %
- Savings %
- Maverick Spend %
- Overdue Invoice Count
- Disputed Invoice Count
- No Match %
- Average Lead Time
- On-Time Delivery Rate
- Supplier ESG Classification
- Approval Governance Metrics

---

# Data Modelling Approach

The analytical solution was built using a **star schema model** to ensure scalability, analytical flexibility and high performance.

## Fact Table

### Fact_Procurement
The central transactional table capturing:

- Supplier spend
- Budget values
- Invoice status
- Delivery performance
- Contract information
- Savings metrics
- Procurement compliance indicators

---

## Dimension Tables

### Dim_Supplier
- Supplier details
- ESG scores
- Payment terms
- Geographic attributes

### Dim_Department
- Department hierarchy
- Cost centre classifications

### Dim_Item
- Procurement categories
- Subcategories
- Item descriptions

### Dim_Contract
- Contract type analysis
- Contract lifecycle attributes

### Dim_Requestor
- Procurement requestor tracking

### Dim_Approver
- Approval governance analysis

### Dim_Date
- Fiscal calendar
- Time intelligence analysis

---

# Data Preparation & Transformation

Data preparation involved:

- Cleaning null and inconsistent procurement records
- Standardising invoice and contract status categories
- Creating Delivery Variance Buckets
- Creating Lead Time Buckets
- Engineering Supplier ESG Bands
- Building procurement governance KPIs
- Developing invoice quality metrics

---

# Advanced DAX Measures

The solution includes advanced DAX calculations such as:

```DAX
Total Spend
Budget Variance %
Savings %
Maverick Spend %
Overdue Invoice Count
Disputed Invoice Count
No Match %
Average Lead Time
On-Time Delivery Rate
Supplier ESG Band
Approval Governance Metrics
```

These calculations enable dynamic and context-aware procurement analysis across all business dimensions.

---

# Dashboard Pages

## 1. Spend Intelligence & Supplier Performance Dashboard

### Key Focus Areas

- Procurement spend analysis
- Budget monitoring
- Supplier spend performance
- Category analysis
- Department spend analysis
- Contract type analysis

### Key Insights

- IT Software and Professional Services are major cost drivers
- Supplier activity is concentrated across the UK, Netherlands and Australia
- Elevated maverick spend indicates procurement compliance exposure
- Framework and long-term contracts drive procurement stability

---

## 2. Invoice Performance & Risk Dashboard

### Key Focus Areas

- Overdue invoice monitoring
- Disputed invoice analysis
- No-match invoice tracking
- Approval governance analysis
- Invoice quality monitoring
- Procurement lead time analysis

### Key Insights

- Overdue invoices represent operational payment risk
- Invoice disputes highlight reconciliation challenges
- No-match invoices indicate procurement control weaknesses
- Lead time variability impacts procurement efficiency

---

## 3. Supplier Spend & Budget Matrix

### Key Focus Areas

- Supplier governance
- Budget variance analysis
- Multi-currency spend analysis
- ESG supplier performance
- Supplier tier monitoring

### Key Insights

- Preferred suppliers demonstrate stronger budget alignment
- Supplier ESG performance varies significantly
- Certain suppliers show elevated budget variance exposure

---

## 4. Department & Contract Performance Matrix

### Key Focus Areas

- Department procurement efficiency
- Contract compliance monitoring
- Savings performance analysis
- Delivery performance tracking
- Procurement compliance KPIs

### Key Insights

- Framework contracts demonstrate stronger procurement efficiency
- Departments with higher maverick spend show weaker compliance
- Procurement savings performance varies across business units

---

# Key Business Insights

Several important operational insights emerged from the analysis:

- Technology and professional services drive procurement expenditure
- Elevated maverick spend reveals procurement governance opportunities
- Invoice quality significantly impacts operational performance
- Framework contracts improve procurement efficiency
- Supplier ESG monitoring enhances supplier risk visibility
- Procurement lead times influence operational delivery effectiveness

---

# HTML Custom Visual Development

One of the unique aspects of this project was the use of **HTML and CSS within Power BI** to create custom-designed executive visuals including:

- KPI cards
- Approval governance matrices
- Supplier performance tables
- Invoice quality scorecards
- Multi-currency procurement matrices
- Procurement risk composition cards

This significantly enhanced the dashboard’s executive presentation and storytelling capability.

---

# Tools & Technologies

| Tool | Purpose |
|------|----------|
| Power BI | Dashboard design & analytics |
| DAX | KPI calculations |
| Power Query | Data transformation |
| HTML & CSS | Custom visual development |
| Star Schema Modelling | Data optimisation |
| Business Intelligence Design | Executive storytelling |

---

# Business Value

This solution enables:

- Procurement leaders to monitor supplier performance
- Finance teams to identify invoice risk exposure
- Operational stakeholders to evaluate procurement efficiency
- Decision-makers to optimise procurement governance
- Organisations to improve financial control and supplier management

---

# Conclusion

The **Procure360: Procurement Spend, Supplier Performance & Invoice Risk Intelligence Dashboard** demonstrates how advanced business intelligence, procurement analytics and visual storytelling can transform procurement data into a powerful operational decision-making platform.

By integrating procurement spend analysis, supplier governance, invoice quality monitoring and operational performance metrics into a single analytical environment, the solution provides a comprehensive view of procurement operations and financial control.

This project highlights the value of data-driven procurement intelligence, enabling organisations to make informed strategic decisions, optimise supplier performance and strengthen procurement governance through advanced analytics.
