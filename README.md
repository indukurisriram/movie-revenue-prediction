# Movie Revenue Prediction Machine Learning Project

This project aims to predict movie box office collections using features such as marketing expense, production expense, budget, actor ratings, director ratings, genre, and more.

## Project Structure
- `data/`: Contains the primary dataset (`Movie_regression.csv`).
- `notebooks/`: Contains the Jupyter Notebook holding the model training and analysis (`MOVIE_REVENUE_PREDICTION_MACHINE_LEARNING_PROJECT.ipynb`).
- `presentations/`: Contains the presentation slide deck explaining the project's findings (`ML_PROJECT.pptx`).

## Dataset
The dataset utilized is `Movie_regression.csv`, containing 506 records with features relating to the financial investment, reception, and details of various movies. Key features include:
- Financials: Marketing expense, Production expense, Budget, Collection
- Ratings: Lead Actor Rating, Lead Actress Rating, Director Rating, Producer Rating, Critic Rating
- Information: Multiplex coverage, Movie length, Trailer views, 3D availability, Twitter hashtags, Genre, Average age of actors, Number of multiplexes

## Machine Learning Models Used
The project explores the following regression models to predict movie revenue:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor

The implementation covers data preprocessing steps like handling missing values, standardizing numerical features, and creating dummy variables for categorical attributes, before model training and evaluation using metrics such as Mean Squared Error and R-squared.

## Access the Code
You can access the project notebook directly via Google Colab:
[Movie Revenue Prediction Colab Notebook](https://colab.research.google.com/drive/1GWV77Zm02omzeLG1baIkgTxTUhHvyMHe)