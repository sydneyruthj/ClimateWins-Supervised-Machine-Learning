# ClimateWins Machine Learning Analysis

### ClimateWins is interested in using machine learning to help predict the consequences of climate change around Europe and, potentially, the world. This project includes determining which areas can use machine learning, looking at data that already includes answers so that machine learning can be trained to recognize similar answers (supervised learning), and communicating what was found and how it will affect ClimateWins’ strategy.
### My final deliverable is a [Powerpoint Presentation](ML1pres.pdf)
## Objective
#### Use machine learning to help predict the consequences of climate change for a European nonprofit organization.
## Data
#### [](https://www.kaggle.com/datasets/asaniczka/top-spotify-songs-in-73-countries-daily-updated/data)
#### The data used for this project is from the [European Climate Assessment & Data Set Project](https://s3.amazonaws.com/coach-courses-us/public/courses/da-spec-ml/Scripts/A1/Dataset-weather-prediction-dataset-processed.csv) and has been collected on a daily basis from 18 different weather stations across Europe, spanning from the late 1800s to 2022. These stations have recorded data on temperature, wind speed, snow, radiation, cloud cover, and more. A [seperate data set](https://images.careerfoundry.com/public/courses/da-spec-ml/Scripts/A1/Dataset-Answers-Weather_Prediction_Pleasant_Weather.csv) was also incorporated that measures whether or not the weather on a specific day in Europe was pleasant or not.
#### Like all data, there is a potential for bias in this set, but that bias is relatively minimal. The values recorded here are all objective measures that have been consistently recorded. Any potential bias comes from the technology used to measure these variables and the way they have changed since the late 1800s.
#### There are also a number of weather stations whose data does not span the entire time at which we are interested in looking (Gdansk, Roma, and Tours), which we’ll be excluding from our analysis. 

## Tools
#### I performed my analysis using Python in Jupyter Notebooks. Algorithms I used for this analysis include Gradient Descent, K-Nearest Neighbor (KNN), Decision Trees, and Artificial Neural Network (ANN).
## Resources
#### This project is part of my curriculum for the Career Foundry Data Analytics Bootcamp. The project brief for this independent study can be found [here](https://s3.amazonaws.com/coach-courses-us/public/courses/da-spec-ml/Project%20Briefs/Machine-Learning-with-Python-Achievement-1-Project%20Brief.pdf).
