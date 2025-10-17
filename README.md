🎌 Anime Recommendation System Analysis

📘 Summary of Project

This project explores and analyzes data from a large-scale anime dataset to understand user preferences, rating patterns, and content-based relationships between anime titles. The goal is to identify insights that can improve recommendation quality and help design a more personalized anime recommendation system.

The notebook performs data cleaning, feature exploration, and visualization using Python’s data science ecosystem (pandas, numpy, matplotlib, seaborn). It also investigates correlations between genres, scores, popularity, and demographic factors such as gender and age.
Ultimately, it demonstrates how data-driven insights can enhance user engagement by surfacing the most relevant titles to different types of viewers.

🧩 Key Objectives

Analyze anime metadata (genres, studios, type, source, popularity)

Understand user rating patterns and demographic tendencies

Visualize genre distributions and relationships among features

Lay groundwork for building a recommendation model based on collaborative and content filtering ideas

📊 Data Overview

Main datasets used:

anime-dataset-2023.csv: Anime metadata (titles, genres, popularity, scores)

users-details-2023.csv: Demographic data and watch statistics

users-score-2023.csv: Individual anime ratings

📈 Example Visualizations

1. Gender and Age Distribution of Users

<img width="872" height="427" alt="Screenshot 2025-10-17 at 7 02 36 PM" src="https://github.com/user-attachments/assets/07867a44-7e1e-4184-9282-403a862ff129" />


2.  Main audiences' preference on sources

<img width="1096" height="385" alt="Screenshot 2025-10-17 at 6 59 53 PM" src="https://github.com/user-attachments/assets/6dd5966e-4210-44cc-bb96-8e100b2956d0" />


3. User Rating Consistency Across Genres

<img width="651" height="358" alt="Screenshot 2025-10-17 at 7 01 22 PM" src="https://github.com/user-attachments/assets/bb80c4f1-9b61-4c42-bf59-aa9ec0620312" />


🧠 Insights

No preference difference across region, age and gender

Top 5 Genres🎭: Award Winning, Suspense, Avant Garde, Drama, Mystery 

Top 4 Sources📚:  Manga, Original, Web Manga, Novel

We suggest: Item-Based Collaborative Filtering > User-Based Collaborative Filtering



⚙️ Tools and Libraries

Python: Core language

pandas / numpy: Data manipulation and computation

matplotlib / seaborn: Data visualization

scikit-learn (optional): Recommendation logic exploration
