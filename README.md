# Random Forest Flassifier
This project uses random forest classifier to predict whether an individual makes more than 50K a year. We use the UCI Machine Learning Repository data: https://archive.ics.uci.edu/ml/datasets/Census+Income

We transform skewed continuous features, normalize numerical features and convert categorical features using one-hot encoding. Then we fine tune the random forest classifer using the grid search. We then describe the first five most predictive features. 


|     Metric     | Unoptimized Model | Optimized Model |
| :------------: | :---------------: | :-------------: | 
| Accuracy Score |   0.8443          |   0.8475        |
| F-score        |   0.6856          |   0.7296        |

