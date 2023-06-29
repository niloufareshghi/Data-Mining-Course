# Data-Mining-Course

## Association Rules Homework
Association rules represent relationships and interdependencies between large sets of data items.
A common example of association rule discovery is "shopping cart analysis". In this process, according to the different items that customers put in their shopping carts, the buying habits and behavior of customers are analyzed, and by identifying the relationship between products, repeating patterns during shopping can be obtained.

In this exercise, I applied the apriori algorithm on the Hypermarket_dataset dataset, which contains people's purchase orders from grocery stores. 

## Classifications Homework
In this exercise, I implemented binary classification for make-_circles and fashion_mnist datasets. Multiple approaches were taken such as neural network without activation function, neural network with linear activation function, neural network with linear activation function and regression loss (MAE), one layered neural network linear activation function and regression loss (MAE), to compare results. For the optimal solution, hyperparameter tuning was done to obtain the optimal learning rate.

## Clustering Homework
In this exercise, I implement several clustering approaches. K-means is implemented and optimized using the elbow method for optimal cluster count. manifold Isomap has also been implemented for "more complex clustering" examples.

K-means is also used to reduce the size of an image. 

DBSCAN algorithm is one of the other algorithms used for data clustering, which can cluster data with different shapes and detect noises and anomalies in the data.
According to the said advantage, in this section, we want to re-cluster the two data sets mentioned in the "more complex clustering" section using the DBSCAN algorithm. Consider the X_aniso and X_varied datasets. To run the DBSCAN algorithm, there is no need to determine the number of clusters, and you should determine the two main parameters of this algorithm, i.e. epsilon and the minimum number of points in each cluster, in such a way that your output becomes more accurate
In this exercise, I obtained the optimal values for epsilon and the minimum number of points in each cluster, and optimal clustering has been done using them.

## Diabetes Classification
A database of a population given with different features such as Age, Sex, Weight, Blood Pressure, Blood Glucose Level, etc is given and an optimal classification model was designed to predict whether someone given their health factors is at risk of having diabetes or not. GridSearchCv is utilized for hyperparameter tuning and XGBoost was used for the classification.
