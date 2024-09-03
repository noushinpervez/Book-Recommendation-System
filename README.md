# Book Recommendation System

## Overview

This project implements a book recommendation system using collaborative filtering with k-nearest neighbors (k-NN). The system predicts user ratings for books and provides recommendations based on user preferences. The Surprise library is used to build and evaluate the k-NN model. Python functions are included to deliver personalized book recommendations and rating predictions. The dataset can be obtained from [here](https://www.kaggle.com/datasets/ruchi798/bookcrossing-dataset/data).

## Dataset Characteristics

- **Books Dataset**: Contains information about 271,379 books, including attributes like ISBN, title, author, publication year, and publisher.
- **Book Ratings Dataset**: Includes 1,149,780 ratings given by users to various books. Each rating can be explicit (user-provided) or implicit.
- **Users Dataset**: Contains demographic information for 278,858 users, including user IDs, location, and age.

## Key Features

- Utilizes user-based collaborative filtering to recommend books based on user similarity.
- Implements the k-nearest neighbors algorithm to predict ratings and generate recommendations.
- Excludes books and users with insufficient interaction to enhance recommendation quality.

## Prerequisites

- **Python**: Version 3.6 or higher
- **Jupyter Notebook**: If using Google Colab or any notebook environment
- **Required Libraries**: 
  - `pandas` 
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-surprise`