# linear-regression-matrix-manipulation
This repository contains a Python notebook with a reference implementation of linear regression, a fundamental machine learning algorithm.
This repository contains a Python notebook with a reference implementation of linear regression, a fundamental machine learning algorithm. The goal of this task is to create a custom implementation of linear regression by developing functions for the necessary matrix manipulations. The notebook includes functions for matrix operations such as multiplication and transposition, which are used to compute the least squares estimate of the linear regression weight vector. The key functions are named 'fit', 'predict', and 'get_params'.

Please note the following specifications:
- The matrix manipulation functions handle matrices of arbitrary sizes, except for the inverse calculation, which is tailored for 2x2 matrices.
- Error handling is implemented to prevent runtime errors arising from matrices of incorrect sizes.
- Appropriate comments (doc strings) are added to the functions for clarity.

At this stage, a class is not used to encapsulate the code. The addition of a class may be considered in the future, as indicated in the task description.

The repository also includes a task for Week 4, where a Principal Components Analysis (PCA) is performed on a dataset using the Scikit-learn toolbox. The dimensionality of the dataset is reduced to 1, and the effect of applying PCA in the original data space is visualized. The reverse transform is implemented using the numpy module for verification against Scikit-learn's output.
