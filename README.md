# Spotify-Project

In this Github, you can find the work I did with three of my fellow comrades, Mohammed Nafeez Abubacker (from India), Min Chen (from China) and Jella Carillo (from Philippines) in the context of our Machine Learning Course (Master in Data Science & Business Analytics -Essec Business School & CentraleSuplec in France-).

We chose to develop aglorithms that can predict the popularity of a song in Spotify. On Spotify, the popularity of a song is a score between 0 and 100. In our study, we turned this feature into bi-class feature to make our life easier and work on a simple classification problem. The 25% most popular songs were considered as popular (1), the remaining one as non-popular (0).
We used and merged two databases : a dataset A with 232,725 tracks extracted from the Spotify API with their Spotify features (artist, danceability,duration, popularity, speechiness, etc.) and a dataset B of lyrics of 57,650 songs. We focused our whole study on the resulting merged dataset of 5261 songs with their lyrics and their Spotify features.

Our key features can be divided in two parts : the first one coming from the sentiment analysis of the lyrics (three features) and the second one coming from the original Spotify features (a dozen of original features).
We performed encoding on certain features (such as the name of the artist) to get around 500 features. Using feature selections, we got our best results with AdaBoost with an accuracy of 0.78 and 60 features. (As it was our first Machine Learning Project, we did not know XgBoost at the time).

You can also find herewith our final report, final code as well as the ppt presentation detailing our methodologies and results. Good reading !
