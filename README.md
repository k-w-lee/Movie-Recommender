# Movie Recommender System using Unsupervised Learning

## Problem Formulation
1. Given the attributes of the movies, group the similar movies together by using clustering analysis.
2. Given the users rating histories, identify the association rules among the movies to predict what movies the users are going to watch next.

## Dataset
We selected [The Movies Dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset) from Kaggle which consists of 7 CSV files, containing metadata for all 45,000 movies released on or before July 2017 that are listed in the Full MovieLens Dataset, and 26 million ratings from 270,000 users for all 45,000 movies. 

## Preprocessing
<img align="middle" alt="Python" width="350" src="https://user-images.githubusercontent.com/78056833/138011652-7a5f2545-73d0-4bfa-abbc-247af684ee1d.png" />

## Machine Learning Techniques
1. K-Means Clustering
2. Hierachical Clustering
3. Apriori Algorithm for association rules mining
4. Apriori Algorithm for subsets of data (genre of movie)

## Team Presentation
You can view the team presentation via this [link](https://spark.adobe.com/page/5LdV3RV1i3Ubk/)

## How the system will looks like in real world
<img width="664" alt="movie" src="https://user-images.githubusercontent.com/78056833/138011033-c014a787-178d-4287-90c0-e4a9a23b7d58.png">

## Conclusion
K-Means and K-Modes clustering are chosen to cluster similar movies together. By having these clusters, it helps service provider to manage their contents more efficiently, and it also enables users to choose their favorite movies easily. Furthermore, by using association rules, we discovered a lot of rules with high lift that can be used to recommend the right movies to the users. So, the overall users experience will improve. The figure below shows a movie recommender system interface to a audience who has watched "The Sixth Sense".
