# Delhi Electricity Demand Prediction

A web-based electricity demand prediction application developed as part of the **Smart India Hackathon (SIH)**. The project uses historical electricity demand data for Delhi to predict electricity load based on specific dates, times, and related features present in the dataset.

## Project Overview

Electricity demand varies with factors such as time, weather conditions, holidays, and previous electricity consumption. This project uses historical data to identify patterns in electricity demand and generate predictions based on the available input features.

The application combines a web-based frontend with a **FastAPI backend** and a **SARIMAX (Seasonal AutoRegressive Integrated Moving Average with eXogenous variables)** model for time-series analysis and prediction.

## Features

* Electricity demand prediction using historical data
* Date and time-based input and analysis
* Time-series forecasting using SARIMAX
* Historical electricity load data analysis
* Consideration of weather and calendar-related features
* Interactive web interface for presenting demand predictions
* Frontend-backend integration through FastAPI

## Tech Stack

### Frontend

* HTML
* CSS
* JavaScript

### Backend

* Python
* FastAPI
* Uvicorn
* Pandas

### Machine Learning / Forecasting

* SARIMAX
* Statsmodels

## Dataset

The project uses historical electricity demand data for Delhi. The dataset contains electricity load values associated with specific dates and timestamps, along with additional factors that can influence electricity demand.

The features used in the project include:

* Datetime
* Time
* Temperature
* Rainfall (mm)
* Wind gust (km/h)
* Rain probability (%)
* Holiday status
* Electricity load (MW)

## Methodology

The project uses historical electricity demand data along with temporal and weather-related features to analyze electricity consumption patterns. The dataset is processed using Python and Pandas, and a SARIMAX time-series model is used to identify relationships between historical load values and the available input features. The prediction functionality is integrated with a FastAPI backend, while the frontend displays the electricity demand results through a web interface.


## Role & Contributions

I primarily worked on the **frontend and backend integration** of the project.

My contributions included:

* Developing the web interface using HTML, CSS, and JavaScript.
* Designing and implementing the user-facing components for interacting with the application.
* Integrating the frontend with the FastAPI backend.
* Handling communication between the web interface and backend APIs.
* Implementing the display of electricity demand prediction results.
* Contributing to the overall integration of the forecasting functionality into the web application.

## Team

The project was developed as part of a **6-member team** for the Smart India Hackathon.

## Outcome

Developed a functional web-based application that integrates historical electricity demand data, time-series prediction, and a user interface for presenting electricity demand predictions for Delhi.

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/ishitapradhan19/sih-hackathon.git
cd sih-hackathon
```

### 2. Install the required Python packages

```bash
pip install fastapi uvicorn pandas statsmodels
```

### 3. Start the FastAPI backend

```bash
uvicorn main:app --reload
```

### 4. Open the frontend

Open index.html in your web browser after starting the FastAPI backend.

## License

This project is licensed under the MIT License.
