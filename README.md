# Manufacturing Downtime Analysis & Forecasting

## DEPI Final Project — Team 3

Team 3
Supervisor: Eng. Mahmoud Emad

## Project Overview

- Manufacturing downtime directly affects production efficiency, operational costs, and production planning.

- This project aims to analyze manufacturing line productivity, identify the major causes of downtime, evaluate production performance, and develop forecasting models to support data-driven operational decisions.

Using SQL, Python, Machine Learning, and Tableau, the team will transform raw manufacturing data into actionable insights and develop a data-driven approach to estimating next-day downtime and planning production batches.

## Business Objectives

- Identify and quantify the major causes of manufacturing downtime.
- Evaluate production efficiency across products, batches, operators, and operating days.
- Compare actual production duration against minimum required batch time.
- Investigate operational patterns associated with increased downtime.
- Forecast downtime for the next operating day.
- Estimate the number of batches that can be produced based on available operating time and predicted downtime.
- Develop an interactive Tableau dashboard to support operational decision-making.

## Dataset Overview

The project dataset contains four tables describing manufacturing productivity, product characteristics, downtime events, and downtime factors.

### Dataset| Description
Line Productivity| Batch production dates, products, operators, start times, and end times
Products| Product flavors, package sizes, and minimum batch production times
Line Downtime| Downtime duration by batch and downtime factor
Downtime Factors| Downtime descriptions and operator-error classifications

The project also includes a data dictionary describing the available tables and fields.

# Project Workflow

### Week 1 — Data Modeling, Cleaning & Preprocessing

- Inspect dataset structure, data types, missing values, and duplicate records.
- Validate batch identifiers, production timestamps, and downtime values.
- Reshape downtime data into an analysis-ready structure.
- Define relationships between production, product, and downtime tables.
- Prepare clean datasets for analysis.

### Tools: SQL, Python, Pandas, Matplotlib

## Deliverables:

- Cleaned datasets.
- Data preprocessing notebook.
- Documented data model.

Week 2 — Exploratory Data Analysis & Business Questions

- Analyze production performance and downtime distribution.
- Identify the most significant downtime factors.
- Compare downtime across products, operators, and dates.
- Calculate production efficiency metrics.
- Translate analytical findings into actionable business recommendations.

### Tools: SQL, Python, Pandas, Matplotlib

## Deliverables:

- Business analysis questions.
- Analytical results and visualizations.
- Key findings and recommendations.

Week 3 — Downtime Forecasting & Production Planning

- Analyze historical downtime patterns and production trends.
- Develop and evaluate suitable forecasting approaches.
- Estimate downtime for the next operating day.
- Estimate feasible production batch counts using predicted downtime and product-specific production times.
- Evaluate model performance and document forecasting limitations.

### Tools: Python, Pandas, Scikit-learn, Matplotlib

## Deliverables:

- Forecasting models and evaluation results.
- Forecast visualization plots.
- Next-day downtime estimates.
- Production planning estimates.

Week 4 — Tableau Dashboard & Final Presentation

- Develop an interactive Tableau dashboard.
- Present production performance and downtime KPIs.
- Visualize major downtime factors and operational trends.
- Communicate forecasting results and production planning recommendations.
- Prepare the final report and presentation.

### Tools: SQL, Python, Tableau

## Deliverables:

- Interactive Tableau dashboard.
- Final project report.
- Final presentation.

## Technology Stack

- SQL: Data querying, transformation, and analytical calculations.
- Python: Data preprocessing, exploratory data analysis, and forecasting.
- Pandas: Data manipulation and preparation.
- Matplotlib: Data visualization.
- Scikit-learn: Machine learning model development and evaluation.
- Tableau: Interactive dashboards and business reporting.
- Git & GitHub: Version control and project documentation.

# Expected Business Outcomes

### The project aims to provide evidence-based recommendations for:

- Prioritizing the downtime causes with the greatest operational impact.
- Improving production efficiency and reducing avoidable downtime.
- Identifying differences in production performance across products and operating periods.
- Supporting next-day production planning through downtime forecasting.
- Improving the visibility of manufacturing performance through interactive reporting.

All findings and recommendations will be based on the available dataset and validated analytical results.

# Team Members

Ahmed Bayoumy





# Repository Structure

Manufacturing-Downtime-Analysis-Forecasting/
│
├── data/
│   ├── raw/
│   │   ├── Manufacturing_Line_Productivity.xlsx
│   │   └── data_dictionary.csv
│   └── processed/
│
├── notebooks/
│   ├── 01_Data_Preprocessing.ipynb
│   ├── 02_Exploratory_Data_Analysis.ipynb
│   └── 03_Downtime_Forecasting.ipynb
│
├── sql/
│   └── manufacturing_analysis.sql
│
├── dashboard/
│
├── reports/
│
├── README.md
└── .gitignore

The structure above represents the planned organization of the project. Files and folders will be populated as the project progresses.

## Project Status

### Status: In Progress

This project is being developed as part of the DEPI Professional Data Analyst track.

Further updates will include the data model, preprocessing workflow, business analysis, forecasting results, and Tableau dashboard.

## Acknowledgments

Thanks to the Digital Egypt Pioneers Initiative (DEPI) and our project supervisor, Eng. Mahmoud Emad, for supporting the project as part of the data analytics learning journey.
