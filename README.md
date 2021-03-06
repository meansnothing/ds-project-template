# Data Science Project Template
Ensuring reproducibility of experiments requires:
- Consistent data
    - raw data version (date)
    - processing pipelines
- Consistent model 
    - random seeds
    - hyperparameters
  
# Basic
Based on [cookiecutter data science project structure](https://drivendata.github.io/cookiecutter-data-science/).
```
project
├── data                      
|   ├── raw                       
|   ├── interim               <- Intermediate data that has been transformed.      
|   └── processed             <- Data ready for modeling
│
├── models                    <- Trained and serialized models.
|
├── reports                   <- Generated analysis as HTML, PDF, LaTeX, etc.
│
├── notebooks                 <- Jupyter notebooks.
|   └── 0.0-name-description.ipynb
│
├── src                       <- Source code for use in this project.
|   ├── __init__.py           <- Makes src a Python module
|   ├── data                  <- Scripts to prepare data
|   ├── model                 <- Scripts to train models
|   └── tests                 <- Unit testing
|     ├── test_data.py                  
|     ├── test_model.py                
|     └── ...
│
├── references                <- Data dictionaries, manuals, and all other explanatory materials.
│
├── requirements.txt          <- pip install requirements.txt
└── .gitignore
```

# More
```
project  
├── LICENSE
├── Makefile           <- Makefile with commands like `make data` or `make train`
├── setup.py           <- Make this project pip installable with `pip install -e`
├── docs               <- Sphinx or MKDocs?
│
└── tox.ini            <- Automate and standardize testing
```
