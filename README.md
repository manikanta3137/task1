# task1
# FIFA World Cup 2026 – Data Cleaning & Visualization Project

## Overview

This project focuses on cleaning, processing, and visualizing the FIFA World Cup 2026 Fixtures dataset using Python. The goal is to demonstrate data preprocessing, exploratory data analysis (EDA), and data storytelling through meaningful visualizations.

## Dataset Information

* Total Matches: 104
* Total Features: 15
* File: `wc_2026_fixtures.csv`

### Dataset Columns

* group
* stage
* team1
* team2
* venue
* city
* country
* date
* kickoff_et
* team1_confederation
* team1_fifa_rank
* team1_coach
* team2_confederation
* team2_fifa_rank
* team2_coach

## Project Objectives

* Identify and handle missing values
* Detect and remove duplicate records
* Convert and standardize data types
* Explore tournament structure and hosting distribution
* Create visualizations to reveal insights
* Practice data storytelling using sports analytics

## Data Cleaning Performed

### Missing Values

The dataset contains missing values in:

* group
* team1_confederation
* team1_fifa_rank
* team1_coach
* team2_confederation
* team2_fifa_rank
* team2_coach

These missing values correspond mainly to knockout-stage fixtures where participating teams had not yet been determined.

### Data Processing

* Converted date column to datetime format
* Checked for duplicate records
* Verified data consistency
* Filled missing group values with "Knockout" where appropriate

## Exploratory Data Analysis

The following analyses were performed:

1. Match distribution by tournament stage
2. Match distribution by host country
3. Match distribution by city
4. Venue usage analysis
5. FIFA ranking distribution
6. Confederation representation analysis

## Visualizations

### Matches by Stage

Shows the number of matches in each tournament stage.

### Matches by Host Country

Compares how matches are distributed across host nations.

### Matches by City

Highlights cities hosting the most matches.

### Venue Analysis

Identifies stadiums hosting the highest number of fixtures.

### FIFA Ranking Distribution

Examines the ranking spread of participating teams.

### Confederation Representation

Shows representation of different football confederations.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Key Insights

* Group Stage contains the largest number of matches.
* The United States hosts the majority of fixtures.
* Multiple cities and venues play significant roles in tournament organization.
* UEFA and other major confederations have strong representation.
* Knockout-stage matches contain placeholder teams, resulting in missing ranking and coach information.

## Project Structure

```text
FIFA-WorldCup-2026-Data-Analysis/
│
├── wc_2026_fixtures.csv
├── FIFA_WorldCup_2026_EDA.ipynb
├── README.md
│
├── visualizations/
│   ├── matches_by_stage.png
│   ├── host_countries.png
│   ├── host_cities.png
│   ├── venue_analysis.png
│   ├── ranking_distribution.png
│   └── confederation_distribution.png
```

## Learning Outcomes

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Visualization
* Sports Data Analytics
* Data Storytelling
* GitHub Project Documentation

## Author

Sai Manikanta
AIML Student
