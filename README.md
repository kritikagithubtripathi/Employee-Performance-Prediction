# Machine-Learning-Approach-For-Employee-Performance-Prediction

## Overview

This project implements a machine learning model to predict employee performance based on various input parameters. It uses Flask for building a web application that allows users to interact with the predictive model.

## Demo 
Visit the [Empoyee-Performance-Prediction](https://employee-attrition-flask.onrender.com) web app

## Table of Contents

- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Application Structure](#application-structure)
- [Screenshots](#screenshots)
- [Deployment](#deployment)


## Technologies Used

* Python
* Flask
* scikit-learn
* XGBoost
* HTML/CSS

## Installation

1. Clone the repository:
   
```bash
  git clone https://github.com/kritikagithubtripathi/employee-performance-prediction.git
cd employee-performance-prediction
```
2. Install the required dependencies:
 
```bash
  pip install -r requirements.txt
```
3. Run the Flask application:
   
```bash
  python app.py
```

## Usage
* Navigate to the home page for an overview of the project.
* Explore the "About" page to understand the background of the employee performance prediction.
* Visit the "Predict" page to input data and receive predictions.
* The "Submit" page displays the prediction results.

## Application Structure

```bash
  employee-performance-prediction/
|-- Flask/
|   |-- Templates/
|   |   |-- about.html
|   |   |-- home.html
|   |   |-- predict.html
|   |   |-- submit.html
|   |-- app.py
|   |-- gwp.pkl
|-- README.md
|-- requirements.txt
|-- Employee_Performance_Prediction.ipynb

```
## Screenshots
![App Screenshot](https://github.com/kritikagithubtripathi/Machine-Learning-Approach-For-Employee-Performance-Prediction/blob/main/Screenshot/Screenshot%201.png)

![App Screenshot](https://github.com/kritikagithubtripathi/Machine-Learning-Approach-For-Employee-Performance-Prediction/blob/main/Screenshot/Screenshot%202.png)

![App Screenshot](https://github.com/kritikagithubtripathi/Machine-Learning-Approach-For-Employee-Performance-Prediction/blob/main/Screenshot/Screenshot%203.png)

![App Screenshot](https://github.com/kritikagithubtripathi/Machine-Learning-Approach-For-Employee-Performance-Prediction/blob/main/Screenshot/Screenshot%204.png)



## Deployment
This project is deployed on the Render platform. Access the live application at (https://employee-attrition-flask.onrender.com).

