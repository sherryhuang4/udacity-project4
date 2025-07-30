# Recommendation System Project

This project uses real data from users and articles on the IBM Watson Studio platform and makes recommendations about new articles.

## Project Instructions

All code can be found in the Jupyter notebook. You may need install some of the packages used in the notebook (matplotlib, scikit-learn, etc.). THe project includes the following sections:

### Exploratory Data Analysis

In this section, we look at and try to answer some basic, required questions about the data.

### Rank Based Recommendations

The first type of recommendation system we built is rank based, which finds the most popular articles based on the number of user interactions. This style of recommendation is good for new users with little to no history, as we don't need any information about/from the user to do rank based recommendations.

### User-User Based Collaborative Filtering

The second type of recommendation system we built is user-user based collaborative filtering, which finds similar users based on article interactions and recommends other articles that the similar users have interacted with that the specified user hasn't. This works well with users with a lot of history, as we are able to get similar users based on their history.

### Contet Based Recommendations

The third type of recommendation system we built is content based, which first clusters similar articles together using NLP and then recommends articles based on similarities in content.

### Matrix Factorization

The last type of recommendation system we built is matrix factorization. Using the user-item interactions, we built out a matrix decomposition. We use that matrix decomposition to get an idea of how well we can predict new articles an individual might interact with.

## Acknowledgements

This project was originally completed as part of the Udacity Data Scientist nanodegree.
