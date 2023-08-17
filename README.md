# Anime-Recommendation

## Dataset Overview

This repository contains a comprehensive Anime Recommender System that utilizes a dataset comprising user preferences for various anime. The dataset, obtained from Kaggle, consists of two main files: `anime.csv` and `rating.csv`.
Dataset not added in this repository.

### anime.csv

This file contains information about different anime entries, including:

- `anime_id`: A unique identifier for each anime on myanimelist.net.
- `name`: The full name of the anime.
- `genre`: A comma-separated list of genres associated with the anime.
- `type`: The type of the anime (e.g., movie, TV, OVA).
- `episodes`: The number of episodes in the anime (1 if it's a movie).
- `rating`: The average rating out of 10 for the anime.
- `members`: The number of community members associated with the anime.

### rating.csv

This file contains user ratings for various anime, including:

- `user_id`: A non-identifiable randomly generated user ID.
- `anime_id`: The anime that the user has rated.
- `rating`: The rating (out of 10) assigned by the user to the anime (-1 if no rating was assigned).

## Project Overview

This Jupyter Notebook presents an Anime Recommender System that harnesses the power of machine learning techniques to provide personalized anime recommendations to users. The recommendation models are built using a combination of genre information and anime types. Additionally, a special consideration has been given to address the "cold start" problem, where users who are new to the platform are provided with recommendations based on their favorite genres.

## Repository Contents

- `Anime Recommender.ipynb`: A Jupyter Notebook containing the complete workflow of the Anime Recommender System. This notebook showcases the development of multiple recommendation models, including genre-based, genre and type-based, and a cold-start solution using the Bray-Curtis metric. The notebook also includes exploratory data analysis and visualizations to derive insights from anime and user ratings.

## Getting Started

To explore and utilize the Anime Recommender System, follow these steps:

1. Download or clone the repository to your local machine.
2. Open the Jupyter Notebook `Anime Recommender.ipynb` using a compatible environment (e.g., Jupyter Notebook, VS Code)
