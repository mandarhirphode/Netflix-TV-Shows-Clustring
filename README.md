# Netflix-TV-Shows-Clustring

📺 Netflix Movies and TV Shows Clustering Project 🎥
Welcome to the Netflix Movies and TV Shows Clustering project! 🚀 This unsupervised machine learning project dives into the exciting world of Netflix's content, uncovering patterns and insights from a dataset of movies and TV shows available as of 2019. Let’s explore the magic of data clustering and content analysis! ✨
📖 Project Overview
This project analyzes a dataset from Flixable, a third-party Netflix search engine, to:

🔍 Perform Exploratory Data Analysis (EDA) to understand the dataset.
🌍 Discover content availability across different countries.
📊 Investigate Netflix's focus on TV shows vs. movies over the years.
🧩 Cluster similar content using text-based features for a deeper understanding of content patterns.

The dataset includes 7,787 entries with details like show ID, type, title, director, cast, country, release year, rating, duration, genres, and descriptions. 📈
🎯 Objectives

EDA: Uncover trends, distributions, and relationships within the Netflix dataset. 📉
Content Distribution: Analyze what types of content are available in various countries. 🌎
Trend Analysis: Investigate if Netflix is shifting focus toward TV shows or movies. 📺🎬
Clustering: Group similar movies and TV shows using text-based features with unsupervised ML techniques like K-Means and Hierarchical Clustering. 🧑‍💻

📂 Dataset Description
The dataset contains the following key columns:

show_id: Unique ID for each movie/TV show.
type: Movie or TV Show.
title: Title of the content.
director: Director of the movie.
cast: Actors involved.
country: Country of production.
date_added: Date added to Netflix.
release_year: Year of release.
rating: TV rating (e.g., TV-MA, PG-13).
duration: Duration in minutes (movies) or seasons (TV shows).
listed_in: Genres.
description: Summary of the content.

🛠️ Tools & Libraries Used
This project leverages a powerful stack of Python libraries to analyze and visualize the data:

🐍 Pandas & NumPy: Data processing and wrangling.
📊 Matplotlib, Seaborn, Plotly: Data visualization.
🔤 NLTK, Scikit-learn: Text preprocessing and clustering (TF-IDF, K-Means, Agglomerative Clustering).
☁️ WordCloud: Visualizing text data.
⚠️ Warnings: Suppressing unnecessary warnings for cleaner output.

🚀 Key Steps

Data Loading: Loaded the Netflix dataset from a CSV file using Google Colab. 📂
EDA: Explored distributions of movies vs. TV shows, genres, ratings, and release trends. 📈
Text Preprocessing: Cleaned and transformed text data (descriptions, genres) using TF-IDF Vectorizer for clustering. 🧹
Clustering:
Applied K-Means and Hierarchical Clustering (Agglomerative with Ward linkage).
Identified 26 optimal clusters using the elbow method and silhouette score. 🧑‍💻


Evaluation: Used Silhouette Coefficient (-0.002 for Hierarchical) and Davies-Bouldin Score (13.98 for Hierarchical) to assess clustering performance. 📏
Insights: Analyzed content trends, regional distribution, and Netflix’s focus on movies vs. TV shows. 🔎

📊 Key Findings

Content Distribution:

Netflix hosts 5,372 movies and 2,398 TV shows, with movies dominating the platform. 🎬
TV-MA is the most common rating for TV shows, while Documentaries lead movie genres, followed by Stand-up Comedy and Dramas. 📼
Kids’ TV is the top genre for TV shows. 👶


Release Trends:

Movie releases peaked in 2017, 2018, and 2020, with a surge in content post-2015. 📅
A decline in production was observed after 2020, suggesting a shift toward movies over TV shows. 📉
Most content is added between October and January. 🍂❄️


Durations:

Movies typically run 50–150 minutes, with NC-17 movies having the longest average duration and TV-Y the shortest. ⏱️
Most TV shows have single seasons, favoring limited-series formats. 📺


Regional Insights:

The United States leads in total titles, while India has the most movies. 🇺🇸🇮🇳
30% of movies are Netflix exclusives, with 70% released elsewhere first. 🌟


Clustering:

K-Means outperformed Hierarchical Clustering, with Cluster 0 containing the most data points. 🧩
Clusters reveal patterns in content based on text features like genres and descriptions. 📜



📈 Visualizations

Word Clouds: Highlighted frequent words in descriptions and genres. ☁️
Bar/Line Plots: Showed trends in releases, ratings, and genre popularity. 📉
Dendrograms: Visualized Hierarchical Clustering structure. 🌳
Cluster Visualizations: Displayed content groupings using K-Means and Silhouette plots. 📊

📝 Conclusion
This project successfully clustered Netflix content, revealing key insights into content distribution, trends, and regional preferences. The analysis confirms Netflix’s stronger focus on movies, with a notable shift post-2015 and seasonal content additions. Clustering helped identify content similarities, with K-Means proving more effective than Hierarchical methods. 🏆
🌟 Future Work

Integrate external datasets like IMDb or Rotten Tomatoes for richer insights. 🍅
Experiment with advanced clustering algorithms (e.g., DBSCAN, Spectral Clustering). 🧑‍💻
Build a recommendation system based on cluster assignments. 🎥


🎉 Happy Analyzing! Let’s uncover more stories hidden in Netflix’s vast content library! 🍿
