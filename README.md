# Life Expectancy Project
Project of analyzing a Life Expectancy dataset from kaggle.

Source: [Life Expectancy Trends for Males and Females](https://www.kaggle.com/datasets/saimondahal/life-expectancy-trends-for-males-and-females)

“Data Page: GDP per capita”, part of the following publication: Max Roser, Pablo Arriagada, Joe Hasell, Hannah Ritchie and Esteban Ortiz-Ospina (2023) - “Economic Growth”. Data adapted from Bolt and van Zanden. Retrieved from https://ourworldindata.org/grapher/maddison-data-gdp-per-capita-in-2011us-slopechart [online resource]


> [!NOTE]
> Data is merged with a GDP data, it may not have data from every countries.

## Overview 
This project aims to explore and analyze factors influencing life expectancy across the globe. Using robust data analysis and visualization techniques, the project seeks to uncover key insights into how various socio-economic factors contribute to life expectancy.

## Objectives
To identify and analyze the primary factors that impact life expectancy.
To understand the relationships between these factors and life expectancy.
To provide data-driven insights that can inform health policy and resource allocation.
Data Source
The analysis is based on a comprehensive dataset that includes variables like GDP, education, employment rates, health expenditure, and more, covering multiple countries over several years.

## Methodology
**Data Loading:** Importing the dataset using pandas and understanding its structure.

**Data Cleaning:** Handling missing values, anomalies, and data inconsistencies.

**Exploratory Data Analysis:** Employing seaborn and matplotlib for visual exploration of data.

**Feature Engineering:** Creating new features that better represent the underlying patterns in the data.

**Statistical Analysis:** Applying statistical methods to derive deeper insights from the data.

**Data Visualization:** Utilizing plotly and seaborn for dynamic and static visual representations.

## Key Findings
1. **Data Overview:** Initial data exploration was conducted using data.head(), data.describe(), and data.info() commands. These provided a preliminary understanding of the dataset's structure, contents, and statistical summaries.
2. **Descriptive Statistics Visualization:** Histograms and boxplots were created to visualize the distribution of average life expectancy. These plots highlighted the central tendency and variability in life expectancy data.
3. **Life Expectancy Trends Over Time:** Line plots were used to depict trends in life expectancy over the years for different genders. This revealed how life expectancy has changed globally over time.
4. **Comparative Analysis:** A line plot was created to compare the life expectancy of the top 15 countries from 1950 to 2018. This analysis provided insights into how different countries fare in terms of life expectancy.
5. **Correlation Analysis:** A heatmap of the correlation matrix was generated to understand the relationships between various factors such as gender, population, average life expectancy, and GDP per capita.
6. **Pairplot for Multiple Variables:** A pairplot was used to explore the relationships between female and male life expectancy, population, average life expectancy, and GDP per capita.
7. **GDP and Life Expectancy Correlation:** Line and scatter plots were created to analyze the progression of GDP per capita over time and its relation to life expectancy. This helped in understanding the impact of economic factors on health outcomes.
8. **GDP vs Life Expectancy Visualization:** A scatter plot was used to visualize the relationship between GDP and average life expectancy, highlighting how economic prosperity correlates with longevity.

## Tools & Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly

## Future Work
- Plans to make a machine learning model of this data (Regression Analysis, Clustering, etc..)

## Contact Information
Name: Azhar Rahadian
LinkedIn/GitHub: Kunkoala
