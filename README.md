# Mechanism-Oriented Reaction Descriptors for Dispersity Prediction in Nitroxide-Mediated Radical Polymerization Considering Mediator Stability
Mechanism-Oriented Reaction Descriptors can be used to construct quantitative structure–property relationship (QSPR) models that are both highly predictive and interpretable for predicting the dispersity of controlled radical polymerization (CRP) in nitroxide-mediated radical polymerization(NMP). Since the descriptor follows the mechanism of CRP focusing on the equilibrium constant for forming dormant species from catalyst and propagating species and stability of mediator, it is expected to be adapted to other CRP approaches.


### Reference: Mori T.; Mieda S.; Kodama K.; Miyao T.; Mechanism-Oriented Reaction Descriptors for the Prediction of the Polydispersity Index in Nitroxide-Mediated Radical Polymerization

## Getting Started
### Prerequisites
The following libraries are necessary on top of [Python 3.7.16](https://www.python.org/downloads/release/python-3716/).

* [pandas](https://github.com/pandas-dev/pandas)
* [numpy](https://github.com/numpy/numpy)
* [matplotlib](https://github.com/matplotlib/matplotlib)
* [itertools](https://github.com/rust-itertools/itertools)
* [scikit-learn](https://github.com/scikit-learn/scikit-learn)
* [Boruta 0.3](https://github.com/scikit-learn-contrib/boruta_py)


## File Composition

- scripts
  * 00_function：Functions used for the following files
  * 01_Fitting_ARD：ARD linear regression for all data sets, and thier combinations for the NMP reactions.
  * 02_LOOCV_ARD：ARD linear regression for comparison of model accuracy.
  * 03_LOOCV_Lasso：Lasso regression for comparison of model accuracy.
  * 04_LOOCV_SVR：SVR with RBF kernel for comparison of model accuracy.
  * 05_LOOCV_SVR_tanimoto：SVR with tanimoto kernel for comparison of model accuracy.
  * 06_LOOCV_RF：RF for comparison of model accuracy.
  * 07_AD_after_removing_outliers_from_the_training_data：Exploring AD with Explanatory Variables after removing outliers from the training data.
  * 08_predicting_test_data：Dataset 1&2 was used as training data to predict Dataset 3&4.
  * 09_comparison_with_explicit_equations：Comparison of our approach with explicit　equations approach.
  * 10_williams_plot：A graphical method for visually identifying the AD and outliers of a model.
  * 11_LOOCV_ARD_with_conversion：Comparison with and without conversion information
- data
- result 


## Authors 
Tatsuya Mori: https://github.com/tastuya6
Tomoyuki Miyao: https://github.com/miyaotomoyuki

### Contributors to the Mechanism-Oriented Reaction Descriptors for living radical polymerization project:
Tatsuya Mori
Shunsuke Mieda
Koharu Kodama
Tomoyuki Miyao

## License
See LICENSE.txt

```python

```
