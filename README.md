# Movie-Recommendation-System

Movie Recommendation System
Application used to recommend similar movies according to users choice of movie using machine learning

Types of Recommendation System:
 1) Content Based :Recommends on basis of sililarity of the content. (tags)
 2) Collaborative Filtering based : Recommends on the basis of users interest or users similarity.
 3) Hybrid: It consist of both Content based and Collaborative based approach.

Project Flow:
 
Data collection
Data Preprocessing 
Model building
Convert model to website
Deploy website


Dataset Link: https://www.kaggle.com/datasets/harshitshankhdhar/imdb-dataset-of-top-1000-movies-and-tv-shows
 


We have two datasets with us one is credit score dataset and the other movie dataset
In this project we are using Content Based Filtering, so we need to create tags for each object.

In this project we used feature extraction or text vectorization technique to find similarity between movies. Scikit-learn's CountVectorizer is used to convert a collection of text documents to a vector of term/token counts.
 


Reference:
https://medium.com/python-in-plain-english/tmdb-streamlit-build-your-own-movie-recommendation-system-f2ffbca63d11

Tools used:
jupyter notebook, Pycharm ide 
