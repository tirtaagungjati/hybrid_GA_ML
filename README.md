# hybrid_GA_ML

Dataset : Dry Bean Dataset. (2020). UCI Machine Learning Repository. https://doi.org/10.24432/C50S4B. 

Machine Learning Models for Classification:
1. Random Forest Classifier
2. Naive Bayes Classifier
3. Support Vector Machines (SVM)

With Feature Selection Algorithm Using : Genetic Algorithms

Each classification model undergoes 4 experiments:
1. Data Attributes Not Normalized
2. All Data Attributes Normalized (Normalization is done using MinMaxScaler)
3. Partial Data Attributes Normalized where the data is not within the range [0,1] (Normalization is done using MinMaxScaler)
4. Without Feature Selection Algorithm just ML models for classification

Conclusion:

From all the experiments conducted, it was concluded that the experiment using Support Vector Machine (SVM) machine learning model along with Feature Selection using Genetic Algorithm and Normalization of All Data Attributes (Normalization done using MinMaxScaler) achieved the best accuracy result compared to other experiments, with an accuracy score of 92.65%.