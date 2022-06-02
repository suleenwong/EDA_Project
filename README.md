# EDA Project: King County Housing Data


![](https://kingcounty.gov/~/media/services/home-property/historic-preservation/images/KirklandHistoricHome.jpeg)

Source: [kingcounty.gov](https://kingcounty.gov/services/home-property/historic-preservation/projects/kirkland-inventory.aspx)


## Introduction

The goal of this project is to present to a fictitious stakeholder, our recommendations based on Exploratory Data Analysis (EDA) of the King County Housing Dataset.

Our stakeholder for this project is Mr. Zachary Brooks, with the following requirements:

Seller. Invests in historical houses, best neighborhoods, high profits, best timing within a year, should renovate?                                                      


## Setup

This repository contains a requirements.txt file with a list of all the packages and dependencies you will need. 

To install the environment you can use the following commands:
```zsh
pyenv local 3.9.8
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

Before you can start with plotly in Jupyter Lab you have to install node.js (if you haven't done it before):
```zsh
brew update
brew install node
```

## About this repo

In this repository you will find:


- **King_County_House_prices_dataset.csv** : Raw data

- **column_names.md** : Descriptions of the columns

- **EDA_Project_Notebook.ipynb** : Jupyter notebook with Exploratory Data Analysis (EDA), python code, visualizations, documentation

- **EDA_Project_Slides.pdf** : Presentation of the results of the EDA