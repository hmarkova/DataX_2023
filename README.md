# DataX_2023 - Penguins classification

Repository for project created within the course Data-X – Applied Data Analytics Models in Real World Tasks (4IT439), at Faculty of Informatics and Statistics, Prague University of Economics and Business (VŠE). This project is developed using Python.

**Authors:** Hana Marková, Ekaterina Pronevich, Karolína Pěstová, Jakub Sokol

## Description

We have been given a dataset of penguins, based on which we need to create a model that will classify the species of penguin based on the penguin's characteristics.

In order to accomplish the task, we took the following steps: Problem definition, Data Understanding, Data Exploration, Data Preprocessing, Data Visualizaion, Modeling with finding best hyperparameters and Evaluation of created models.

## Repository structure

```
├── data     <- Data in raw form, transformed and normalized
│    ├── raw.csv                      <- Original data.
│    ├── preprocessed.csv      	      <- Final preprocessed data.
│    ├── interim.csv                  <- Joined testing, traing and validation dataset after normalization.
│
├── models   <- models that have been created within out project.
│    |
│    ├── rf_model.h5         <- Random Forest Model.
│    ├── lr_model.h5         <- Logistical regression Model.
│    ├── gb_model.h5         <- Gradient Boost Model.
│
├── notebooks     <- All Jupyter notebooks created in the project. 
│    ├── penguins_model.ipynb <- Jupyter notebook with building classification models.
│
├── README.md                         <- The README file for users who wants to use this project.
├── Report                            <- Documentation of our project.
├── requirements.txt                  <- Requirements file to run the project.
```

## Instaling environment

Before running any scripts, you should first install the environment. Once you've created your own environment, you should install all the packages with the correct versions that were used in our scripts and on which the models are built on.

1. Create new virtual environment
- Using version ```Python 3.8.10``` 
- Create the virtual environment in the terminal by:
```
python -m venv venv
``` 
2. Install all packages with correct version.
- All packages with correct veersions are saved into ```../data/requirements.txt``` 
- Download the file with requirements
- Activate the virtual environment in the terminal by:
```
.\venv\scripts\activate
``` 
- Install the requirementsin the terminal by:
```
pip install -r requirements.txt
``` 

## Running scipts

We created script in Jupyter notebook ```penguins_model.ipynb```. To build classification models run this script in the terminal.
