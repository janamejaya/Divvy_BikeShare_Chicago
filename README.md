Divvy is a Chicago based Bike Share service. People can rent a bike at one bike station and return it to the same or a different bike station. For each bike ride, Divvy collects some basic information such as which bike station the ride originated from, which bike station a ride terminated at, duration of the bike rental, whether the bike rider is a customer or subscriber, and if a subscriber, what is the gender and age of the rider. Divvy makes this data available to the public bi-quarterly for each year. The data is available from the website https://www.divvybikes.com/system-data 

In this repo, I present Jupyternote books which 

1. Download the data for the year 2017 from the Divvy website.
2. Perform an exploratory data analysis and constructs features for modeling.
3. Split the data into training, validation and test sets in order to train a ML/DL model.

Objective:

For the sake of this repo, give the data for the year 2017, I construct a model that predicts whether a bike ride will travel a distance of 2 km or less (class 1) or more (class 0). I train a Neural Network with a few layers in order to make these predictions. The model has a good performance with accuracy of 0.999 on the training, validation and the test datasets.

Directory Structure:
.
 - input
 - EDA\_plus\_features
 - data\_splits
 - model1

Software requirements:
- Python 3.6+
- Keras/Tensorflow

Order in which to run Jupyter Notebooks
1. download\_2017\_data.ipynb in ./input
2. eda\_divvy.ipynb in ./EDA\_plus\_features
3. test\_train\_validation\_split.ipynb in ./data\_splits
4. mlp.ipynb in model1
