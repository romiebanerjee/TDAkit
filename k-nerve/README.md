# k-nerve

Input: n-dimensional dataset (ex: numpy array of floats) + covering dimension = k ( any integer between 1 and n)

Output: k-dimensional simplicial complex (k <= n )

Visualization: 2-skeleton of k-dimensional simplicial complex 

## Dependencies
* numpy
* pandas
* sklearn.decomposition.PCA
* sklearn.cluster.DBSCAN
* json
* d3.js


# Examples

## Iris Dataset

Data: http://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_iris.html

![iris_2_400_1](https://github.com/romiebanerjee/k-nerve/blob/master/Examples/iris_2_400_1.png)

2-nerve of Iris Dataset

Click [here](https://github.com/romiebanerjee/k-nerve/blob/master/Examples/index_iris.html) for interactive version.

## Breast Cancer Dataset

Data: http://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html

![breast_cancer_2_400_065](https://github.com/romiebanerjee/k-nerve/blob/master/Examples/breast_cancer_2_400_065.png)

2-nerve of Breast Cancer Dataset

Click [here](https://github.com/romiebanerjee/k-nerve/blob/master/Examples/index_breastcancer.html) for interactive version

## Diabetes Dataset 

Data: http://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_diabetes.html

![diabetes_2_225_065](https://github.com/romiebanerjee/k-nerve/blob/master/Examples/diabetes_2_225_065.png)

2-nerve of Diabetes data

Click [here](https://github.com/romiebanerjee/k-nerve/blob/master/Examples/index_diabetes2.html) for interactive version.

![diabetes_3_225_04](https://github.com/romiebanerjee/k-nerve/blob/master/Examples/diabetes_3_225_04.png)

3-nerve of Diabetes data

Click [here](https://github.com/romiebanerjee/k-nerve/blob/master/Examples/index_diabetes3.html) for interactive version.


## Wine Quality Dataset 

Data: https://archive.ics.uci.edu/ml/datasets/Wine+Quality

![redwine_2_400_055](https://github.com/romiebanerjee/k-nerve/blob/master/Examples/redwine_2_400_055.png)

2-nerve of redwine data

Click [here](https://github.com/romiebanerjee/k-nerve/blob/master/Examples/index_redwine.html) for interactive version.









