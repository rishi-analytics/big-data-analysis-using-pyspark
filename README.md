# Using PySpark for Big Data Analytics

[![Data Velho Rishi](https://img.shields.io/badge/Data%20Velho-Rishi-blueviolet)](https://rishi-analytics.github.io/)
![PySpark](https://img.shields.io/badge/Big%20Data-PySpark-orange)
![Google Colab](https://img.shields.io/badge/Environment-Google%20Colab-yellow)
![License](https://img.shields.io/badge/License-Educational-lightgrey)
![Dataset Size](https://img.shields.io/badge/Rows-13M%2B-blue)
![Course](https://img.shields.io/badge/Coursera-Guided%20Project-3cb371)


<p id="PySpark_Certificate" align="center">

<img src="PySpark_Course_Images/PySpark_Certificate.png"  width="600"  height="600">
    
</p>
---

Analyzed over **13 million rows** (13,758,905) of music listening data using **PySpark** on **Google Colab**.  
This project demonstrates how distributed data processing can efficiently handle big data tasks such as cleaning, querying, joining, and visualizing— all at scale, using Google Colab.

---

## Skills Gained & Applied

- Big data analytics using **PySpark**
- Data cleaning & transformation
- SQL-style queries and aggregations
- Joining datasets
- Visualizing results with **Matplotlib**
- Working in **Google Colab** cloud environment

---

## Dataset

- `listenings.csv` – User listening history (13M+ rows)
- `genre.csv` – Artist-genre mapping

---

## Some images from the project

<img id="picture1" src="PySpark_Course_Images/Screenshot 2025-07-09 at 2.47.38 AM.png" alt="alt text" width="600"/>

<img id="picture2" src="PySpark_Course_Images/task_1.png" alt="alt text" width="600"/>

<img id="picture1" src="PySpark_Course_Images/merging_2dataset.png" alt="alt text" width="600"/>

<img id="picture2" src="PySpark_Course_Images/query_7.png" alt="alt text" width="600"/>


## Tasks Overview

### ✅ Task 1: Setup
- Mounted Google Drive
- Installed PySpark
- Created Spark session

### ✅ Task 2: Load & Explore Data
- Loaded `listenings.csv`
- Checked schema and null values
- Dropped `date` column
- Removed null records
- Verified shape (~13.7M rows)

### ✅ Task 3: Queries on Main Dataset
- Filtered listening history by artist (e.g., Rihanna)
- Found top users, top tracks, and top albums
- Aggregated listening behavior

### ✅ Task 4: Merge Datasets
- Loaded `genre.csv`
- Performed **inner join** on `artist` to enrich data with genre info

### ✅ Task 5: Genre Analytics
- Identified users’ favorite genres (using `Window` & `Struct` methods)
- Counted artists per genre (pop, rock, metal, hip hop)
- Visualized genre-wise artist distribution with bar chart

---

## Certificate

([Certificate of Completion from Coursera](https://coursera.org/share/ee1e071b24629c33202b8de674074d1b))

---

## Full data analysis code in python is found 
[here](https://github.com/rishi-analytics/big-data-analysis-using-pyspark/blob/main/big_data_analysis_using_pyspark.ipynb)

