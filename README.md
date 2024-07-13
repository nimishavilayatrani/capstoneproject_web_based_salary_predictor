# Capstone Project: Web-Based Salary Predictor

This repository contains files necessary for a web-based salary predictor project.

## Project Structure

The project is organized into four main parts:

### model.py

This file contains the code for the Machine Learning model. It predicts employee salaries based on training data from the 'hiring.csv' file.

### app.py

This file hosts Flask APIs. These APIs receive employee details either through a GUI or API calls, compute the predicted salary using our model, and return the result.

### request.py

This script utilizes the `requests` module to call APIs defined in `app.py`. It then displays the predicted salary value.

### templates

This folder includes an HTML template. It allows users to input employee details and displays the predicted salary.

## Prerequisites

To run this project, ensure you have the following dependencies installed:

- Scikit Learn
- Pandas
- Flask
