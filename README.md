# ICC Cricket World Cup CWC23 All Innings Scenario

## Introduction

Welcome to the final project by Suthi de Silva for CSC 285, completed on 18th January 2024. This project delves into the fascinating world of cricket, a sport beloved by 2.5 billion fans worldwide. Cricket is renowned for its rich history, strategic gameplay, and passionate fan base. In this project, we explore the manipulation, cleanup, and visualization of data from the ICC Cricket World Cup using RStudio.

## Research Question

The primary research question addressed in this project is: How to manipulate, clean up, and better visualize a Cricket World Cup .csv data set with RStudio?

## Dataset Overview

The dataset used in this project contains valuable information about matches, teams, players, and various performance metrics. Key fields include:
- Team
- Player
- Batting or bowling indicator
- Balls bowled or faced
- Runs scored or conceded
- Number of wickets taken
- Wicket probability
- Runs per ball
- Opposition team
- Ground
- Start date

## Loading Data

The project begins with loading the dataset into RStudio and examining the first 20 rows to understand the structure and contents of the data.

## Cleaning Up Data

The data cleaning process involves removing columns with "NA" values and adding an ID column for each row to uniquely identify performances by players.

## Data Visualization

### Favorite and Least Favorite Teams' Performance
- Scatter plots show balls bowled or faced vs wicket probability for each team, providing insights into the performance of favorite teams.

### Best Stadiums for Batting and Bowling
- Scatter plots illustrate the relationship between balls faced or bowled and runs scored or wicket probability, highlighting the best stadiums for batting and bowling performances.

### Teams' Bowling and Batting Performances with Each Other
- Heatmaps and scatter plots visualize teams' bowling and batting performances against opponents, providing insights into performance trends across different matchups.

### Stadiums with Highest Run and Wicket Probability Contributions
- Pie charts display run and wicket probability contributions for each stadium, highlighting the top-performing venues.

## Conclusion

After cleaning up the dataset and visualizing the data, several insights are derived:
- Australia and South Africa had the best batting performances.
- India excelled in bowling, particularly against Sri Lanka.
- Dharamsala stadium emerged as the best for bowling, while Delhi stadium was optimal for batting.
- Glenn Maxwell (Australia) and Dilshan Madhushanka (Sri Lanka) stood out as top performers in batting and bowling, respectively.

## Citation

- Dataset Source: [Kaggle](https://www.kaggle.com/datasets/jdaustralia/icc-cwc23-all-innings-cleaned)
- Data Reference: [ESPN Cric Info Website](https://www.espncricinfo.com/records/tournament/icc-cricket-world-cup-2023-24-15338)
