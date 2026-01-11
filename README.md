# FIFA World Cup Prediction & Simulation

This project builds a probabilistic framework to predict FIFA World Cup match outcomes and tournament winners using historical international football data.

## Overview
- Built Elo ratings with tournament-aware weighting
- Trained an XGBoost multi-class model for match outcome prediction
- Modeled goals using Poisson regression
- Combined models into a hybrid simulation framework
- Ran Monte Carlo simulations to estimate WC 2026 win probabilities

## Data
- International football match results (1872–2024)
- Evaluated on FIFA World Cups 2018 and 2022

## Models Used
- Elo Rating System (custom implementation)
- XGBoost (multi-class classification)
- Poisson Regression (goal modeling)
- Monte Carlo Simulation (tournament forecasting)

## Key Results
- Evaluated models using accuracy and log loss
- Simulated future tournament scenarios under uncertainty
- Generated team-level probabilities for advancing stages and winning the tournament

## Limitations
- Squad selection and injuries not modeled
- WC 2026 groups are randomly generated placeholders
- No betting market calibration

## Notebook
📓 Kaggle Notebook:  
https://www.kaggle.com/code/saptarshisadhukhan/fifa-worldcup-prediction
