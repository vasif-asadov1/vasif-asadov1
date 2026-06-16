<div align="center">

# Vasif Asadov

**Data Analyst · Data Engineer · AI-Augmented Developer**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vasif-asadov1/)
[![Portfolio](https://img.shields.io/badge/Website-111827?style=flat-square&logo=githubpages&logoColor=white)](https://vasif-asadov1.github.io/)
[![Microsoft PL‑300](https://img.shields.io/badge/Microsoft_PL--300-Power_BI_Data_Analyst_Associate-F2C811?style=flat-square&logo=powerbi&logoColor=black)](https://learn.microsoft.com/en-us/certifications/power-bi-data-analyst-associate/)

</div>

---

## About Me

I'm a data professional and M.Sc. candidate at Yıldız Technical University (Istanbul), building end-to-end data pipelines and ML solutions while completing a thesis on **AI-Based Model Predictive Control of Nonlinear Systems**.

My background spans two scholarships — a **Presidential Scholarship from Azerbaijan** (ranked 1st nationally with a perfect 700/700 entrance score) and a **fully funded Turkish Government Scholarship** — giving me a strong academic foundation that I apply directly to real-world data problems.

I work across the full data stack: from raw ingestion and transformation to dashboards, predictive models, and deployed applications. I hold a **Microsoft PL-300 Power BI Data Analyst Associate** certification (valid through 2027) and have hands-on internship experience at **SOCAR R&D Institute** and **Data Science Academy**.

Beyond data, I use AI as a force multiplier for software development — I lead product vision and architecture, while AI handles lower-level implementation details. This lets me ship polished, full-featured desktop and web applications that would otherwise take months.

---

## Tech Stack

**Languages**
`Python` · `SQL (T-SQL, DuckDB)` · `R`

**BI & Visualization**
`Power BI` · `Tableau` · `Plotly Dash` · `Matplotlib` · `Seaborn` · `Apache Superset` · `Excel` · `SPSS`

**Data Engineering**
`Snowflake` · `dbt` · `AWS S3` · `AWS IAM` · `DuckDB` · `Docker` · `GitHub Actions (CI/CD)`

**Machine Learning**
`Scikit-learn` · `XGBoost` · `LightGBM` · `SHAP` · `Pandas` · `Streamlit`

**Documentation & Web**
`LaTeX` · `Typst` · `Quarto` · `Markdown` · `Astro` · `Tailwind CSS`

**Desktop Development**
`PyQt6` · `PySide6` · `PyInstaller`

---

## Featured Projects

### 🏗️ E-commerce Cloud Analytics Pipeline
> *AWS S3 · Snowflake · dbt · Databricks · MLflow · Power BI*

End-to-end cloud data pipeline built on the **Olist e-commerce dataset**, structured around a full **medallion architecture** (Bronze → Silver → Gold). Raw data is ingested from Kaggle into an S3 data lake, cleaned and transformed via dbt into a Snowflake warehouse, then surfaced to a Power BI executive dashboard. The ML layer (Databricks + MLflow) solves a multi-class classification problem — predicting customer review scores — with SHAP analysis for feature interpretability and A/B testing for statistical validation.

`AWS S3` `IAM` `Snowflake` `dbt` `Databricks` `MLflow` `Power BI` `SHAP` `Spark ML`

---

### 🏦 Home Credit Default Risk Analysis & Prediction
> *Python · DuckDB · XGBoost · LightGBM · SHAP*

Credit risk modeling on a **307,511-customer dataset** spanning 7+ relational tables (20M+ rows). The project involves deep multi-table EDA with 50+ structured business questions, extensive feature engineering (146 final features engineered from 250+ raw columns), and WoE encoding to handle high-cardinality categoricals. Final models: **LightGBM achieved 0.79 ROC-AUC and 0.696 Recall**. DuckDB was used throughout for fast out-of-core SQL processing.

`DuckDB` `XGBoost` `LightGBM` `Scikit-learn` `SHAP` `WoE Encoding` `Stratified K-Fold CV`

---

### 📉 Customer Churn Prediction — Telecom
> *Python · Scikit-learn · XGBoost · LightGBM · Streamlit*

End-to-end ML pipeline predicting telecom customer churn. Includes Chi-Square and ANOVA-based feature selection, 9-model comparison baseline, hyperparameter tuning via RandomizedSearchCV, and imbalance handling (SMOTE + undersampling). Deployed as an interactive **Streamlit web app** using sklearn Pipelines and ColumnTransformer. SHAP analysis on both Logistic Regression and XGBoost reveals that **tenure, contract type, and monthly charges** are the dominant churn drivers.

`Scikit-learn` `XGBoost` `LightGBM` `SHAP` `SMOTE` `Streamlit` `Pipelines`

---

### 📊 B2C Sales Analysis — AdventureWorks DW
> *SQL Server · T-SQL · Tableau · Docker*

Full analytical workflow on the AdventureWorksDW2022 dataset, scoped exclusively to B2C sales. Stood up SQL Server in a Docker container on Linux, restructured the schema into an 11-table star schema, and answered 23 business questions spanning executive KPIs, customer segmentation, product profitability, geographic distribution, and SLA adherence. Published an executive **Tableau dashboard** with a dynamic KPI parameter allowing stakeholders to toggle between Revenue, Cost, Profit, and Order Count across all visuals.

`SQL Server` `T-SQL` `Docker` `Tableau` `Star Schema` `Data Modeling`

---

### 📦 pysqdb — PyPI Package
> *Python · DuckDB · GitHub Actions*

Open-source Python library published on **PyPI** (`pip install pysqdb`) that wraps DuckDB with a Pandas-like declarative API. Provides zero-copy views, SQL-native imputation, outlier handling, multi-table joins via Python dicts, window functions, and aggregation pipelines — all designed for large datasets that exceed RAM. CI/CD via **GitHub Actions** automates testing and publishing on every release.

[![PyPI](https://img.shields.io/pypi/v/pysqdb?style=flat-square&logo=pypi&logoColor=white)](https://pypi.org/project/pysqdb/)
[![GitHub](https://img.shields.io/badge/Source-GitHub-181717?style=flat-square&logo=github)](https://github.com/vasif-asadov1/pysqdb)

`DuckDB` `Python` `PyPI` `GitHub Actions` `CI/CD`

---

### 🗣️ Language Learner — Desktop App *(AI-Augmented)*
> *Python · PyQt6 · SQLite · PyInstaller*

Cross-platform desktop translation and vocabulary app with **zero ads, zero subscriptions, and no usage limits**. Features include real-time translation across 11 target languages, automated PDF note generation (1-column and 2-column layouts), SQLite session storage, smart German article detection (der/die/das), contextual synonyms, and phonetic transliteration for Russian, Arabic, and Persian scripts. Ships as a standalone binary for both Windows and Linux via PyInstaller.

[![Releases](https://img.shields.io/github/v/release/vasif-asadov1/language-learner?style=flat-square&logo=github)](https://github.com/vasif-asadov1/language-learner/releases)

`PyQt6` `SQLite` `ReportLab` `PyInstaller` `Cross-platform`

---

### 🌙 AyahFinder Royal Edition — Desktop App *(AI-Augmented)*
> *Python · PySide6 · QTextDocument · GitHub Actions*

Offline Quran verse search and PDF export application with a premium royal-themed UI (deep navy/magenta/rose-gold palette). Supports **8 translation languages**, smart search by name or ID, auto-scroll TOC sidebar, dynamic Arabic typography (3 script choices), and high-fidelity PDF export with linear gradient backgrounds. Cross-platform builds (Windows `.exe` + Linux binary) automated via GitHub Actions CI/CD.

[![Releases](https://img.shields.io/github/v/release/vasif-asadov1/AyahFinder?style=flat-square&logo=github)](https://github.com/vasif-asadov1/AyahFinder/releases)

`PySide6` `QTextDocument` `QPrinter` `PyInstaller` `GitHub Actions`

---

## Education

| Degree | Institution | Period | Scholarship |
|---|---|---|---|
| M.Sc. Control & Automation Engineering | Yıldız Technical University, Istanbul | 2024 – Present | 🇹🇷 Fully Funded Turkish Government Scholarship |
| B.Sc. Process & Automation Engineering | Baku Higher Oil School, Azerbaijan | 2018 – 2023 | 🇦🇿 Azerbaijan Presidential Scholarship · GPA 3.5/4.0 |

**M.Sc. Thesis:** *AI-Based Model Predictive Control of Nonlinear Systems*
**Relevant coursework:** Machine Learning & Neural Networks · Computer Vision in Control Systems · Reinforcement Learning

---

## Experience

**Data Scientist Intern** — *Data Science Academy* · Remote · Aug 2025 – Feb 2026
- Built Power BI and Tableau dashboards for KPI monitoring and stakeholder reporting
- Automated SQL + Python pipelines for data processing and reporting workflows
- Conducted A/B testing and statistical analysis across product and marketing datasets
- Completed comprehensive EDA and predictive modeling across multiple business domains

**Data Management Intern** — *SOCAR R&D Institute of Oil and Gas* · Baku · Mar – May 2023
- Managed and optimized industrial sensor data in Microsoft SQL Server
- Developed automated SQL triggers for threshold-based anomaly alerting
- Created documentation for data management processes to ensure operational continuity

---

## Certifications

- 🏆 **Microsoft PL-300** — Power BI Data Analyst Associate *(valid through 2027)*
- 📜 **Full Stack Data Scientist Certificate** — Data Science Academy
- 📊 **CDS-ES Talent Score: 93.70 / 100** — Data Science Academy · [View Report](./vasif_asadov_talent_report.pdf)
- 📜 **Advanced SQL Certificate** — BTK Akademi


---

<div align="center">

*I document everything I build. Check my [personal website](https://vasif-asadov1.github.io/) for blog posts, project walkthroughs, and data science content.*

</div>
