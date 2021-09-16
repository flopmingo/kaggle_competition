# Machine Learning Kaggle Competition
The Kaggle Competition project was a class competition for creating the best ensemble of classifers of data on satelite based measurements to predict the presence or absence of rainfalls at a particular location. The ensemble created consist of Random Forest, Neural Networks, Linear Classifer, and SVM Kernel. The classifers were combined using weighted average of class probabilities or soft predictions. The Random Forest was given a weight of 0.7 and the rest of the classifers each had a weight of 0.1. This was because the Random Forest classifier produced the highest validation AUC score, while the remaining classifers had similar validation AUC scores.

The results:

Model | Training AUC | Validation AUC | Kaggle Score

Random Forest | 0.9534 | 0.7860 | 0.78167

Neural Networks | 0.6536 | 0.6561 | 0.53208

Linear Classifer | 0.6772 | 0.6765 | N/A

SVM Kernel | 0.7173 | 0.75113 | 0.67466

Ensemble | 0.86939 | 0.75113 | 0.78173 
