# EPL-Match-Prediction-25-26
A machine learning project predicting Premier League 25/26 results — built with Random Forest models, Elo-based team strength ratings, and rolling form features. Covers outcome classification and exact score prediction with a Gradio interface.

## Models
- **Outcome Classifier** — Predicts Win/Draw/Loss (Random Forest)
- **Score Predictor** — Predicts exact goals (Random Forest Regressor)

## Features Used
- Team Elo ratings with home advantage adjustment
- Rolling 5-game attack/defense form

## Setup
pip install -r requirements.txt

## Data
Place `EPL_2526.csv` in the `data/` folder.
Source: [football-data.co.uk] (https://www.football-data.co.uk)

## Results
- Outcome accuracy: ~XX%
- Goals MAE: ~XX goals
