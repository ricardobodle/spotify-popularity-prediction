# Spotify Popularity Prediction

## Overview
This project predicts whether a song will be "popular" or not based on its audio features (like danceability, loudness, and tempo). I trained a **Random Forest Classifier** on a dataset of Spotify tracks to classify songs as "Hits" or "Non-Hits."

## Key Results
* **Model Accuracy:** 87.55%
* **Top Predictor:** Loudness was the most important feature in determining popularity.

## The Process
1.  **Data Cleaning:** Handled missing values and defined a "Popular" threshold (Popularity > 50).
2.  **Feature Selection:** Focused on audio attributes like `loudness`, `acousticness`, and `danceability`.
3.  **Modeling:** Used a Random Forest Classifier (n_estimators=100).
4.  **Evaluation:** Achieved ~88% accuracy and visualized feature importance.

## Technologies Used
* Python
* Pandas (Data Manipulation)
* Scikit-Learn (Machine Learning)
* Seaborn/Matplotlib (Visualization)

## Installation
1. Clone the repo.
2. Install requirements: `pip install pandas sklearn seaborn matplotlib`
3. Run the notebook `notebook.ipynb`.