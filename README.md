# Rotten Tomatoes Analysis

### Description

The purpose of this project was to:
- experiment with creating a recommendation system
- practice NLP
- experiment with time series modeling
- play with the Prophet library



### Data

The data used for this analysis included:
- [Rotten Tomatoes Kaggle Data](https://www.kaggle.com/datasets/stefanoleone992/rotten-tomatoes-movies-and-critic-reviews-dataset)



### Challenges
- The [Prophet library](https://facebook.github.io/prophet/) was a little difficult to get installed.  This [link](https://blog.quantinsti.com/installing-prophet-library-mac/#:~:text=conda%20install%20jupyter-,Installing%20the%20Prophet%20dependencies,using%20pip%20to%20install%20prophet.&text=With%20PyStan%20and%20its%20dependencies,you%20need%20to%20install%20Prophet.) proved to be very helpful in getting started.

### Things I Learned
- Seems obvious now, but time series models will perform better when there's a trend present in the data.  Most of my models I played around with did not perform well no matter how I tweaked the parameters, which leads me to believe I needed to reformat my data or just use different data all together.  There was no detectable seasonality to the opinions of movie critics for certain genres of movies.
