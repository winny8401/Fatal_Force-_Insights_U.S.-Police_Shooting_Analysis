**Fatal Force Insights: U.S. Police Shooting Analysis**

An Excel-based data analysis project exploring demographic and incident patterns in 4,895 fatal police shooting records in the United States from 2015-01-02 to 2020-06-15.


**Project Overview**

This project analyzes fatal police shooting records using Microsoft Excel. The workbook contains the raw dataset, cleaned fields, pivot-table analysis, and an interactive dashboard focused on demographics, weapon categories, mental-health indicators, body-camera use, fleeing status, and threat level.

The goal is to demonstrate practical data-analysis skills such as data cleaning, categorization, pivot-table analysis, dashboard design, descriptive statistics, and communicating findings clearly.

**Key Questions**

Which demographic groups appear most often in the dataset?

What weapon categories are most common?

How many recorded cases involved an unarmed person?

How frequently were signs of mental illness recorded?

How often was body-camera use recorded?

What were the most common fleeing and threat-level classifications?

Which states recorded the highest number of incidents in this dataset?

What does the age distribution of victims look like?

**Descriptive Findings**

White victims account for 2,476 records (50.6%), Black victims for 1,298 (26.5%), and Hispanic victims for 902 (18.4%).

2,764 incidents (56.5%) are categorized under guns.

348 records (7.1%) are categorized as unarmed.

Signs of mental illness are recorded in 1,103 cases (22.5%).

Body-camera use is recorded as true in 578 cases (11.8%).

3,073 records (62.8%) are classified as not fleeing.

The three states with the highest raw incident counts in this workbook are California (701), Texas (426), and Florida (324).

**Important Interpretation Note**

This project is primarily a descriptive count analysis. Raw counts by race, state, or other group should not be interpreted as population-adjusted shooting rates or proof of causal disparity. A stronger disparity analysis would add population denominators, exposure measures, demographic context, and statistical testing.

**Tools and Skills Demonstrated**

Microsoft Excel

Data cleaning

Data categorization

Pivot tables

Dashboard design

Descriptive statistics

Data visualization

Demographic analysis

Business-style insight communication

**Workbook Structure**

shootings

Contains the incident-level dataset and cleaned analysis fields.

Pivot_tables

Contains summarized tables used to aggregate the data for charts and dashboard analysis.

Dashboard

Contains the visual summary of demographic and incident-level patterns.

Repository Structure

us-fatal-police-shootings-analysis/
├── README.md
├── GITHUB_DETAILS.txt
├── .gitignore
├── assets/
│   └── dashboard-preview.png
├── data/
│   ├── US_Police_Shooting_Disparities_Analysis.xlsx
│   └── us_police_shootings_2015_2020.csv
└── docs/
    └── DATA_DICTIONARY.md

**How to Explore the Project**

Open data/US_Police_Shooting_Disparities_Analysis.xlsx in Microsoft Excel.

Review the shootings worksheet to understand the raw and cleaned fields.

Review Pivot_tables to see the summarized analysis.

Open the Dashboard sheet to explore the visual analysis.

Use the CSV file if you want to recreate the project in SQL, Python, Power BI, or Tableau.

**Future Improvements**

Rebuild the dashboard in Power BI for interactive filtering.

Add year-over-year trend analysis.

Add U.S. population data to calculate population-adjusted rates.

Compare state incident counts with state populations.

Add more robust age bands and demographic cross-analysis.

Remove grand totals from chart source ranges where they should not appear as categories.

Add slicers for year, race, state, armed status, and body-camera status.

Build a SQL version of the analysis for query practice.
