# Recommender-using-Iterative-RSVD

## Introduction
This is a recommender system using iterative RSVD algorithm. The dataset is tmbd dataset from kaggle (https://www.kaggle.com/tmdb/tmdb-movie-metadata). The dataset contains 4803 movies and 20 features for each movie. The features include genres, keywords, production companies, production countries, release date, revenue, runtime, spoken languages, vote average, vote count, etc. The goal of this project is to recommend movies to users based on their ratings on movies.
Instead of using the metadata of the movie we're trying to bulid a recommender using the method of collaborative filtering. 

## About RSVD
RSVD is a matrix factorization method. It factorizes the user-item matrix into two low rank matrices. The user-item matrix is a sparse matrix. The RSVD algorithm is an iterative algorithm. It first initializes the two low rank matrices and then iteratively updates the two matrices until the error is small enough. The error is defined as the difference between the user-item matrix and the product of the two low rank matrices. 
The matrix is factorized into two low rank matrices U and V. U is the matrix of user latent factors and V is the matrix of item (here move) latent features.
