# Recommendations-with-IBM

## Introduction
The purpose of this project is to analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles they would like. 

The notebook is divided in four parts 

**I. Exploratory Data Analysis**

This part aims to explore the data that we will be working with for the project 

**II. Rank Based Recommendations**

This part aims to find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

**III. User-User Based Collaborative Filtering**

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users.

**IV. Matrix Factorization**

Using the user-item interactions, this part aims to build a matrix decomposition. Using your decomposition, we will get an idea of how well we can predict new articles an individual might interact with. We will finally discuss which methods you might use moving forward, and how you might test how well your recommendations are working for engaging users.

This project is part of the Udacity Data Scientist Nanodegree Program
