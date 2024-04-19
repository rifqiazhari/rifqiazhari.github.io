# Data Science Portfolio
---
## Machine Learning

### Predict House Prices (Regression) using XGBoost, Linear Regression, Ridge Regression, Lasso Regression, Lightgbm Regression, and CatBoost Regression with Cross Validation (Top 13% in Kaggle - Solo)

[![Open Notebook](https://img.shields.io/badge/Jupyter-Open_Notebook-green?logo=Jupyter)](html3/houseprice.html)
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-green?logo=GitHub)](https://github.com/rifqiazhari/rifqiazhari.github.io/blob/main/python/houseprice.ipynb)
[![Download Notebook](https://img.shields.io/badge/Download%20Notebook-8A2BE2)](python/houseprice.ipynb)

When buying a house, customers usually have considerations about things like the presence of a garage, the number of bedrooms, the number of floors, and the age of the house. On this occasion, I am given The Ames Housing dataset compiled by Dean De Cock and provided by Kaggle. This dataset talks about many variables of houses from the count into its variable area. Our objective is to predict the sales price for each house.

I use many regression algorithms to build the model for this case. From what I worked on, the results stated that The CatBoost Regression makes the best prediction with score 0.12635 (TOP 13%) followed by Lightgbm Regression with 0.13600, XGBoost Regression with 0.13846, Random Forest Regression with 0.14769, Ridge Regression with 0.16393, Lasso Regression with 0.18259, Linear Regression with 0.19824. Improvement still can be make by adding by applying cross-validation (CV), and more deeper EDA.

<center><img src="images/regression.jpg"/></center>

---
### Predict Spaceship Titanic Passenger Who Got Transported (Classification) using Logistic Regression, Random Forest, KNN, Decision Trees, SVM, GradientBoosting Classifier, Catboost Classifier with Cross Validation (Top 7% in Kaggle - Solo)

[![Open Notebook](https://img.shields.io/badge/Jupyter-Open_Notebook-green?logo=Jupyter)](html3/spaceship.html)
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-green?logo=GitHub)](https://github.com/rifqiazhari/rifqiazhari.github.io/blob/main/python/spaceship.ipynb)
[![Download Notebook](https://img.shields.io/badge/Download%20Notebook-8A2BE2)](python/spaceship.ipynb)

In 2912, The Spaceship Titanic was an interstellar passenger liner launched a month ago. With almost 13,000 passengers on board, the vessel set out on its maiden voyage transporting emigrants from our solar system to three newly habitable exoplanets orbiting nearby stars. While rounding Alpha Centauri en route to its first destination—the torrid 55 Cancri E—the unwary Spaceship Titanic collided with a spacetime anomaly hidden within a dust cloud. Sadly, it met a similar fate as its namesake from 1000 years before. Though the ship stayed intact, almost half of the passengers were transported to an alternate dimension!

From this unique case, we have the objective to predict whether a passenger was transported to an alternate dimension during the Spaceship Titanic's collision with the spacetime anomaly. We use many classification algorithms for this binary classification case. From what I worked on, the results stated that the Catboost Classifier makes the best classifier algorithm with 0.80734 accuracy on the test set followed by Random Forest, SVM, Decision Trees, KNN, Logistic Regression.

<div style="text-align: justify"></div>

<center><img src="images/classification.jpg"/></center>

---

## Deep Learning (Computer Vision)

### MNIST Digit Recognizer using VGG16 and ResNet50 with TensorFlow (Top 9% in Kaggle - Solo)

[![Open Notebook](https://img.shields.io/badge/Jupyter-Open_TensorFlow_Notebook-green?logo=Jupyter)](html3/mnisttensorflow.html)
[![Open Notebook](https://img.shields.io/badge/Jupyter-Open_PyTorch_Notebook-green?logo=Jupyter)]()

This time I am provided MNIST data from Kaggle. MNIST data is a collection of 70,000 handwritten digit images. Our goal is to build a model that classifies each image of MNIST data into 10 different classes or digits (0, 1, 2, 3, 4, 5, 6, 7, 8, and 9). The data is separated between the training and test datasets with the 60:40 proportion. In other to evaluate our model, I need to match our predicted data to the actual data on the Kaggle website.

We want to make prediction models using Convolutional Neural Network (CNN). The MNIST image was originally in 28x28 format but the data from Kaggle is in flattened format so we need to do some preprocessing to convert it to the original image dimension.

<div style="text-align: justify">For now only available in TensorFlow</div>
<br>
<center><img src="images/mnist2.jpg"/></center>
<br>

---
### CIFAR-10 Image Classification using VGG16 and ResNet50 with TensorFlow

[![Open Notebook](https://img.shields.io/badge/Jupyter-Open_TensorFlow_Notebook-green?logo=Jupyter)]()
[![Open Notebook](https://img.shields.io/badge/Jupyter-Open_PyTorch_Notebook-green?logo=Jupyter)]()

CIFAR-10  is an established computer-vision dataset used for object recognition. It is a subset of the 80 million tiny images dataset and consists of 60,000 32x32 color images containing one of 10 object classes, with 6000 images per class. It was collected by Alex Krizhevsky, Vinod Nair, and Geoffrey Hinton. In this case, we will use the 60,000 32x32 color images, 50,000 for the training set and 10,000 for the test set.

Our objective is to build a model that could precisely classify the 10,000 test data. 

<div style="text-align: justify">The model is still in development since the parameters could up to 27 million.</div>
<br>
<center><img src="images/cifar102.jpg"/></center>
<br>

---
## Data Science (R)

### Building a Baseball Team with Limited Budget ($40M) for 2002 MLB Season (code in R)

[![Open Notebook](https://img.shields.io/badge/Medium-Open_Medium-12100E?style=flat&logo=medium&logoColor=white)](https://medium.com/@rifqiazhari/building-a-baseball-team-with-limited-budget-40m-for-2002-mlb-season-84222de82913)

We want to build a baseball team with a limited budget of forty million dollars for the 2002 MLB season. We will explore the data from Lahman Library from R which include team-level and player-level statistics.
<br>
<center><img src="images/baseball.jpg"/></center>
<br>

---
## Forecasting
### Store Item Demand Forecasting Challenge (In the process of editing)

[![Open Notebook](https://img.shields.io/badge/Jupyter-Open_TensorFlow_Notebook-green?logo=Jupyter)]()

I have been given a dataset of 5 years of store-item sales and I want to predict 3 months of sales for 50 different items at 10 different stores.

From the dataset I also want to answer this question: (i) What's the best way to deal with seasonality? Should stores be modeled separately, or can you pool them together?

In the process of editing.
<br>

---
## Analytics Only
### Ice Cream Sales Rating (In the process of editing)

[![Open Notebook](https://img.shields.io/badge/Jupyter-Open_TensorFlow_Notebook-green?logo=Jupyter)]()

This dataset contains details (including ingredients), images, and reviews of 241 ice cream flavors across 4 brands (Ben & Jerry's, Häagen-Dazs, Breyers, and Talenti). There are a total of 21,674 reviews, with each review containing star ratings and text.

From the dataset I want to answer these questions: (i) Which brand has the most recommended products? (ii) Which brand has the most bad products? (iii) Which product has the highest rating? (iv) Which product has the lowest rating? (v) Which product that has the highest sales?

In the process of editing.
<br>

---
## Visualization

### Tableau Visualization

[![Open Notebook](https://img.shields.io/badge/Tableau-Open_Tableau-E97627?style=flat&logo=Tableau&logoColor=white)](https://public.tableau.com/app/profile/rifqiazhari)

The data for visualizations are mostly from web scrapping.
<br>
<center><img src="images/tableau.jpg"/></center>
<br>

---
<center>© 2024. Powered by Jekyll and the Minimal Theme.</center>
