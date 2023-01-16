#Predicting How Long One Song Will Stay On Chart
## Using data from Spotify top charts to predict the next hit assuming the longer it stays on charts, the more popular it is
###TOC
1. Data: [Spotify top charts 2022](https://github.com/krystalduong/SpotifyAnalyst/blob/main/Data/spotify_top_charts_22.csv)
2. Business Problem
The music industry is a turbulent place. Artists who once dominated the charts fall out of favor, while newcomers may unexpectedly take the stage. There never seems to be a definite pattern, and no matter what anyone knows, it's nearly impossible to predict which songs will make the cut.
With that in mind, knowing which songs are popular on Spotify and the characteristics of those songs, we will be able to find correlations algorithmically that will provide a little more certainty when predicting the next 'hit'.
3. Modeling
a. Linear Regression: 'RMSE': 35.98, 'RSquared ': 0.11
b. K-Nearest Neighbors: 
![alt text](https://github.com/krystalduong/SpotifyAnalyst/blob/main/Image/KNNerror.png)
c. Random Forest
![alt text](https://github.com/krystalduong/SpotifyAnalyst/blob/main/Image/FeatureImportance.png)
4.Results
It is difficult to determine if a song will be a popular or not. There are many factors at play that are not included in this dataset, like artist popularity, genre, country of origin, etc. However, my best model got meto within 85% of my target value. I can predict how long one song will stay on chart and the search will continue.