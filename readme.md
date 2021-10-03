# Analysis TMDB Movie Dataset
## by Omar Alomeari


## Dataset

This project is part of Udacity Nanodegree certification.

The data is a clean version of the TMDB movie dataset at Kaggle provide by Udacity, you can find the origin [here](https://www.kaggle.com/tmdb/tmdb-movie-metadata).

This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue. 
- Certain columns, like ‘cast’ and ‘genres’, contain multiple values separated by pipe (|) characters.
- There are some odd characters in the ‘cast’ column. Don’t worry about cleaning them. You can leave them as is.
- The final two columns ending with “_adj” show the budget and revenue of the associated movie in terms of 2010 dollars, accounting for inflation over time.

The goal is to investigate the data and answer some interesting questions.

## Summary of Findings

I found that the average run reached its peaks in 1965 then start to decrease over time, The most popular movie genre varies from year to year but the frequent one is drama,  the popularity of movies don't associate with the rating, a high rating doesn’t indicate higher budget and movies with high budget receive a high revenue.

## Key Insights for Presentation

I focus to introduce each categorical variable one by one. To start,  I used the line plot to plot the average run by the years, histogram to plot distribution of rating, scatterplot to see if there is any relation between popularity and rating, and bar plot for comparing.  
