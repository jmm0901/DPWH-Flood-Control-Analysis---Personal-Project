# 🇵🇭 DPWH Flood Control Projects Dashboard
## Project Overview
This project involves an end-to-end analysis of the Department of Public Works and Highways (DPWH) Flood Control Projects in the Philippines. Using Power BI, I created an interactive executive dashboard to audit budget allocations, track project completion rates, and analyze the geospatial distribution of flood control infrastructure from 2018 to 2026.

The goal is to provide transparency into government spending, identifying which regions receive the most funding and which contractors handle the largest volume of projects.

## 📊 Dashboard Preview

<img width="1413" height="790" alt="image" src="https://github.com/user-attachments/assets/8eaf2725-7d1f-466b-8297-f330650f938d" />

Data Source
Dataset: DPWH Flood Control Projects on Kaggle
Link: https://www.kaggle.com/datasets/bwandowando/dpwh-flood-control-projects

Source Agency: Department of Public Works and Highways (DPWH) / DIME


Key Columns: Project Name, Region, Contract Cost, Approved Budget, Contractor, Status

## 🎯 Key Objectives

Budget Audit: Compare Approved Budget vs. Actual Contract Cost to calculate variance and savings.

Regional Analysis: Identify which regions are prioritized for flood control funding.

Operational Status: Track the ratio of Completed vs. Ongoing projects.

Contractor profiling: Identify the top contractors by total project value.

## 🛠️ Tech Stack & Methodology
Tool: Microsoft Power BI

Data Transformation (Power Query):

Cleaned currency columns.

Standardized Contract Cost and Approved Budget to decimal types.

DAX Measures:

Project Status Logic: Categorized projects as "Ongoing" if ActualCompletionDate was blank.

Top N Analysis: Dynamic ranking for Top Regions and Top Contractors.

Financial Metrics: Calculated Total Savings (Budget - Cost) and Completion Rate %.

## 📈 Key Insights
Top Region: Region III (Central Luzon) receives the highest funding allocation, significantly outpacing the National Capital Region (NCR).

Market Leaders: A small group of contractors (e.g., Legacy Construction) handles a disproportionately large share of the total contract value.

Timeline: A significant spike in project funding was observed starting in 2022.
