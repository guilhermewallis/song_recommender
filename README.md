# Song Recommender
## Goal
#### The goal of this script is to provide song recommendations to a user based on their input making use of a machine learning algorithm
#### The algorithm generates the recomendation based on one condition:
* if the inputed song is currently popular/trending, it suggests an also currently popular song. Otherwise it returns a  recommendation from a larger more generic pool of songs.
    * It implements an unsupervised learning algorithm that creates clusters of songs based on similarities in their audio features.
    * It then matches the inputed song with the most similar cluster in the data and recommends the closest element to the user.
## Data
#### The script gathers song data containing song names, artist names and several features of the audio track
* data is sourced through the Spotify API
* song choices are researched throughout the web and sourced from popular user generated and offical Spotify playlists:
    * popular charts and trending in social media (ex Billboard, Tiktok)
    * recently popular/emerging artists
    * top countries by music market share (ex Wikipedia article)
    * most popular music genres in current days
    * greatist hits of past decades and/or specific popular genres
