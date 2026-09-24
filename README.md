# AnalystLab_HealthConnect-Week5-Analysis

Week 5 HealthConnect Clinic Experience Lab - Data Analytics Project.

## Project Overview
This project focuses on analysing appointment attendance and no-show patterns at HealthConnect Clinic. I used Excel for exploratory data analysis and Power BI to develop an analytical dashboard.

## Key Areas Analysed
- Overall appointment outcomes
- Reminder status and reminder channels
- Previous no-show history
- Booking lead time
- Appointment type and time
- Distance to clinic
- Waiting time

## Key KPIs
- No-Show Rate: 48.46%
- Average Booking Lead Time for No-Shows: 34.53 days
- Repeat No-Show Rate: 55.41%
- Reminder No-Show Rate

## Tools Used
- Microsoft Excel
- Power BI

## Project Files
The repository contains the cleaned dataset, Power BI dashboard, dashboard PDF, exploratory analysis report and Week 5 project summary.

Prepared by: Rachel Nuhu Birma


## Week 6 – Advanced Analytics and Cross-Track Integration

In Week 6, I built on my Week 5 HealthConnect analysis by carrying out deeper analysis and validating the main findings.

### Key Findings
- Overall no-show rate remained 48.46%.
- No-show rate increased as booking lead time became longer:
  - 0–7 days: 29.47%
  - 8–14 days: 35.19%
  - 15–30 days: 45.53%
  - 31–60 days: 63.95%
- Previous no-show history also showed a strong pattern.
- Reminders were linked with a lower no-show rate.

### Dashboard Improvement
I kept the original HealthConnect Overview dashboard and added a second Power BI page for the Week 6 advanced analysis.

### Cross-Track Collaboration
I worked with a Data Science collaborator and shared my refined booking lead-time analysis with her. She independently validated the four groups and got the same no-show rates.

She also tested the refined feature using Logistic Regression and Random Forest. Although it did not lead to a major improvement in model performance, she kept the refined grouping because it was more detailed and better validated. Logistic Regression was selected as the final model because it maintained recall.

### Week 6 Files
- Advanced Analysis Excel workbook
- Power BI dashboard
- Decision Support Report
- Week 6 Project Summary
- Cross-track collaboration evidence
- Dashboard screenshots

### Next Step


## Week 7 — Testing, Refinement & Validation

Week 7 focused on testing and refining the analytical work developed during Weeks 5 and 6.

My Data Analytics work included:

- Validating key HealthConnect KPIs.
- Testing dashboard filters and calculations.
- Validating booking lead-time and previous no-show history findings.
- Testing booking lead time together with reminder status.
- Refining the Power BI dashboard with a Week 7 Validation & Refinement page.
- Re-testing the analytical results after refinement.
- Collaborating with the Data Science track to validate the combined finding.

The Data Science collaboration independently verified the combined booking lead-time and reminder-status results and tested an interaction feature. The interaction feature produced only a small change in accuracy, from 0.631 to 0.633, while short-lead-time recall remained at 6.1%, so it was not adopted.

The Week 7 work is documented in the `Week 7 HealthConnect Testing & Refinement` folder.

### Week 7 Outputs

- Week 7 Analytics Testing & Refinement Report
- Week 7 Project Summary
- Final Excel analysis and testing workbook
- Updated Power BI dashboard
- Week 7 testing and cross-track validation documentation
For Week 7, I will test how booking lead time, reminder status and previous no-show history work together and whether combining these factors provides stronger predictive or decision-making value.
