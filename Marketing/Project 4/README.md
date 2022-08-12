Project 4 - A Yelp-powered Restaurant Recommendation Program from CS61A 
![image](https://user-images.githubusercontent.com/105506874/184378565-c62c5461-6e78-40b3-9b90-2c6752bc76d9.png)
In this project, a visualization of restaurant ratings is created. In this visualization, Berkeley is split into different regions, each shaded by the predicted rating of the nearest restaurant (5 stars in yellow and 1 star in blue).

This model uses Unsupervised Learning (k-means) and Supervised Learning (linear regression).
The Unsupervised Learning part divides Berkeley into different areas using restaurant location information. It groups restaurants that are close to each other into these clusters.

The Supervised Learning section predicts how many ratings a user will give a restaurant. The model will try to infer the correct rating from the examples of known correct ratings. By analyzing the user's past ratings, we can try to predict how a user will rate a new restaurant.
