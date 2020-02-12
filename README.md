# Principle_Component_Analysis(PCA)

Principle Component Analysis(PCA) is a technique which is udes to reduce dimensionality of the dataset having multiple correlated variables. The degree of correlation may vary for each variable to another variable. The reduction process tries to minimise the loss in the variation of the datatset. The principal components are the eigenvectors of a covariance matrix, and hence they are orthogonal.


# PCA On Breast Cancer Dataset

The skicit  library of python consists of varius datasets, one of which is Breast Cancer Dataset. The dataset consists of 569 instances in total out of which 212 are malignant and 357 are beneign. 30 attributes define various features of each sample in the dataset. Now it is hard to work with 30 feature vectors due to increased amout of computation. Also, all the features donot have same amount of influence on the output. Hence the features with less impact are removed from final feature vector set using PCA. 
