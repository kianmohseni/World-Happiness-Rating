# Project Overview

This project explores how social and economic indicators influence happiness across 157 countries. The dataset includes 12 key metrics such as GDP per Capita, Family, Life Expectancy, Freedom, Government Trust, Generosity, and a Dystopia Residual. The latter represents unexplained variations in happiness that are not accounted for by the other variables.

The goal of this project is to identify correlations between these factors and to uncover insights about what contributes most significantly to the happiness and well-being of a country's population.

# Dataset

The dataset consists of:

- 12 key indicators, including both measurable economic metrics and social factors.
- 157 countries, each scored on different scales (no standard units).
  
Key variables:

- GDP per Capita: Economic productivity.
- Family: Social support structures.
- Life Expectancy: Health and longevity.
- Freedom: Perceived ability to make life choices.
- Government Trust: Confidence in public institutions.
- Generosity: Cultural inclination towards altruism.
- Dystopia Residual: Unexplained variations in happiness.

# Tools and Libraries

This project utilizes the following Python libraries:

- Pandas: Data manipulation and cleaning.
- Matplotlib: Visualization of trends and distributions.
- Seaborn: Advanced statistical visualizations.

# Methodology

1. Data Preprocessing:

  - Cleaning and preparing the dataset for analysis.
  - Handling missing values and formatting inconsistencies.

2. Exploratory Data Analysis (EDA):

  - Summarization of the dataset.
  - Visual exploration of trends, correlations, and distributions.

3. Insights and Conclusions:

  - Identifying the strongest contributors to happiness.
  - Highlighting patterns across countries and regions.

# Visualizations

The project includes visualizations such as:

- Heatmaps of correlations between variables.
- Bar plots and histograms to show distributions of key metrics.
- Scatterplots to illustrate relationships between happiness and specific factors.

Example code snippet:

```ruby
# Correlation heatmap
sns.heatmap(df.corr(), annot=True, cmap='coolwarm')
plt.title('Correlation Between Happiness Indicators')
plt.show()

# Scatterplot of GDP per Capita vs Happiness Score
sns.scatterplot(x='GDP per Capita', y='Happiness Score', data=df)
plt.xlabel('GDP per Capita')
plt.ylabel('Happiness Score')
plt.title('GDP vs Happiness')
plt.show()
```

# Findings

1. The dataset was largely complete, with minimal missing values detected:

2. The strongest correlations with happiness included GDP per Capita and Family metrics, as visualized in the heatmap:

3. Freedom and Government Trust also showed moderate correlations, indicating both economic and social factors play roles in overall happiness.

# Results

Through this analysis, the project highlights how specific indicators—both economic and social—interact to influence happiness scores. These findings can inform policy decisions and further research into well-being.

