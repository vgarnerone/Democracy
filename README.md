# Democracy

In a very good video from 'Le chat sceptique' https://youtu.be/NCHYDtA60-g, a statician explain how to predict if a country is a democracy or a dictatorship in regards of the height of the highest building.

Based on this idea, we use data to explore the differences between democratic and authoritarian regimes.

A study publish by the Economist on www.eiu.com, give for each country a democratic score.

The project is based on Python and on the pandas library and was made with Jupyter notebook.


# Summary

1) Democracy Data Analyse

Introduction and description of our data set, looking for correlations between parameters, and differences between democracy dans dictatorship.

2) Multiregression and boxplots

We use the multiregression tool to find out which parameters influence the most the democratic overall score of a country.
We split countries in four groups : Full democracy, flawed democracy, hybrid regime and authoritarian regime.Then we draw box plots showing the four quartiles of each samples for each parameters in order to understand deeper differences between political regimes.

3) Machine learning xgboost

We use a train test method to build a xgboost model that will predict the political regime of a country giving a set of parameters.

4) K-Fold Cross Validation

We use a train test method to build SVM model that will predict the political regime of a country giving a set of parameters.

5) Which country...

A serie of few questions answered using Pandas on our data.

6) Deep Learning - Neuronal Network

We use Keras from TensorFlow to create a neuronal network model to predict if a country is a democracy or not according to some demographical parameters.
