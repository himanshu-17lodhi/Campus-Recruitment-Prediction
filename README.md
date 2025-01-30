# Campus Recruitment Prediction

This repository contains a machine learning-based web application to predict whether a candidate will be recruited during campus recruitment drives. The model is built using a dataset of past recruitment data, and the predictions are made available through a web interface built with Flask.

## Files in the Repository

- `app.py`: The main Flask application file that runs the web server.
- `index.png`: A screenshot of the home page of the application.
- `model.pkl`: The trained machine learning model, saved for inference.
- `notebook.ipynb`: The Jupyter notebook where the data preprocessing, model training, and evaluation are performed.
- `prediction.png`: A screenshot showing the prediction output of the application.
- `requirements.txt`: The list of required Python packages for the project.
- `runtime.txt`: The runtime environment information (for platforms like Heroku).
- `scaler.pkl`: The saved scaler object used for feature scaling during prediction.
- `train.csv`: The training dataset used to build the model.

## Project Overview

The project aims to predict the likelihood of a candidate being recruited based on various factors like test scores, interview performance, and past academic achievements. The machine learning model is trained using the dataset `train.csv`, and predictions are made using a Flask web application.
