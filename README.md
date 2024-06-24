# Movie Recommendation System

## Objective
The objective of this project is to build a recommendation system that suggests movies to users based on their preferences and past behavior.

## Data Source
The dataset used for this project is the MovieLens dataset, which contains millions of movie ratings from users. It can be downloaded from [MovieLens](https://grouplens.org/datasets/movielens/).

## Project Outline
1. Import Library
2. Import Data
3. Describe Data
4. Data Visualization
5. Data Preprocessing
6. Define Target Variable (y) and Feature Variables (X)
7. Train Test Split
8. Modeling
9. Model Evaluation
10. Prediction
11. Explanation

## Import Library
The following libraries are required for this project:
- pandas
- numpy
- matplotlib
- seaborn
- sklearn
- scipy

## Import Data
The data is imported using pandas:
```python
import pandas as pd

movies = pd.read_csv('movies.csv')
ratings = pd.read_csv('ratings.csv')
