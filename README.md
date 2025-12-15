# weather-parameters-prediction-ML
Date Assigned: November 18, 2025 Date Submitted: December 12, 2025

This project was an assignment for CISC484: Intro to Machine Learning, which is being taught in the Fall of 2025 at the University of Delaware by Professor Xu Yuan. This class is an undergraduate course within the Computer and Information Sciences department at the University of Delaware College of Engineering. The objective of this course is to introduce students to the key concepts and techniques of machine learning.

This specific project involved using the Long Short-Term Memory (LSTM) model in order to make predictions about four different weather parameters: temperature, wind speed, humidity, and air pressure. The goal was to train a model that took 12 consecutive hours of weather as inputs and produced weather predictions for the following four hours as outputs. 

For this project, Professor Yuan provided some demo code with an LSTM model that was built for a finance problem. It was up to students to create LSTM models in Jupyter Notebook that could be applied to a weather parameters problem such as this one. 

For my project, I decided to create four separate LSTM models, one for each weather parameter. These models are labeled within the 'LSTM Weather Code' folder of this repository. For each model, the training and testing losses were graphed over each epoch. Additionally, the predictions were graphed against the actual values by hour for each weather parameter. Finally, the report submitted to Professor Yuan is located within the 'report' folder.

Professor Yuan's University of Delaware page: https://www.cis.udel.edu/people/faculty/xu-yuan/