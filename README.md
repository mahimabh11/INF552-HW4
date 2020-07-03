Readme for Assignment-4

Name: Mahima Bhargava
USC ID: 3936853735

1.The libraries used:

a.) Scikit-Learn
b.) Numpy
c.) Matplotlib
d.) Pandas
e.) Xgboost
f.) Seaborn
g.) math
h.) weka.classifiers
i.) weka.core.converters

2.) I had experimented with iterative imputer too but decided to stick with mean(simpleImputer) to avoid any issues which might arise due to sudden deprecation as this was an experimental module.

3.) I have done part 2d in two ways-: one using class_weight='balance'. Since that did not give better results, I re-did the balancing using smote(ratio of minority:majority of 1:4). The accuracy increased very slightly but the f1-score for the positive class increased.



