TimeSeries_StockPrice
==============================

In this project, I use different concepts and packages in the python ecosystem to work with time series data. The aim is to develop an end-to-end machine learning pipeline.

Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.testrun.org


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>

# Machine learning, statistics, analytics

## Libraries

| Project Name | Description |
| ------- | ------ |
| [arch](https://github.com/bashtage/arch) | Autoregressive Conditional Heteroskedasticity (ARCH) and other tools for financial econometrics |
| [Featuretools](https://github.com/Featuretools/featuretools) | Time series feature extraction, with possible conditionality on other variables with a pandas compatible relational-database-like data container |
| [ffn](https://github.com/pmorissette/ffn) | financial function library |
| [flint](https://github.com/twosigma/flint) | A Time Series Library for Apache Spark |
| [HMMLearn](https://github.com/hmmlearn/hmmlearn) | Hidden Markov Models with scikit-learn compatible API |
| [prophet](https://github.com/facebook/prophet) |  Time series forecasting for time series data that has multiple seasonality with linear or non-linear growth |
| [pyts](https://github.com/johannfaouzi/pyts) | Contains time series preprocessing, transformation as well as classification techniques |
| [sktime](https://github.com/alan-turing-institute/sktime) | A scikit-learn compatible library for learning with time series/panel data including time series classification/regression and (supervised/panel) forecasting |
| [statsmodels](https://github.com/statsmodels/statsmodels) | Contains a submodule for classical time series models and hypothesis tests |
| [stumpy](https://github.com/TDAmeritrade/stumpy) | Calculates matrix profile for time series subsequence all-pairs-similarity-search. Offers anomaly detection and pattern (or “motif”) discovery at the same time. |
| [tsfresh](https://github.com/blue-yonder/tsfresh) | Extracts and filters features from time series, allowing supervised classificators and regressor to be applied to time series data |
| [tslearn](https://github.com/rtavenar/tslearn) | Direct time series classifiers and regressors |

# Data

| Project name | Description |
| ------- | ------ |
| [pandas-datareader](https://github.com/pydata/pandas-datareader) | Pulls financial data from different sources (e.g. yahoo, google, Quandl) |

### [ref](https://github.com/MaxBenChrist/awesome_time_series_in_python/blob/master/README.md)

Please visit my [site](https://adataanalyst.com/) for more information.
