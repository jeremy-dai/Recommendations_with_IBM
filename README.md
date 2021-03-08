# Recommendations_with_IBM
 
This analyzes the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles you think they will like. In order to determine which articles to show to each user, we perform a study of the data available on the IBM Watson Studio platform. 

## Exploratory Data Analysis

Before making recommendations of any kind, we explore the data we are working with for the project. 

## Rank Based Recommendations

To get started in building recommendations, we first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

## User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. 

## Content Based Recommendations

Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using the NLP skills, we come up with a way to develop a content based recommendation system. 

## Matrix Factorization

Finally, we complete a machine learning approach to building recommendations. Using the user-item interactions, we will build out a matrix decomposition. Using the decomposition, we will get an idea of how well we can predict new articles an individual might interact with (spoiler alert - it isn't great). We will finally discuss which methods we might use moving forward, and how we might test how well our recommendations are working for engaging users.