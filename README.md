# Group_Project_1
Happiness Explained: An Exploration of Happiness Scores

Core Message: 

According the the World Happiness Report there are several subjective well-being measures (SWB) that can be used to measure happiness. Our main objective was to explore, the measures of subjective well-being to determine which ones had the most influence on happiness. We also to set out to examine the different factors to determine the correlation of each of these with overall happiness.


Research Questions:

1. Which countries had the lowest happiness score? highest happiness score? (data from 2017, 2018, and 2019). 
2. Which of the measures of SWB (i.e., social support, healthy life expectancy, generosity, freedom to make life choices, GDP per capita, and perception of corruption) are most highly correlated with a higher happiness score?
3. Which of these measures are most likely to influence the happiness score? 

Findings: 

1. Over the past three years, which countries had the lowest happiness score? highest happiness score? 

Answer: The average over the last three years shows Finland as having the happiest overall score. Rounding out the top five is Denmark, Norway, Switzerland, and Iceland. Inversely, the lowest happiness scores fall on South Sudan, Afghanistan, and Central African Republic. 

Plots: Average Sorted DF-Top 10 (img 1.1) and Lowest 10 (img 1.2) and Stacked Bar Charts (img 1.3 and img 1.4)

2. Which of the measures of SWB (i.e., social support, healthy life expectancy, generosity, freedom to make life choices, GDP per capita, and perception of corruption) are most highly correlated with a higher happiness score?

*Pearson's correlation coefficient (r) is a measure of the strength of the association between the two variables.

Answer: We found that GDP had a highest correlation  (at .807), Healthy Life Expectancy a close second (at 0.798), and Social Support was third (at 0.774)

Plots: Pearson Comparison Chart (img 3.1). Other visualizations to show correlation and outliers (imgs 3.2, 3.3)

3.Which of these measures have the most influence on the happiness score? 

Answer: 
We ran a linear regression between each SWB and Happines. We found that GDP per capita, Social Support, Health Life Expectancy, Freedom to make Life Choice, and Perception of Corruption had a significant linear relationship with the Happiness score, except for generosity. 

We utilized a multiple linear regression model to examine influence. We found evidence to support our hypothesis. For each unit increase in the absence of corruption, the happiness score increases by 1.13% - holding all other variables constant.

The four most influential measures of SWB are Freedom to Make Life Choices, Perceived Absence of Corruption, Healthy Life Expectance, Social Support have the most influence on the Happiness score.

Although, one would assume that more developed nations would have a higher perceived happiness score, GDP per Capita is not as effective at predicting a higher happiness score, so less developed countries would still be considered Happier.

Previous studies suggest that economic expansion does not lead to increased happiness at the country level (Easterlin, 1974, Shin, 1980, Rose, 2020).

Plots: Scatterplots of SWBs linear relationship w/Happiness  (4.1 and 4.2), Linear regression results of all SWBs (img 4.3), Multiple Linear Regression with Generosity Output (img 4.4), Multiple Linear Regression Output without Generosity (img 4.5).
