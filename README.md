# NBA Home Court Advantage Analysis

This project investigates the existence of home court advantage in NBA games. We analyze historical data from NBA games to determine whether teams playing at their home court have a statistically significant advantage over their opponents.

## Project Authors
- Radman Avakoli
- Yao(Chengyuan) Yao
- Rehan Mondal
- Parham Alijani

## Introduction
Home court advantage in sports typically suggests a team has a higher chance of winning due to familiarity with the venue, support from local fans, or reduced travel fatigue. Our analysis aims to quantify this advantage in the NBA by examining game results from the 2004 to 2020 seasons, focusing on whether teams win more frequently at home compared to playing away.

## Data Source
The dataset used in this project is sourced from the NBA statistics website, covering detailed game results from 2004 to 2020. The dataset includes over 25,000 games with attributes such as game dates, team IDs, points scored, and home/away status.

- **Data Access**: The data can be accessed directly via this [Kaggle link](https://www.kaggle.com/datasets/nathanlauga/nba-games).

## Installation
To run this analysis, you need to install several R packages. The required libraries are listed below, and you can install them using R commands:

```r
install.packages("tidyverse")
install.packages("infer")
install.packages("rsample")
install.packages("repr")
