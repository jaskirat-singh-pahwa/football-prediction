# football-prediction

## Problem Statement
Goal is to build a model to predict the outcome of a football match, given data for the past 9 years. All the football matches from 2009 to 2017 are covered in the dataset.

Based on the dataset provided, goal should be to come up with an optimal solution to predict if a Home Team would win or lose or draw a game (column name FTR) for the year of 2017-2018.
We will try to compare multiple approaches and choose the one that performs the best.

The problem statement is intended to be fun and learning. The current dataset is downloaded from http://www.football-data.co.uk/

We can enrich the dataset by using other publicly available European football league datasets, 
http://www.football-data.co.uk/ or 
http://football-data.mx-api.enetscores.com/


Column Details:

  Name        Description
  HomeTeam    Home Team
  AwayTeam    Away Team
  FTR         Full-Time Result (H=Home Win, D=Draw, A=Away Win) HTHG Half Time Home Team Goals
  HTAG        Half Time Away Team Goals
  HS          Home Team Shots
  AS          Away Team Shots
  HST         Home Team Shots on Target
  AST         Away Team Shots on Target
  AC          Away Team Corners
  HF          Home Team Fouls Committed
  AF          Away Team Fouls Committed
  HC          Home Team Corners
  HY          Home Team Yellow Cards
  AY          Away Team Yellow Cards
  HR          Home Team Red Cards
  AR          Away Team Red Cards
  Date        On which day the match was played
  league      Under which league the match was played


Key things to focus:
  1.) Understand all the variables in the data.
  2.) Follow best practices to make sure the model is robust.
  3.) Think about how the model will evolve, over a period of time, in production, when more data is available.
  4.) Code should be readable.
  5.) Think about the biases that can be there in the data.
