# Hospital Emergency Room Dashboard

## Project Overview
This project presents an interactive dashboard for analyzing Emergency Room (ER) patient data spanning 19 months and covering 9,216 unique patient records. The dashboard provides insights into patient flow, wait times, satisfaction, departmental referrals, and demographics to help improve ER operational efficiency and patient care quality.

## Key Objectives
- Monitor ER performance monthly and over custom date ranges.
- Analyze patient admission status and referral patterns.
- Track patient wait times and satisfaction scores.
- Understand patient demographics including age, gender, and race.
- Provide detailed patient-level data for granular analysis.
- Deliver actionable insights for hospital decision-makers.

## Data Description
The dataset includes anonymized patient records with fields such as:
- Patient ID
- Admission date and time
- Patient name (initial and last name for anonymity)
- Gender, Age, Race
- Department referrals (e.g., Orthopedics, Cardiology)
- Admission status (admitted or not)
- Patient satisfaction score (scale 1-10)
- Patient wait time in minutes
- Case manager ID

For more details, see [Data Terminology](./Data-Terminology.docx).

## Dashboards Included

### 1. Monthly View
Tracks key metrics and trends monthly:
- Admission status count and percentages
- Patient age distribution in 10-year intervals
- Department referrals analysis
- Percentage seen within 30 minutes (timeliness)
- Gender and race demographics
- Patient volume by day and hour

### 2. Consolidated View
Aggregates data across any date range with the same metrics as the monthly view for trend analysis.

### 3. Patient Details
Displays granular data at the patient level for deep analysis and troubleshooting.

### 4. Key Takeaways
Summarizes findings, patterns, anomalies, and provides recommendations to optimize ER performance.

## Key Metrics
- Total number of patients
- Average wait time (~35 minutes)
- Average patient satisfaction score (~5 out of 10)
- Number of patients referred per department
- Patient volume peak days and hours

## Tools & Technologies
- Power BI for data modeling, visualization, and dashboard creation
- Excel for initial data cleaning and exploration
- DAX for advanced metric calculations

## How to Use
1. Open the Power BI report file(available in respository) to explore dashboards interactively.
2. Review raw data in the `Hospital-ER_Data.csv.xlsx`.
3. Reference `Data-Terminology.docx` for column descriptions.
4. Use insights to guide ER resource allocation and patient care improvements.

## Project Summary
- 9,216 ER patient records from April 2023 to October 2024
- Balanced admission rates (~50%)
- Peak patient times on Saturdays and during mid-morning and evening hours
- Frequent referrals to General Practice and Orthopedics
- Diverse patient demographics with the largest groups being White and African American

## Author
**Vamsi Alluri**  
Email: vamsialluri2004@gmail.com  
Date: September 2025
