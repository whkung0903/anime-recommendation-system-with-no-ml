# Anime Recommendation System Analysis
**Project Manager: Grace Kung (Me)**

Group Members: Allen Chiu, Maggie Croghan, Emily Su, Pin-Chen Kuo, Hannie Han

A data science project analyzing anime ratings, genres, and user preferences to build a recommendation system.
This project explores data preprocessing, visualization, and collaborative filtering techniques to recommend anime titles based on user behavior.

## **📘 Project Overview**

This notebook performs a full analysis of an anime dataset to uncover patterns and build recommendation models.
It covers exploratory data analysis (EDA), feature engineering, and the implementation of various recommendation approaches.

## **📊 Dataset**

The dataset used is from [Anime Recommendation Database](https://www.kaggle.com/datasets/dbdmobile/myanimelist-dataset?select=final_animedataset.csv) (Kaggle)

It contains:

* Anime information: title, genre, episodes, members, and ratings
* User ratings: user ID, anime ID, and rating (1–10 scale)

## **🧠 Methodology**

1. Data Cleaning
* Handle missing and inconsistent data
* Normalize text data (titles, genres)
2. Exploratory Data Analysis (EDA)
* Visualize rating distributions, top genres, and user activity
* Correlation between popularity and average score
3. Result Visualization
* Genre heatmaps, top-N recommendations, and rating patterns

## **📈 Results Summary**
**I. Audience Insights**

The majority of users are aged 25–39, mainly located in Europe and North America. Their rating behaviors are consistent across region, gender, and age, indicating no significant demographic segmentation in anime preferences.

**II. Content Strategy: What to Air**

Since preferences remain stable across different user groups, platforms should focus on content that appeals broadly.

* Top 5 Genres: Award Winning, Suspense, Avant Garde, Drama, Sports
* Top 4 Sources: Manga, Original, Web Manga, Novel

**III. User Engagement Patterns**

While most users’ viewing days fall below 159 and show no clear correlation with rating behavior, engagement levels do not strongly influence satisfaction.
Popularity and quality only partially overlap (30%), suggesting both should be considered when curating or promoting titles.

**IV. Recommendation System Design**

Given users’ consistent behavior and high rating stability (low variance within genre/type/source), an item-based recommendation approach is more suitable than a user-based one.

Key predictive features: Genre, Type, and Source.

**V. Strategic Implication**

Platforms should prioritize content diversity within high-performing genres and sources, and refine their recommendation systems around item attributes rather than user demographics or viewing time. This approach maximizes relevance and scalability while aligning with audience preferences.
