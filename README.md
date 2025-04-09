
📱 Google Play Store Analytics – Internship Project
This repository contains the complete implementation of an interactive data analytics project on Google Play Store apps using Python. The goal of the project was to analyze and visualize trends in app categories, user ratings, installs, reviews, and more using advanced filtering techniques and dynamic time-bound visualizations.

📁 Project Structure

google-play-store-analytics/
│
├── data/
│   └── googleplaystore.csv              # Cleaned & formatted dataset
│
├── visualizations/
|   |-- interactive_wordcloud.html       # Word cloud (Task 1)
│   ├── groupchart.html                  # Grouped bar chart (Task 2)
│   ├── choropleth.html                  # Choropleth map (Task 3)
│   ├── violinplot.html                  # Violin plot (Task 4)
│   └── heatmap.html                     # Heatmap correlation matrix (Task 5)
│
├── scripts/
│   ├── googleplaystoreanalytics.ipynb
│
├── README.md                           

🔍 Project Overview

This project focuses on analyzing the Google Play Store app dataset by applying strict filtering conditions and generating insights using the following interactive charts:

✅ Task 1: Word Cloud from 5-Star Reviews (Health & Fitness)
Filters: Only 5-star reviews, app category = “Health & Fitness”
Excludes: Common stopwords and app names
Shows: Most frequent keywords mentioned in highly rated reviews
Output: Word cloud image displaying positive sentiment trends

✅ Task 2: Grouped Bar Chart
Filters: Rating ≥ 4.0, Size ≥ 10MB, Last Updated in January
Shows: Top 10 categories by installs with average rating & review counts
Time Limit: Visible only from 3 PM to 5 PM IST

✅ Task 3: Choropleth Map
Filters: Top 5 categories, excludes names starting with A, C, G, S, Installs > 1M
Shows: Category-wise global install distribution
Time Limit: Visible only from 6 PM to 8 PM IST

✅ Task 4: Violin Plot
Filters: App names containing “C”, ≥ 50 apps per category, ≥ 10 reviews, Rating < 4.0
Shows: Rating distribution by category
Time Limit: Visible only from 4 PM to 6 PM IST

✅ Task 5: Correlation Heatmap
Filters: Apps updated in the last year, Installs ≥ 100K, Reviews ≥ 1K, Genre not starting with A, F, E, G, I, K
Shows: Correlation between Installs, Reviews, and Ratings
Time Limit: Visible only from 2 PM to 4 PM IST

💡 Tools & Technologies Used
Python 3.x
Pandas, NumPy
Plotly (for interactive HTML charts)
Matplotlib & Seaborn
Jupyter Notebook

