# Wine Quality Regression: Chemical Properties and Quality

### Introduction
This notebook shows a linear regression fit to a set of wine chemical properties and their consumer ranked quality. Chemical properties that have a poor correlative relationship to wine quality are filtered out of the analysis. Properties with a high correlation to quality appear to be predictive of a consumer's satisfaction with a given wine. Apoorva Dave's Medium article was referenced extensively when researching and implementing the design for this learning exercise. Her work is referenced in the Acknowledgements, and deserves the credit for this design.

### Results
Results of the analysis may be seen directly in the Jupyter notebook within this repository. A snapshot with the generated analysis data is encapsulated in the notebook.

### How to Run the Code
To run this code, simply run the ipybn notebook file in Jupyter. Ensure that you have the following libraries installed: 	

```
import pandas as pd 
from sklearn.model_selection import train_test_split 
from sklearn.linear_model import LinearRegression 
from sklearn import metrics
from sklearn.metrics import mean_squared_error
import matplotlib.pyplot as plt 
import numpy as np 
import seaborn as sns
```

### Acknowledgments

* [Regression from scratch — Wine quality prediction](https://medium.com/datadriveninvestor/regression-from-scratch-wine-quality-prediction-d61195cb91c8)
* [Apoorva Dave's repo](https://github.com/apoorva-dave)

![alt text](thetaprime_shape.png)
