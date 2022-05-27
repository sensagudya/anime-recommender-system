# anime-recommender-system

This is a guided-project of recommender system from 2019 Digital Talent Scholarship program. We use data from [Kaggle]( https://www.kaggle.com/datasets/CooperUnion/anime-recommendations-database?datasetId=571). The data is about 73516 user preferences in 12294 animes from myanimelist.net. The data used contain 2 files; anime.csv & rating.csv. Below, we display example data from those files. 

![anime.csv](documentation/anime_data.png)
![rate.csv](documentation/rate_data.png)

In this project, we built 2 kind of recommender system, namely content-based filtering and collaborative-filtering recommender system, based on user input below.

![userinput](documentation/user_input_1.png)

## content-based filtering recommender system

A content-based filtering anime recommendation system using only anime.csv. This recommendation system provides anime recommendations for users based on their watchlists and ratings. Then, the system adjusts the genre in the overall anime list with the anime genre that the user is watching. So that users have several anime recommendations to watch according to the genre they like. This system doesn't need other users' preferences to decide recommendations for a user. Below shows anime that the system recommended for the user. 

![result1](documentation/anime_recommendation_content_based.png)

## collaborative-filtering recommender system

A collaborative filtering anime recommendation system using anime.csv and rating.csv. This recommendation system provides anime recommendations for users not only based on their watchlists and ratings. We need other users' preferences too (in this case, the rating they give). Then, the system adjusts the rating in the overall anime list with the rating that the user gives. So that, users have several anime recommendations to watch according to similar tastes to other users. Below shows anime that the system recommended for the user.

![result2](documentation/anime_recommendation_collaborative.png)
