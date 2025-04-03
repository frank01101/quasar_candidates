# Quasar candidates

Demonstration of a comprehensive machine learning analysis of the real scientific data of candidates for quasi-stellar objects (QSO or quasars) by Richards et al., ApJS 219 (2015). The analysis consists of:

1. Exploratory data analysis (EDA) with data cleaning and feature engineering, exploration of important correlations between the features and significance testing of statistical hypotheses.
   * **quasars-report.pdf** contains the readable report of the EDA analysis.
   * **quasars_eda.ipynb** is the Jupyter iPython notebook where the whole EDA analysis was performed.
2. Regression analysis with various models aiming at prediction of the redshift value of an object basing on its color variables.
   * **quasars_regression.ipynb** is the Jupyter notebook where the whole regression analysis was performed.
3. (In future) Classification analysis to differentiate objects with respect to given features (like redshift) in the color-color space.

**cand.dat** is the raw catalog which the analysis was based on ([accessed remotely](https://cdsarc.cds.unistra.fr/ftp/J/ApJS/219/39/) as it's a large file).
