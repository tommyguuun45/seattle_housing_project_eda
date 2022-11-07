# Seattle Housing Dataset - EDA Project

This repository contains an Exploratory Data Analysis on the Seattle Housing dataset. After exploring and cleaning the data in a first step, I set up a few hypotheses and tested them afterwards. The goal of the analysis is to make some recommendations for my stakeholder who wants to invest in houses in poor neighborhoods in Seattle.

The results of the analysis can be found in 
the [Jupyter Notebook](EDA.ipynb) and in the [Stakeholder Presentation](SeattleHousingDatasetEDA.pdf).



## Environment

Please make sure you have forked the repo and set up a new virtual environment. For this purpose you can use the following commands:

```sh
pyenv local 3.9.8
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

The added [requirements file](requirements.txt) contains all libraries and dependencies we need to execute the EDA notebook.

## Data

The dataset for the notebook is stored in the `data` folder. 
