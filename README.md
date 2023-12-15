# Speedup Predictor

Implementing machine learning algorithms to accurately predict the speedup, and the optimal set of parameters with which maximum speedup can be achieved, which can be attained by parallelizing the given program as compared to its serial counterpart. 

Tested the algorithms on a publicly available benchmark of the PARSEC 3.0 dataset. 

SMOTE was used for removing data skewness. 

Random Forest Regressor performs the best with SMOTE applied to it.

![Arch](https://github.com/imnishanth/SpeedupPredictor/blob/main/sp-arch.png)