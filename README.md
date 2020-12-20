# Indian-Liver-Patient-Dataset

This dataset is publicly available on UCI-ML. Link:- https://archive.ics.uci.edu/ml/datasets/ILPD+(Indian+Liver+Patient+Dataset)
The related publications are also provided on the UCI-ML page. In the paper "International Journal of Database Management Systems (IJDMS), Vol.3, No.2, ISSN : 0975-5705, PP 101-114, May 2011", the authors didn't consider the multicollinearity and have used only the ranking of the independent features to build the classification model. In this study, the Pearson correlation to determine the multicollinearity and remove the independent features for which the Pearson correlation coefficient (PCC) is outside the range of -0.3 < PCC < 0.3.     

The objective is to classify the a patient into a "sick" or "normal" category based on certain features. 
Main focus is in on the feature selection and hyperparameter optimization. For the latter, I have used RandomizedSearch and BayesianSearch method.
Two metrics viz. classification report and confusion matrix have been to quantify the result.
