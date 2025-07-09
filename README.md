# Cyclistic Bike-Share Capstone Project

Welcome to my capstone project, part of the **Google Data Analytics Professional Certificate**. In this project, I apply the knowledge and skills I have gained throughout the program’s seven courses to answer key business questions and deliver data-driven insights.

To make the analysis process effective and reliable, I followed the six steps of the data analysis process: **Ask, Prepare, Process, Analyze, Share, and Act**.  
Tools used: **Microsoft Excel**, **BigQuery**, and **Tableau**.

---

##  Scenario

I am a junior data analyst working on the **marketing analytics team at Cyclistic**, a Chicago-based bike-share company. The director of marketing believes that increasing the number of **annual memberships** is crucial for future growth. Our team has been tasked with analyzing how **casual riders** and **annual members** use Cyclistic bikes differently, to help design a targeted marketing strategy that encourages casual riders to become members.

---

## About the Company

- Launched in 2016
- 5,824 geotracked bikes
- 692 docking stations across Chicago
- Flexible pricing plans: single-ride, full-day, and annual memberships
- Casual riders = Single-ride or day-pass users  
- Members = Annual subscription users

Cyclistic’s finance team has concluded that **annual members are more profitable** than casual riders. The marketing team wants to focus on converting casual riders into members by analyzing behavioral differences.

---

## Business Task

**Goal:** Analyze how annual members and casual riders use Cyclistic bikes differently, using historical data from **March 2023 to February 2024**.

**Context:** Insights from this analysis will help the marketing team design a strategy to convert casual riders into annual members.

**Assigned Question (by Manager):**  
 _"How do annual members and casual riders use Cyclistic bikes differently?"_

---

## Key Stakeholders

- **Lily Moreno:** Director of Marketing. Oversees campaigns including email, social, and digital media.
- **Cyclistic Marketing Analytics Team:** Analyzes and reports insights to guide strategy.
- **Cyclistic Executive Team:** Reviews recommendations for approval.

---

## Data Preparation

### Where is the data located?
- PublIc dataset available on **AWS**.
- Covers 12 months: **March 2023 to February 2024**.
- Files are stored monthly in **.zip** format.

### How is the data organized?
- Monthly CSV files, each representing a month of ride data.
- Includes trip start/end times, ride length, bike type, user type, station info, etc.

### Data Credibility Check (ROCCC):

- **Reliable:** Yes, published by a credible source.
- **Original:** Yes, provided by Motivate International Inc.
- **Comprehensive:** Yes, includes key fields required for analysis.
- **Current:** Yes, data is up to date through February 2024.
- **Cited:** Yes, proper citation is included.

### Privacy, Licensing & Security

- Data is shared under a license by **Motivate International Inc.**
- No personally identifiable information (PII) is included.
- Cannot match user passes with credit card data or location of residence.

---

## Data Processing

- The data was downloaded, cleaned, and merged for further analysis. This includes:
- Removing duplicate records
- Filtering invalid trip durations (e.g., <1 minute)
- Converting datetime formats
- Creating new variables like day of week, hour, ride length

  ---

- ##  Analyze 

- Explored trip duration, ride type, time-based trends, and station usage to compare casual and member riders.
- Used SQL queries to summarize and extract key insights from the cleaned master dataset.
- Identified clear differences in riding patterns that helped define user behaviors.


---

## Visualize And Share

- Built Tableau dashboards to visualize ride frequency, bike preferences, and usage trends.
- Highlighted monthly, weekly, and station-based patterns to support key insights.
- Made findings easier to understand and interpret for stakeholders.

---

## Act

- Provided recommendations to convert casual riders into members using seasonal and behavioral trends.
- Suggested targeted promotions, referral programs, and station-based campaigns.
- Noted missing station data as a quality issue to address in future data collection.


