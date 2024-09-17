# Development of Predictive Models for Nanomaterial Biodistribution Using Machine Learning

This repository contains all the files used for the thesis titled "Development of Predictive Models for Nanomaterial Biodistribution Using Machine Learning" of Alexandros Angelis. The thesis focuses on developing models to predict the biodistribution of nanomaterials using machine learning techniques.

## Table of Contents
- [Biodistribution Data](#biodistribution-data)
  - [Experiment_details.xlsx](#experiment_detailsxlsx)
  - [NMs_Database.xlsx](#nms_databasexlsx)
  - [Organ_percent_BW.xlsx](#organ_percent_bwxlsx)
- [Code](#code)
  - [AUC_calculation_code.ipynb](#auc_calculation_codeipynb)
  - [Crawl_with_Bio_by_Date.ipynb](#crawl_with_bio_by_dateipynb)
  - [Data_Processing.ipynb](#data_processingipynb)
  - [Parameters_optimization_NLopt.ipynb](#parameters_optimization_nloptipynb)
  - [Random_forest_regression.ipynb](#random_forest_regressionipynb)
- [Installation](#installation)

## Biodistribution Data

This folder contains the data files used in the thesis:

### `Experiment_details.xlsx`

Detailed information on the experimental conditions used to generate the biodistribution data.

### `NMs_Database.xlsx`

A comprehensive database of nanomaterials and their associated properties, used as input data for modeling.

### `Organ_percent_BW.xlsx`

Data on the organ-to-body weight ratios for different tissues, used to analyze the biodistribution of nanomaterials.

## Code

The code folder in this repository contains all Jupyter notebooks used in the thesis. Below is a brief overview of each file:

### `AUC_calculation_code.ipynb`

Calculates the Area Under the Curve (AUC) and Cmax values for the biodistribution data using a double exponential decay model with a constant factor.

### `Crawl_with_Bio_by_Date.ipynb`

This notebook contains a web crawler that searches for biodistribution data specific to nanomaterials. It automates the collection of relevant data to build and update the database.

### `Data_Processing.ipynb`

Processes the raw data obtained from the database, including data cleaning, normalization, and transformation steps, preparing it for further analysis and modeling.

### `Parameters_optimization_NLopt.ipynb`

Optimizes the parameters of the biodistribution fit curve. The fitting is performed using a double exponential decay with a constant factor, leveraging the NLopt optimizer for precise parameter estimation.

### `Random_forest_regression.ipynb`

Builds machine learning models using Random Forest regression to predict AUC and Cmax. This file also evaluates model performance, identifies feature importance, and determines the applicability domain.

## Installation

To use the code files, you need to have Jupyter Notebook installed.
