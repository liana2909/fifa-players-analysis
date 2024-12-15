# FIFA Players Analysis

## How to Use
1. Clone this repository.
2. Place the `fifa_players.csv` file in the root directory.
3. Run the `Project.ipynb` notebook to explore the analysis and models.

This project is a comprehensive analysis of FIFA player data, designed to showcase data manipulation, visualization, and modeling skills. The dataset (`fifa_players.csv`) contains rich information about players, including ratings, salaries, positions, and performance metrics.

## How to Use
1. Clone this repository.
2. Place the `fifa_players.csv` file in the root directory.
3. Run the `Project.ipynb` notebook to explore the analysis and models.

## Objectives
The project is divided into several sections, each focusing on a different aspect of data analysis and modeling. Here's a breakdown of the tasks:

### Analytical Block
1. Identify the top 100 players with the highest ratings.
2. Compare the top 100 players with the highest salaries to those with the highest ratings.
3. List the top 30 goalkeepers with the highest ratings.
4. Determine the top 30 teams with the highest average player ratings.
5. Find the top 30 teams with the fastest players on average.
6. Highlight leagues with the best dribblers.
7. Identify the top 30 teams with the highest-rated squads, considering specific positional requirements (e.g., 1 goalkeeper, 4 defenders, etc.).

### Visualization Block
1. Create a distribution chart of players by age across positions.
2. Build a distribution chart of players' ratings across positions.
3. Visualize the distribution of nationalities based on player ratings.

### Analytical Thinking Block
1. Develop a custom metric to evaluate penalty-takers.
2. Create a custom metric for goalkeepers specialized in saving penalties.
3. Analyze whether clubs have significantly better penalty-takers compared to their goalkeepers, and vice versa.
4. Rank the top 10 clubs with the best penalty-takers.
5. Rank the top 10 clubs with the best goalkeepers.

### Business Insights Block
Propose business applications for the data, such as:
- Identifying high-potential players for scouting.
- Assisting clubs in forming balanced squads.
- Analyzing league dynamics for media or sponsorship opportunities.

### Data Science Block
1. Perform exploratory data analysis (EDA) to identify issues (e.g., mixed attributes between goalkeepers and field players).
2. Engineer features to prepare the dataset for modeling.
3. Select the most relevant features using appropriate algorithms.

### Modeling Block
1. Build a classification model to predict player positions based on performance metrics.
2. Experiment with different algorithms and evaluate their performance with and without specific variables (`club_position`, `nation_position`).
3. Optimize for metrics beyond accuracy, considering precision, recall, or F1-score.

## Methodology
- **Data Manipulation:** Leveraged `pandas` for grouping, filtering, and aggregating data. SQL queries were used for more complex operations.
- **Visualization:** Created insightful charts using `matplotlib` and `seaborn`.
- **Modeling:** Applied machine learning techniques (e.g., Random Forest, Logistic Regression) to predict player positions and uncover patterns in the data.

## Results
The analysis provided actionable insights, including:
- A clear understanding of the relationship between salaries and player performance.
- Identification of top-performing players, teams, and leagues based on various metrics.
- Custom metrics to evaluate player specialization, such as penalty-taking and goalkeeping skills.

## Tools Used
- **Python Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`
- **Database Management:** SQLite for SQL-based queries
- **Development Environment:** Jupyter Notebook