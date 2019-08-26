# A study on IRIS Plant Classification using K-nearest Neighbor (KNN).
This project is a part of the learning milestone of a Udemy course delivered by [SuperDataScience Team](https://www.udemy.com/machine-learning-classification/). 

### Author
[Derrick Chan](https://github.com/zhenyu92)

[Derrick's Linkedin](https://www.linkedin.com/in/zychan/)

### Project Status: [Completed]

### Project Objective
The data set contains 3 classes of 50 instances each, where each class refers to a type of iris plant. 
The attribute to be predicted is the class of iris plant. 
The classes are as follows: 1. Iris Setosa, 2. Iris Versicolour, 3. Iris Virginica

`Predictors:`
```
sepalLength (cm)
sepalWidth (cm)
petalLength (cm)
petalWidth (cm)
```

`Target:`
```
Class (1. Iris Setosa, 2. Iris Versicolour, 3. Iris Virginica)
```

### Environment Prerequisites
`Jupyter Notebook` for Python scripting.

### Instructions
1. Downloaded the [dataset](https://github.com/zhenyu92/ML_KNN_IRIS_Plant_Classification/blob/master/Iris.csv).
2. Run and execute the [IPython](https://github.com/zhenyu92/ML_KNN_IRIS_Plant_Classification/blob/master/KNN%20-%20IRIS%20Plant%20Classification.ipynb).
    The following will be covered, and return a prediction.
    ```
    1 Importing Relevant Libraries
    2 Loading Raw Data
    3 Preprocessing
      3.1 Visualizing the Variables
    4 Train Test Split
    5 Select and Train a Model
      5.1 K-nearest Neighbors Model
    6 Apply Model on Test Set
    ```   
    
### Model Performance
The model has an average `Precision` of 97% and `Recall` of 87%.
![alt text](https://github.com/zhenyu92/ML_KNN_IRIS_Plant_Classification/blob/master/Confusion%20Matrix.JPG "Confusion Matrix")
