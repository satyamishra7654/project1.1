Predicting Car Price using Random Forest algorithm
Deciding whether a used car is worth the posted price when you see listings online can be difficult.
Several factors, including mileage, make, model, year, etc. can influence the actual worth of a car. From
the perspective of a seller, it is also a dilemma to price a used car appropriately[2-3]. Based on existing
data, the aim is to use machine learning algorithms to develop models for predicting used car prices.
For this project, we are using the dataset on used car sales from all over the United States, available on
Kaggle. The features available in this dataset are Car Name, Manufecturing Year,	Selling Price,	Present Price, Kms Driven, Fuel Type,	Seller_Type and Transmission.

The model is divided into the following sections:
-Data understanding and exploration
-Data cleaning
-Data preparation
-Model building and evaluation

Algorithm used- Random Forest
Random Forest is an ensemble learning based regression model. It uses a model called decision
tree, specifically as the name suggests, multiple decision trees to generate the ensemble model
which collectively produces a prediction. The benefit of this model is that the trees are produced in
parallel and are relatively uncorrelated, thus producing good results as each tree is not prone to
individual errors of other trees. This uncorrelated behavior is partly ensured by the use of Bootstrap
Aggregation or bagging providing the randomness required to produce robust and uncorrelated
trees. This model was hence chosen to account for the large number of features in the dataset.
