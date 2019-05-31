`recourse-equalization` is the code associated to the paper `Equalizing recourse across groups`

## Overview
We define recourse as the true/approximate distance of an individual from the decision boundary of a classifier. In `codes/svm-recourse.py` we train linear, non-linear kernelizable classifiers (SVM like) to equalize for recourse across two groups. And in `codes/blackbox-agnostic.py` we retrain blackbox classifiers to equalize recourse across groups.

## Requirements
* Python 3
* Scikit-Learn
* CVXOPT (for the quadratic solver)
* Pandas (for reading csv files)
* Ray (for running the agnostic tests in parallel)
* Psutil
* Matplotlib (for plotting)

## Credits
We thank Riberio et. al. for [LIME](https://github.com/marcotcr/lime) and Ustun et. al. for [Actionable Recourse](https://github.com/ustunb/actionable-recourse).
