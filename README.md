# Songs Recommender System
A step-by-step guide to building a Python-based Songs Recommender System using Cosine Similarity

## Overview
In this notebook, we will be using cosine similarity to produce songs recommendation. We will be using data from Spotify to cluster the songs into different song types and see what kinds of songs have the same attributes. 

We will use the k-means algorithm to sort the songs into different types. We will then use the clustered database to create a recommendation system and make a few recommendations.

By the end of this notebook you will be able to find similar songs to your favorite song, and hopefully, find new favorite songs :)

We’ll use a dataset from Kaggle: <https://www.kaggle.com/datasets/rodolfofigueroa/spotify-12m-songs>

The dataset contains audio features for over 1.2 million songs, obtained with the Spotify API. 

Reference for these audio features can be found here: <https://developer.spotify.com/documentation/web-api/reference/#/operations/get-audio-features>
