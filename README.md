# Predicting a Song's Popularity with Regression and Classification Analysis

**Data Scientists** - Nasrin Khansari & Max Tingle 

**Flatiron School** - Module 4 Project


## Project Goals

Our analysis examines Spotify track popularity scores by track features. We collected data from Spotify's Web API that includes 637,265 tracks and their associated duration, single or album status, key, mode (major/minor), speechiness, acousticness, instrumentalness, liveness, valence. *(Here are links to examine the [audio features](https://developer.spotify.com/documentation/web-api/reference/tracks/get-several-audio-features/) and [popularity score](https://developer.spotify.com/documentation/web-api/reference/tracks/get-track/).)*

**Research Question:** Using the CRISP-DM framework, we asked the research question: "Do the track features (independent variables) predict track popularity score (dependent variable)?" 

**Linear Regression:** We first built and tested a linear regression model. Our data failed to meet the assumption of normality, and we also observed imbalances in the data, specifically, 93% of the data were for not-popular tracks and only 7% were popular tracks.

**Logistic Regression:** Next we fitted a logistic regression model and re-tested the model with balanced data. We observed that the true positive rate remained low even when fitting balanced data. Therefore concluding that our logistic regression model was not a good predictor of track popularity.

**Random Forrest Classification:** We moved on to try Random Forrest classification, but observed similar results as we did for logistic regression. The true positive rate was still low, and the models had high accuracy at predicting true negatives (tracks that were not popular), but not for predicting true positives (tracks that were popular).

**Finding:** Based on our analysis, we cannot say that the independent variables (duration, single or album status, key, mode (major/minor), speechiness, acousticness, instrumentalness, liveness, valence) predict track popularity.


## Repository Files

1. README.md
2. Modeling Spotify Track Popularity Presentation (PDF)
3. Technical Notebook (Jupyter Notebook)
4. Images (Folder)
5. *Data csv file available upon request (file size was too large for GitHub).*

## Responsibilities

- Data Collection & Cleaning - Nasrin & Max
- Statistical Modeling - Nasrin & Max
- Machine Learning Algorithms - Nasrin & Max
- Technical Notebook - Nasrin & Max
- Presentation - Nasrin & Max

