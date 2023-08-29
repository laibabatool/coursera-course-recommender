# coursera-course-recommender

it recommends courses on the context of previous course you have done from coursera

the dataset of coursera courses has taken from kaggle

the method i have used for content-based recommendation system is:
first i apply TF-IDF Vectorization to the content of the recommender system, in this project i used 'Course Description' as content.
then i apply cosine_similarity on the vector which i have created by tf-idf.
cosine similarity is like a tool that measures how much two things are alike.
