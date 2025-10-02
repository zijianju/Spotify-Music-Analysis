# Spotify Song Popularity & Genre Analysis

## Project Overview
This project analyzes a dataset of **52,000 Spotify tracks** to explore what makes music popular and how songs group together based on audio features. Using Python (pandas, scikit-learn), I combined **hypothesis testing**, **regression**, and **PCA + clustering** to uncover insights into song popularity, musical attributes, and genre alignment.

The project was originally developed as a Data Science capstone, and later polished for portfolio presentation.


## Dataset
- **Source:** Provided as part of the course (52k Spotify tracks).  
- **Features analyzed (10 audio features):**
  - Duration, Danceability, Energy, Loudness, Speechiness, Acousticness, Instrumentalness, Liveness, Valence, Tempo  
- **Targets used:**
  - Popularity (0–100 scale), Mode (major/minor), Track genre  


## Methods
- **EDA:** Distribution plots, correlation heatmaps, boxplots  
- **Hypothesis Testing:** t-test, Mann–Whitney U for explicit vs non-explicit and major vs minor  
- **Regression:** Linear regression (single and multiple features) predicting popularity (R², RMSE)  
- **PCA:** Dimensionality reduction (retain ~95% variance)  
- **KMeans Clustering:** Elbow method for optimal k (~4 clusters)  
- **Classification:** Logistic regression for Mode prediction, Decision Tree for genre classification  
