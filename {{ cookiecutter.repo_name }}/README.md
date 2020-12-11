#{{cookiecutter.project_name}}
==============================

{{cookiecutter.description}}

Project Organization
------------

    ├── LICENSE
    ├── Makefile                <- Makefile with commands like `make data` or `make train`
    ├── README.md               <- The top-level README for developers using this project.
    ├── data
    │   ├── in                              <- Input data
    │   |── out                             <- Algorithm results.
    │   └── processed                       <- The final, canonical data sets for modeling.
    │
    ├── docs                                <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models                              <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks                           <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                                       the creator's initials, and a short `-` delimited description, e.g.
    │                                       `1.0-jqp-initial-data-exploration`.
    │
    ├── references                          <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports                             <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures                         <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt                    <- The requirements file for reproducing the analysis environment, e.g.
    │                                       generated with `pip freeze > requirements.txt`
    │
    ├── setup.py                            <- makes project pip installable (pip install -e .) so src can be imported
    ├── {{cookiecutter.project_name}}       <- Source code for use in this project.
    │   └─── __init__.py                    <- Makes src a Python module
    └──


--------

<p><small>Project based on the <a target="_blank" href="https://github.com/miquelmn/cookiecutter-data-science">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
