# Rohan Patil

**Data Analyst | Python, SQL, Power BI | Business and Risk Analytics**

Final-year student (expected graduation 2026-27, Shivaji University, Kolhapur) with hands-on experience in data cleaning, SQL analysis and dashboard development. I turn raw data into clear findings and practical business recommendations.

[Email](mailto:rohanrajendrapatil2005@gmail.com) | [LinkedIn](https://www.linkedin.com/in/rohan-patil-653a67307/)

---

## About Me

I am an aspiring Data Analyst with a growing focus on finance and risk analytics. My projects cover the full analytics cycle: cleaning and transforming data with Python (Pandas), querying it with SQL, performing exploratory analysis, and presenting results in Power BI dashboards.

I have completed job simulations in banking and finance (Citi, Goldman Sachs) and in data visualization (Tata), along with coursework in risk management and principles of finance.

I am open to Data Analyst, Business Analyst, and Financial or Risk Analyst internships and entry-level roles.

---

## Skills

| Category | Skills |
|---|---|
| Programming and Data Analysis | Python, SQL, Pandas, NumPy |
| BI and Visualization | Power BI, DAX, Power Query, Excel, Matplotlib, Seaborn, Dashboard Development |
| Data Analysis | Data Cleaning, Data Transformation, Exploratory Data Analysis (EDA), Data Visualization, KPI Analysis, Business Insights, Feature Engineering, Reporting |
| Databases | MySQL, SQL Joins, Filtering, Aggregation, Grouping, Analytical Queries, Data Import |
| Tools | Jupyter Notebook, Git, GitHub |
| Soft Skills | Analytical Thinking, Problem Solving, Communication, Team Collaboration, Adaptability, Time Management |

---

## Projects

### 1. Business Performance Diagnosis

**Tools:** Python, Pandas, Matplotlib, Seaborn, Power BI
**Dataset:** Sample Superstore (Kaggle), 9,994 rows and 21 columns, 2014 to 2017

**Problem statement:** Identify which products, regions and discount levels drive or drain profit in a retail business, and present the results in an interactive dashboard.

**Approach**
- Loaded, profiled and cleaned the data: checked missing values, removed duplicates and converted order and shipping dates to datetime.
- Performed exploratory analysis across overall performance, yearly trends, category and sub-category performance, regional performance and discount impact.
- Built an interactive Power BI dashboard with KPI cards for profit, sales and discount, category and city-level views, and a yearly sales trend.

**Key findings**
- The business generated **2.30M in sales and 286K in profit**.
- **Technology** is the strongest category and Copiers is the most profitable sub-category. Furniture earns the least profit despite contributing about 32% of sales.
- Sales grew from **470.53K in 2015 to 733.22K in 2017**, an increase of roughly 56%, with the strongest growth in 2016 and 2017.
- **New York City** is the most profitable city, well ahead of Los Angeles and Seattle.
- The West region is the strongest market and the Central region the weakest.
- Transactions with **0% discount** produced the highest profit, while **70% discounts** frequently resulted in losses.

**Recommendation:** Scale Technology and the West region, review pricing and costs in Furniture and the Central region, and audit high-tier discounting.


[View Repository](https://github.com/rohanpatil120/Business_Performance_Diagnosis)


[View Dashboard](https://github.com/rohanpatil120/Portfolio_repository/blob/main/certificates/business_daignosis_dashboard.png)


---

### 2. Customer Behavior Analysis

**Tools:** Python (Pandas), SQL, Power BI, DAX

**Problem statement:** Convert raw customer purchase data into behavioral insights through a complete analytics pipeline, from cleaning to dashboard.

**Approach**
- **Python:** cleaned and transformed the raw dataset by handling missing values, removing duplicates, correcting data types and fixing inconsistent entries.
- **SQL:** loaded the cleaned data into a database, connected it to Python and wrote analytical queries using filtering, aggregation and grouping.
- **Power BI:** built an interactive dashboard with KPIs designed using DAX measures, and slicers for subscription status, gender, category and shipping type.

**Key findings**
- The dataset covers about **3.9K customers**, with an average purchase of **$59.76** and an average review rating of **3.75**.
- **Clothing** leads in both revenue and sales volume, followed by Accessories, Footwear and Outerwear.
- Only **27% of customers (1.05K)** hold a subscription, which points to room for growth in subscriber conversion.
- Revenue is spread fairly evenly across age groups, with young adults contributing the most (62K).
- Payment methods are split almost equally (16 to 17% each), so no single payment channel dominates.

[View Repository](https://github.com/rohanpatil120/customer_behavior_analysis)


[View Dashboard](https://github.com/rohanpatil120/Portfolio_repository/blob/main/certificates/customer_behaviour_dashboard.png)



---

### 3. Customer Churn Analysis and Intelligence Framework

**Tools:** Python, SQLite, Pandas, NumPy, Matplotlib, Seaborn

**Problem statement:** Identify which customer segments and behaviors lead to subscription churn, and where retention efforts should be focused.

**Approach**
- Built an automated pipeline that loads a raw multi-sheet Excel file into a relational SQLite database with three linked tables (customers, subscriptions and support tickets), joined on `customerid`.
- Cleaned and normalized categories, filled missing regional data through demographic mapping, engineered customer-tenure features and assigned Low, Medium and High risk levels.
- Used pivot tables, multi-column aggregation and correlation analysis, then visualized results with monthly trend charts, heatmaps and facet grids.
- Exported a combined master dataset ready for Power BI or Tableau.

**Key findings**
- Overall churn rate of **28.57%** (retention rate 71.43%).
- Churn depends strongly on plan type: **Basic 60.00%**, Standard 22.22% and Premium 14.29%.
- Support escalations show a strong positive correlation (**0.77**) with churn.
- Retained customers stay active for an average of about **1,452 days**.

**Recommendation:** Prioritize retention for Basic-plan customers through upgrade offers and onboarding, and improve escalation handling.

[View Repository](https://github.com/rohanpatil120/Customer_Churn_Rate_Analysis) 

---

### 4. Credit Default Risk Analysis

**Tools:** Python, Pandas, Matplotlib, Seaborn
**Dataset:** 255,347 loan records and 18 columns

**Problem statement:** Determine which borrower characteristics are associated with a higher risk of loan default.

**Approach**
- Cleaned and prepared the dataset for analysis.
- Calculated the overall default rate as a portfolio benchmark.
- Analyzed default rates by debt-to-income ratio (DTI), interest rate and employment type, individually and in combination, to identify lower-risk and higher-risk borrower profiles.

**Key findings**
- The overall portfolio default rate is **11.61%**, which provides a benchmark for comparing borrower groups.
- Multiple risk factors matter: DTI, interest rate and employment type together give a more useful view of borrower risk than examining each characteristic in isolation.
- **Relatively lower-risk profile:** low DTI, low interest rate and stable employment. These borrowers carry a lower financial burden, lower loan pricing and more stable employment conditions.
- **Relatively higher-risk profile:** high DTI, low interest rate and unstable employment. This combination indicates greater financial pressure alongside weaker employment stability.

**Business value:** Supports tighter approval criteria and risk-based pricing by borrower segment.

[View Repository](https://github.com/rohanpatil120/credit_default_risk_analysis)

---

##  Certifications

All certificates are verifiable through the links below or available as PDFs in the [`certificates`](certificates/) folder.

###  Finance and Risk

| Certificate | Issuer | Proof |
|---|---|---|
| **Risk Management** (Statement of Participation, 24 hours, CPD-accredited, Oct 2026) | The Open University (OpenLearn) | [View certificate](https://github.com/rohanpatil120/Portfolio_repository/blob/main/certificates/open_university_finance_course_certificate.pdf) |
| **Finance Course** | Saylor Academy | [View certificate](https://github.com/rohanpatil120/Portfolio_repository/blob/main/certificates/saloyr_finance_course_certificate.pdf) |

### Job Simulations (Forage)

| Simulation | Issuer | Proof |
|---|---|---|
| **Citi Bank Finance Job Simulation** | Forage | [View certificate](https://github.com/rohanpatil120/Portfolio_repository/blob/main/certificates/Citi_bank_finance_job_simulation.pdf) |
| **Goldman Sachs Finance Job Simulation** | Forage | [View certificate](https://github.com/rohanpatil120/Portfolio_repository/blob/main/certificates/Goldsmans_Sachs_finance_job_simulation.pdf) |
| **Tata Data Visualisation Job Simulation** | Forage |[View certificate](https://github.com/rohanpatil120/Portfolio_repository/blob/main/certificates/Tata_data_visulization_job_simulation.pdf) |

###  Data and Business Analytics (Coursera)

| Course | Issuer | Proof |
|---|---|---|
| **Databases and SQL** (IBM) | Coursera | [Verify](https://www.coursera.org/verify/6F5DODVLGQDW) |
| **Business Analysis and Process Management** | Coursera | [Verify](https://www.coursera.org/account/accomplishments/records/4YU8TFVLEX9S) |
| **Introduction to CRM** | Coursera | [Verify](https://www.coursera.org/account/accomplishments/records/S2IHQZ22R6YJ) |

**Statement of participation**
- Risk Management, OpenLearn (The Open University). Course RM_1, 24 hours of study, issued 9 October 2026. [View statement](https://github.com/rohanpatil120/Portfolio_repository/blob/main/certificates/RM_1_statement.pdf)

---

## Contact

- Email: [rohanrajendrapatil2005@gmail.com](mailto:rohanrajendrapatil2005@gmail.com)
- LinkedIn: [linkedin.com/in/rohan-patil-653a67307](https://www.linkedin.com/in/rohan-patil-653a67307/)
- GitHub: [github.com/rohanpatil120](https://github.com/rohanpatil120)
