Use predict_proba based scores to evaluate the model. Predict use .5 threshold which is not obviously always the best

resampling only the train set. And if so, avoid it as it modifies the true distribution. Tuning the parameters is more appropriate 

ref : https://medium.com/data-science-at-microsoft/five-mistakes-to-avoid-when-modeling-with-imbalanced-datasets-d58a8c09929c
