 # Volleyball Players Analysis (VNL 2023)

This repository contains an exploratory data analysis (EDA) of volleyball player statistics from the **2023 Volleyball Nations League (VNL)**. The analysis is performed in a Jupyter Notebook (`Analysis.ipynb`) using Python and popular data science libraries.

## Dataset

The dataset `VNL2023.csv` includes player-level statistics for the 2023 VNL tournament. Key columns:

- **Player** – player name  
- **Country** – nationality  
- **Age** – age of the player  
- **Attack** – average attack points per set  
- **Block** – average block points per set  
- **Serve** – average serve points per set  
- **Set** – average set assists per set  
- **Dig** – average digs per set  
- **Receive** – average reception efficiency  
- **Position** – playing position (OH, OP, MB, S, L, etc.)

## Analysis & Visualizations

The notebook performs the following steps:

1. **Data loading & inspection**  
   - Load CSV, check for duplicates & missing values.

2. **Correlation analysis**  
   - Correlation matrix and heatmap of numerical features.

3. **Player position distribution**  
   - Bar chart and pie chart showing frequency of each position.

4. **Attack performance by country**  
   - Mean attack score per country (bar chart) – top countries highlighted.

5. **Serve performance by age**  
   - Mean serve score grouped by age (horizontal bar chart).

6. **Attack by country and position**  
   - Grouped DataFrame and analysis of attack means by `(Country, Position)`.

7. **Digs by country**  
   - Bar chart of mean digs per country.

8. **Block vs Receive relationship**  
   - Scatter plot to explore correlation between block and receive skills.

9. **Serve distribution**  
   - Boxplot of serve scores to detect outliers and spread.

10. **Age distribution**  
    - Histogram of player ages.

## Key Findings (Summary)

- **Attack leaders**: France, Japan, and Cuba show the highest average attack scores.
- **Serve by age**: The highest average serve scores are found in players aged 31, 20, and 21.
- **Position distribution**: Outside Hitters (OH) and Opposite (OP) are the most frequent positions.
- **Digs**: Countries like Japan and France also excel in defensive digs.
- **Correlations**: Attack and serve are positively correlated; block and receive show a weaker negative correlation.
- **Age spread**: Majority of players are between 22 and 30 years old.

## Requirements

The notebook uses the following Python libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

Install dependencies with:

```bash
pip install pandas numpy matplotlib seaborn
