# Capstone Project

## Datasets

- https://data-usfs.hub.arcgis.com/datasets/national-interagency-fire-occurrence-sixth-edition-1992-2020-feature-layer/about
- https://github.com/meteostat/meteostat-python
- https://registry.opendata.aws/terrain-tiles/

## Code Overview

- 1980-2020_plots.ipynb
    - Loads and plots relationships from USFS dataset between 1980-2020
- capstone_eda.ipynb
    - Initial reading and investigation of USFS dataset
    - Performs some data cleaning and writes intermediary dataset (records between 1980-2020) for further processing
    - Enriches USFS data with weather variables from meteostat
- capstone_strm_elevation_data.ipynb
    - Handles downloading an enriching dataset with elevations
    - Merges with weather data and write new shapefile for further processing
- duration_vs_elevation.ipynb
    - Plotting relationship of elevation and fire duration as well as initial xgboost modeling.
- sub_questions.ipynb
    - Answers project questions includes ANOVA, linear regression, logistic regression, ROC curves, etc
- xgboost.ipynb
    - XGBoost regressor and hyperparameter tuning
