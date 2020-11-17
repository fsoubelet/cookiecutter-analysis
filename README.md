# Personal Cookiecutter for Data Analysis

_This is an adaptation of the excellent cookiecutter data science template by drivendata._

## Requirements to use the cookiecutter template:
 
- Python 2.7 or 3.5+
- [Cookiecutter Python package](http://cookiecutter.readthedocs.org/en/latest/installation.html) >= `1.4.0`.

## To start a new analysis, I run:


```bash
cookiecutter gh:fsoubelet/cookiecutter-analysis
```

## The resulting directory structure

The directory structure of your new project looks like this: 

```
├── LICENSE
├── Makefile           <- Makefile with commands like `make data`.
├── README.md          <- The top-level README for people using this project.
├── data
│   ├── interim        <- Intermediate data that has been transformed.
│   └── raw            <- The original, immutable data dump.
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting.
│
└── src                <- Source code for use in this project.
    ├── __init__.py    <- Makes src a Python module.
    │
    ├── data           <- Utilities to download, generate or manipulate data.
    │   └── dataset.py
    │
    └── visualization  <- Utilities to create exploratory and results oriented visualizations.
        └── visualize.py
```
