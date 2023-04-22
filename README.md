# SC1015 MINI PROJECT - NBA GAMES DATA

## Introduction
Through this mini project, we aim to analyse past NBA Games data to determine which variable is the best in predicting whether the home team wins, with the dataset taken from Kaggle, spanning all the games from 2003 to December 2022. Our aim is to provide valuable insights for NBA teams to better improve their games when they have the home team advantage. 

## Team Members

|Name               |Email                                                 |
|-------------------|------------------------------------------------------|
|Ang Yun Zane       |[angy0089@e.ntu.edu.sg](mailto:angy0089@e.ntu.edu.sg) |
|Arjun Kumaresh     |[ARJUN019@e.ntu.edu.sg](mailto:ARJUN019@e.ntu.edu.sg) |
|Adrian Chua Pin Yu |[ad0001yu@e.ntu.edu.sg](mailto:ad0001yu@e.ntu.edu.sg) |

## Problem Formulation
 - Which variable 
   - FG PCT HOME
   - FT PCT HOME 
   - AST HOME 
   - REB HOME
 
 is the best in predicting whether the home team will win?
 
 ## Flow of the Project
 
- ### Exploratory Data Analysis
  We first begin by doing some exploratory data anaylsis on the dataset to determine what we were working with. We included several plots of each variable columns that we were interested in for some initial insights to our problem statement.

- ### Classification Tree Fittings
  In our project, our team explored the use of
  1. Decision Tree Classifier
  2. Logistic Regression Classifier
  3. Random Forest Classifier
  4. Nearest Neighbour Classifier

  For each of the variables columns we were interested in, we fitted them into all of the classification tree models to determine which model is the best for our project case. From there, we made our analysis to determine which is the better variable to answer our problem statement.

## Conclusion / Final analysis
- Nearest Neighbour classifier is ultimately not used in our final analysis as our team deemed the logic behind the classifier not so appropriate for our project problem statement, given also that the classification accuracy is the lowest among the four models used across all four variable columns.
- After analysis of all the models with each of the column variables, it seems that **FG PCT HOME** is the better variable among the four variable to predict whether the home team win, given the higher classification accuracy across all the models used. 
- All models seems to be similarly accurate as the results are similar for the models for the respective variable columns.
- However, the three models could be further improved upon by adding defensive statistics such as Opposing field goal percentage as well as other advanced statistics such as Box Plus Minus, Effective Field Goal Percentage, which could better help identify skill sets that could better help a team win.

## What did we learn?
- Collaborating on github for coding projects
- Use of other classification trees other than decision tree classifier, such as logistic regression and nearest neighbour classifications
- Experience of the entire data science pipeline, starting from a dataset, to problem formulation to research and finally a conclusion
- Limitations of some models and data and how it can be further improved.

## Team member's contribution

- Ang Yun Zane -> Downloading and importing of data, cleaning of Dataset, Classifications trees Fitting
- Arjun Kumaresh -> Core Analysis of results, Script writing, Video filming
- Adrian Chua Pin Yu -> Exploratory Data Analysis, Core Analysis of results, Script writing

While each of us were assigned our individual roles within the project, we made sure to keep each other updated on the progress of the project and helped one another out whenever necessary.


## References 
- Nathan, L. (2020, December 21). NBA games data [Data Scientists]. Kaggle. https://www.kaggle.com/datasets/nathanlauga/nba-games
- Supervised learning. (n.d.). Scikit Learn. Retrieved 22 April 2023, from https://scikit-learn/stable/supervised_learning.html
- Anaconda (2022.10). (2022). [Python]. Anaconda, Inc. http://anaconda.com/
- Bujokas, E. (2022, June 2). Feature Importance in Decision Trees. Medium. https://towardsdatascience.com/feature-importance-in-decision-trees-e9450120b445
- Cournapeau, D. (2023). Scikit Learn (1.2.2) [Python; Python]. https://scikit-learn.org/
- DATAtab (Director). (2023, January 8). Logistic Regression [Simply explained]. https://www.youtube.com/watch?v=C5268D9t9Ak
- Hunter, J. (2023). Matplotlib (3.7.1) [Python]. https://matplotlib.org/
- McKinney, W. (2023). Pandas (1.5.3) [Python; Python]. https://pandas.pydata.org/
- Nathan, L. (2020, December 21). NBA games data [Data Scientists]. Kaggle. https://www.kaggle.com/datasets/nathanlauga/nba-games
- Oliphant, T. (2023). Numpy (1.24.2) [Python; Python]. https://numpy.org/
- R, S. E. (2021, June 17). Understand Random Forest Algorithms With Examples (Updated 2023). Analytics Vidhya. https://www.analyticsvidhya.com/blog/2021/06/-understanding-random-forest/
- Waskom., M. (2022). Seaborn (0.12.2) [Python; Python]. https://seaborn.pydata.org/
- What is a Decision Tree | IBM. (n.d.). Retrieved 22 April 2023, from https://www.ibm.com/topics/decision-trees
- xrotwang & xflr6. (2022). Graphviz [Python]. https://graphviz.readthedocs.io/en/stable/
- Yiu, T. (2021, September 29). Understanding Random Forest. Medium. https://towardsdatascience.com/understanding-random-forest-58381e0602d2
- Jupyter notebooks from NTU Coursesite (M2, M4)
