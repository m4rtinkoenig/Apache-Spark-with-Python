# Apache-Spark-with-Python
In this repository, I create simple projects from to get started with `pyspark`, e.g.:
1. Spark Basics
## Install
Prerequisite: `python3 >= 3.6`
1. Install `venv`
```bash
venv_name=venv
python3 -m venv $venv_name  # install venv
source $venv_name/bin/activate  # activate venv
```
2. Install `requirements`
```bash
pip install --upgrade pip  # update pip
pip install -r requirements.txt  # install required packages
```
## Structure
```
.
├── notebooks
│   └── 1st Spark Basics.ipynb
├── src
│   ├── helper
│   │   ├── __init__.py
│   │   └── decorators.py
│   └── __init__.py
├── README.md
└── requirements.txt
```
Created with `tree`

```bash
tree --dirsfirst -I "$(grep -hvE '^$|^#' {~/,,$(git rev-parse --show-toplevel)/}.gitignore|sed 's:/$::'|tr \\n '\|')"
```