# Welcome to dreamTeam repository

## About

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on datas from [NBA.com](https://www.nba.com/stats/players/).

## For detailed walkthrough, please view the source code in order from:
1. Problem Definition
- [README.md](https://github.com/CSA100/nba-dsai/blob/master/README.md)


2. Data Collection and Preperation
- [WebScraping.ipynb](https://github.com/CSA100/nba-dsai/blob/master/Web%20Scrapping.ipynb)
- [Features.md](https://github.com/CSA100/nba-dsai/blob/master/Features.md)
- [FeatureSelection.ipynb](https://github.com/CSA100/nba-dsai/blob/master/FeatureSelection.ipynb)
The notebokks in this portion is used to extract data from NBA.com to form our datasets. For data extraction, we utilised selenium and beautifulSoup to scrape the data from NBA.com. After extracting the data, the feature selection notebook sees us plot correlation matrixes and graphs to identify features that have high correlation to drop. As these features have high correlation, dropping one of them would help us increase the accuracy of our model

3. Exploratory Data Analysis / Visualisation
- [FeatureSelection.ipynb](https://github.com/CSA100/nba-dsai/blob/master/FeatureSelection.ipynb)
- [PCA.ipynb](https://github.com/CSA100/nba-dsai/blob/master/PCA.ipynb)
- [EDA.ipynb](https://github.com/CSA100/nba-dsai/blob/master/EDA.ipynb)
The FeatureSelection Notebook also serves as a form of data analysis and visualisation as we see the relationship between the various stats. After dropping some features in FeatureSelection, we carried out Principal Component Analysis (PCA) to reduce the dimensions of the data further. After doing the PCA, 


4. Use of Machine Learning
- [hierarchicalClustering.ipynb](https://github.com/CSA100/nba-dsai/blob/master/hierarchicalClustering.ipynb)
- [K-MeansClustering.ipynb](https://github.com/CSA100/nba-dsai/blob/master/K-MeansClustering.ipynb)
After carrying out exploratory data analysis/ visualisation, we went on to use machine learning models specifically clustering 


5. Final Insights
- [clusteringEDA.ipynb](https://github.com/CSA100/nba-dsai/blob/master/clusteringEDA.ipynb)

## Contributors
- @CSA100 (Anand Chaanan Singh) - Exploratory Data Analysis/ Visualization
- @zonpig (Bryan Lim Kai Wen) - Data Collection and Preparation
- @crustyapples (Advait Bharat Deshpande) - Use of Machine Learning

## Background
With the evolution of the sport, players have greater access to training facilities and have been able to build stronger capabilities to improve their play.

This has made it increasingly difficult for managers to predict the outcomes for the teams that they draft. They are no longer able to predict their teams’ success based on traditional methods, such as their height, strength, shooting abilities etc. 

The most successful teams are no longer a combination of the best Point Guards, Shooting Guards, Small Forwards, Power Forwards and Centres. More unorthodox groups can achieve great success too.

## Problem Definition:
Hence, we ask:
- How might we provide more insightful recommendations on team composition to todays managers?

To address this question, we set out to uncover the kind of players that todays high-performing basketball teams are composed of, by using machine learning techniques to reveal the true meta of NBA

## Models Used

1. Hierarchical Agglomerative Clustering 
2. K-Means Clustering

## Conclusion
Challenges:
- Do not know the true underlying clusters to compare against
-Limited practical significance derived from statistical metrics such as Silhouette Coefficient

Insights:
- Directly evaluating results in NBA's context. Models were able to generate useful and logical recommendations.
- Data from NBA.com seems to contain significantly more offensive playstyle statistics that may have limited the model's ability to identify strong defensive clusters.
- K-Means gave less insight on the differences between top and bottom teams
- Top teams had a composition that was in fact distinct from other teams


## What did we learn from this project?
- Using Selenium and BeautifulSoup for web scrapping
- Hierarchical Agglomerative Clustering and K-Means Clustering
- Collaborating using GitHub

## References
- https://www.nba.com/stats/
- https://scikit-learn.org/stable/modules/clustering.html
- 
- 
- 
