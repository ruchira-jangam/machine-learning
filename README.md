Movie Recommendation System based on Reviews
This repository contains the code and data files for a data science project aimed at building a movie recommendation system that recommends movies to users based on their previous movie reviews. The project uses Python programming language and several libraries including pandas and Scikit-learn.

Dataset
The dataset used in this project consists of two files: db_5000_credits.txt and db_5000_movies.txt. The first file contains information on the cast and crew of movies, while the second file contains information on the movies themselves including their titles, release dates, and genres.

Tech Stack
The tech stack used in this project includes:

Python programming language
pandas library for data manipulation and analysis
Scikit-learn library for machine learning algorithms
Approach
The movie recommendation system is built using collaborative filtering approach. Collaborative filtering is a technique used by recommender systems to make predictions about user interests by collecting preferences from many users. In this approach, the system identifies similar users based on their movie preferences and recommends movies that similar users have liked.

The first step in building the recommendation system involves preprocessing the dataset to extract relevant features such as movie genres, cast, crew and reviews. Next, a machine learning model is trained on the preprocessed dataset using the Scikit-learn library. The model uses collaborative filtering algorithm to recommend movies based on the reviews of previous movies.
