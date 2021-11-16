# Model Monitoring: Evidently AI edition

This Repository contains the code for MLOps Blog created by Professor Arnab Bose, Matthew Fligiel, Rupa Ghosh, and Devanshi Verma at the University of Chicago.

**Link of the blog**: https://bit.ly/3DkPPxn(https://bit.ly/3DkPPxn)


## Motivation

Machine learning models put into production have many assumptions baked into them for normal operations. For example, one of these assumptions is that the data distribution does not change between training and inference. While the former is controllable, the latter is influenced by factors that may or may not be controllable. So more often than not, a model in production may not perform per expectations set during training. This is known as model drift and needs to be detected via model monitoring. The repository contains two examples walking through model monitoring and Evidently AI.

## Data

- **Climate Model** : Takes the temperatures of 5 nearby cities (Detroit, Milwaukee, Omaha, Toronto, and  St. Louis), and predict the weather of Chicago. 

- **Plant Seedlings Classification**: Determine the species of a seedling from an image. The dataset contains 960 unique plants belonging to 12 classes at several growth stages. You can find the data [here](https://www.kaggle.com/c/plant-seedlings-classification/data).

## Structure of the repository

- Climate Model: This folder contains the codes for training, and monitoring along with Evidently AI reports for Climate Model .

- Plant Seedlings Model: This folder contains the codes for training, and monitoring along with Evidently AI reports for Plant Seedlings Classification .

## Tool Used

**Evidently AI**: There are multiple open source and commercial software implementations of model monitoring methodologies. In this article, we walk through an open source model monitoring library [evidently.ai](https://evidentlyai.com/) which got selected in YC S21. 

## MLOps Concepts Covered
We have tried to cover a spectrum of topics in drifts

1. **Data Drift**: Change in model input data that leads to model performance degradation.
2. **Concept Drift**: Statistical properties of the target variable, which the model is trying to predict, change over time in unforeseen ways. This causes problems because the predictions become less accurate as time passes.
3. **Performance Monitoring**: Examining how good or bad the existing deployed model is performing viz-a-viz when it was trained (scenario I) or during a previous time frame post-deployment (scenario II).


## Team: 

![](https://i.ibb.co/v3W6bhx/Screen-Shot-2021-10-02-at-12-02-20-PM.png)

- [Dr. Arnab Bose](https://www.linkedin.com/in/arnab-bose-phd-6369531/)

- [Matthew Fligiel](https://www.linkedin.com/in/matthew-fligiel-090a16a8/)

- [Rupa Ghosh](https://www.linkedin.com/in/rupaghosh29/)

- [Devanshi Verma](https://www.linkedin.com/in/devanshiverma/)

Please do not hesitate to contact us, if you have any questions.
