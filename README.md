
# 📊 JobStreet Malaysia Job Listings Analysis

This repository is part of Data Management courses project showcasing a real-world data project that involves **web-scraped job listings from JobStreet Malaysia**. The focus is on using **Hive** for big data querying and **Python (Google Colab)** for data cleaning, analysis, and visualization.

**Objective**:  
To analyze the Malaysian job market by identifying hiring trends across job categories (e.g., IT, Accounting, Logistics, Engineering, Construction), job roles, and determine the **top hiring companies contributed in Jobstreet job listings** and the **most common job by locations**.

---
## 📌 Data Overview

The dataset used in this project contains job listings sourced from [Kaggle](https://www.kaggle.com/datasets/azraimohamad/jobstreet-all-job-dataset/data). 
This dataset compiles a huge range of job listings from Jobstreet, offering a comprehensive view of the current employment landscape from various industries in Malaysia specifically. It includes detailed information such as:

| Column Name   | Description                                                           |
| ------------- | --------------------------------------------------------------------- |
| `job_id`      | Unique identifier for each job listing                                |
| `job_title`   | The title of the job position (e.g., Software Engineer, Accountant)   |
| `company`     | Name of the company offering the job                                  |
| `location`    | City or region in Malaysia where the job is located                   |
| `category`    | Broad job category (e.g. Accounting, Engineering, etc.)               |
| `subcategory` | More specific area within the category (e.g., Mechanical Engineering, Software Developer) |
| `role`        | Job role or function (e.g., account-executive.)                       |
| `type`        | Employment type (e.g., Full-Time, Part-Time etc.)                     |
| `salary`      | Salary information if provided (e.g., RM3,000 - RM5,000)              |
| `listingdate` | Date the job was posted/listed on JobStreet                           |


---

## 🛠️ Tools & Technologies

| Tool        | Description                                 |
|-------------|---------------------------------------------|
| 🐘 Hive     | SQL-like querying of structured data        |
| 🐍 Python   | Data manipulation and visualization         |
| 📓 Google Colab | Cloud notebook environment              |
| 🐼 Pandas   | DataFrame manipulation                      |
| 📊 Seaborn/Matplotlib | Data visualization libraries     |

---

## 🧠 Key Skills Demonstrated

- Writing efficient **Hive SQL** queries to summarize large datasets
- Integrating Hive with **Google Colab** using `PyHive`
- Performing **data cleaning** and preprocessing in Python
- Creating **visualizations** to analyse job markets. 
- Showcasing findings through a structured, reproducible notebook

---
## 🔍 Key Insights

- What is the most category of jobs listed in Jobstreet?
- Which job category offer part-time role?
- What is the top sub-category of job listed?
- What are the top hiring companies actively posted jobs on Jobstreet?
- How do job location distributions differ across job categories?
- Which locations are hubs for jobs across categories?


