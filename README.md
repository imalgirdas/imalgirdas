<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:217346,100:F2C811&height=180&section=header&text=Algirdas%20Vailionis&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Data%20Scientist%20in%20the%20Making&descAlignY=55" />
</p>

<p align="center">
  <a href="https://github.com/imalgirdas">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=217346&center=true&vCenter=true&width=600&lines=SQL+%7C+Python+%7C+R+%7C+Power+BI+%7C+Excel;From+payroll+and+accounting+to+data+science;Turning+data+into+decisions;Open+to+work" alt="Typing SVG" />
  </a>
</p>

## 👨‍💼 About Me

I'm a finance and payroll professional from Kaunas, Lithuania, in the middle of a career move into data analytics and data science. I have a Master's in Accounting and Audit and a Bachelor's in Economics and Finance, and I've spent several years working with numbers at Deloitte Lithuania, NKT and Nordgain. Over time I realised that the part of the job I enjoyed most wasn't closing the books. It was digging into the data behind them.

At Deloitte I handled payroll for many clients, and at NKT I worked as a Senior Accounts Receivable Accountant. Both jobs taught me how much a business depends on accurate, well-structured data. Every month meant reconciling large datasets, chasing down mismatches, and checking that every figure followed Lithuanian tax and labour rules (GPM, NPD, Sodra, VDU). That's where I built the habits that matter most in analytics: attention to detail, a healthy distrust of messy data, and a need to understand why a number is what it is.

Now I'm turning that experience into technical skills. I write **SQL** for data cleaning, exploratory analysis and business KPIs, including window functions, CTEs, stored procedures, triggers and events. In **Python** I work with pandas, NumPy and Matplotlib, and I'm learning Streamlit to build interactive data apps. I use **R** for data cleaning pipelines and R Markdown reporting, and I build dashboards in **Power BI** (DAX, Power Query) and **Excel**.

What sets me apart is that I understand both sides: the data and the business it describes. I know what a finance team needs from a report, which numbers management actually looks at, and how small data errors turn into real financial problems. My goal is to be an analyst who doesn't just produce charts but helps people make better decisions with clean, trustworthy data.

This GitHub is my learning journal and portfolio. Each project below takes a real-world dataset from raw to insight: cleaning, analysis, visualisation and clear conclusions. I'm currently going deeper into data science with Python and R, and I'm **open to data analyst / data scientist opportunities**. Feel free to reach out on LinkedIn or by email!

<p>
  <a href="https://www.linkedin.com/in/algirdas-vailionis"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:algirdas.vailionis@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>
---
 
## 🛠️ Tools & Skills

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" width="55" title="SQL / MySQL" />&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="55" title="Python" />&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" width="55" title="pandas" />&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" width="55" title="NumPy" />&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/matplotlib/matplotlib-original.svg" width="55" title="Matplotlib" />&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg" width="55" title="Jupyter" />
</p>
<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/r/r-original.svg" width="55" title="R" />&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rstudio/rstudio-original.svg" width="55" title="RStudio" />&nbsp;&nbsp;
  <img src="https://img.icons8.com/color/96/microsoft-excel-2019--v1.png" width="55" title="Excel" />&nbsp;&nbsp;
  <img src="https://img.icons8.com/color/96/power-bi.png" width="55" title="Power BI" />&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="55" title="Git" />&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="55" title="GitHub" />
</p>
---
 
## 📂 Projects

### 🛒 Amazon Sales Performance Analysis (2021–2025)
 
<a href="https://github.com/imalgirdas/amazon-sales-pipeline">
  <img src="https://raw.githubusercontent.com/imalgirdas/amazon-sales-pipeline/main/images/dashboard_sales_overview.png" alt="Amazon Sales Performance Dashboard" width="100%">
</a>
End-to-end sales analysis of an Amazon-style marketplace covering five years of trading. I built a full analytics pipeline across 16 related tables and ~680k rows, from data loading and cleaning through KPI modelling to a 5-page executive dashboard. The analysis tracks revenue growth from **$3.0M to $5.4M**, category mix shifts, customer retention, marketing ROI and delivery performance, and closes with data-driven business recommendations.
 
**Focus areas:** Sales KPIs · Customer Retention · Marketing ROI · Fulfilment & Returns
 
[![View Repository](https://img.shields.io/badge/View%20Repository-FF9900?style=for-the-badge&logo=github&logoColor=white)](https://github.com/imalgirdas/amazon-sales-pipeline)
---

### 🏠 Airbnb Rentals Analysis (2022–2025)

<a href="https://github.com/imalgirdas/Airbnb_Rentals_Analysis">
  <img src="https://raw.githubusercontent.com/imalgirdas/Airbnb_Rentals_Analysis/main/Dashboard/ex01.png" alt="Airbnb Rentals Dashboard" width="100%">
</a>

Data cleaning pipeline and analysis for a short-term rental marketplace in London, Paris, Barcelona and Amsterdam. The source data (9 related tables, ~300k rows) came in dirty: mixed date formats, prices with the wrong currency sign or 100x too big, swapped coordinates, duplicate guests, totals that didn't add up and orphan references. I built a MySQL pipeline that loads everything as raw text, parses and validates every value, repairs what the data itself can prove, and routes the rest to a manual review queue instead of guessing. Only rows that pass every check reach the clean database, which went from **278K to 291K** clean rows after review. On top of it sits the analysis of **€48.65M** in revenue and a 4-page Looker Studio dashboard.

```mermaid
flowchart LR
    A[Raw CSVs] --> B[(airbnb_raw<br/>all text)]
    B --> C[Parse & validate<br/>dates, money, ids, rules]
    C -->|passes| D[(airbnb_clean<br/>typed + constraints)]
    C -->|can't fix safely| E[manual_* queue<br/>+ issue log]
    E --> F[Evidence-based fixes<br/>e.g. total must add up]
    F -->|re-run| C
    D --> G[Analytics SQL]
    D --> H[Report views → CSV]
    H --> I[Looker Studio dashboard]
```

**Focus areas:** Data Cleaning & Validation · Revenue & Occupancy · Host Performance · Pricing & Reviews

[![View Repository](https://img.shields.io/badge/View%20Repository-FF5A5F?style=for-the-badge&logo=github&logoColor=white)](https://github.com/imalgirdas/Airbnb_Rentals_Analysis)
---

 




---
 


<img src="https://capsule-render.vercel.app/api?type=waving&color=0:F2C811,100:217346&height=100&section=footer" width="100%" />
