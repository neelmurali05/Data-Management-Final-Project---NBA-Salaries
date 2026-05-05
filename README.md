# Data-Management-Final-Project---NBA-Salaries
NBA salary data compared with player's PER, also known as player effeciency rating, to determine if certain players are really worth paying all that much too, and if there are slightly lower caliber players that can do the job just as well for less money.

# NBA Salary and Player Efficiency Rating Analysis

## Project Overview

This project analyzes the relationship between NBA player salary and player performance during the 2022–23 season. The main focus is Player Efficiency Rating (PER), an advanced basketball statistic that summarizes a player's per-minute production.

The goal of this project is to determine whether players with higher PER values tend to earn higher salaries and whether PER alone can be used to predict NBA salary.

## Research Question

How strongly does Player Efficiency Rating correlate with NBA player salary during the 2022–23 NBA season?

## Dataset

The dataset includes NBA player statistics, salary information, and ESPN Hollinger Player Efficiency Rating data for the 2022–23 season.

Important columns include:

- Player
- Team
- Position
- Age
- Salary
- Player Efficiency Rating
- Points
- Rebounds
- Assists
- Steals
- Blocks
- Turnovers

## Methods

The project uses:

- Data cleaning with pandas
- Salary conversion from string values to numeric values
- Correlation analysis between PER and salary
- Linear regression modeling
- Model evaluation using MAE, MSE, RMSE, and R-squared
- Key findings identifying players paid more or less than the model prediction

## Evaluation Metrics

The model is evaluated using:

- Mean Absolute Error
- Mean Squared Error
- Root Mean Squared Error
- R-squared Score

## Key Findings

The analysis tests whether PER has a meaningful relationship with salary. The model also identifies players who earned more than the PER-based prediction and players who earned less than the PER-based prediction.

## How to Run

1. Clone the repository.
2. Install dependencies:

```bash
pip install -r requirements.txt
