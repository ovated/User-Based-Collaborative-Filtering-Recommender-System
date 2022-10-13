# User-Based-Collaborative-Filtering-Recommender-System

Movie recommender system with user-based collaborative filtering, that recommends top 10 movies you should watch according to the movie preferences of similar users.

## Description

Takes users input, finds similar users who rated the movie 5/5, gets the movies all similar users rated 5/5, calculates the recommendation score, and recommends the top 10 with the highest score.

### Key variables:

- similar_users_score: This contains the percentage of similar users who rated the movie 5/5

- all_users_score: This contains the percentage of all_users who rated the movie 5/5

- recommendation_score: This is ratio or difference between the similar_users_score and the all_users_score

#### Data

Please find the link to the complete data [here.](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbjZLSmRDTlF6Z2hiWUdBWU83QmNzOFRyRE9sZ3xBQ3Jtc0tsV1EzSmpxaG5vakdEVk16RWhCZFk3dEFLYnhKUVVzTTJSa3ZDam9hZF9XVjdJSnFGMVZfUTdyME1Ucmd0bzhUX0VxNHlMVXRYVHJBNVNFVzNtVWhrRmZPMjBGN1RFZ3JaaHpDQVdNZTZTYWotdFBJOA&q=https%3A%2F%2Ffiles.grouplens.org%2Fdatasets%2Fmovielens%2Fml-25m.zip&v=eyEabQRBMQA)