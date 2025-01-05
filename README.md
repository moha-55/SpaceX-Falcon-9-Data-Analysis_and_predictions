# SpaceX Falcon 9 Data Analysis and Predictions

## Project Overview

This project aims to analyze historical SpaceX Falcon 9 launch data and build predictive models to determine the likelihood of successful booster landings. The insights and predictions derived from this project could provide valuable information for aerospace enthusiasts, data scientists, and anyone interested in the future of space exploration.

## Features

Exploratory Data Analysis (EDA): Understand trends, patterns, and key metrics in the Falcon 9 launch data.

Data Visualization: Present findings through compelling visualizations.

Predictive Modeling: Build and evaluate machine learning models to predict the success of Falcon 9 booster landings.

## Datasets

The analysis leverages data from SpaceX's publicly available datasets. Key attributes include:

Launch date and time

Booster version

Launch site

Payload mass

Orbit type

Landing outcome

## Installation

To run this project locally, follow these steps:

1. Clone the Repository:
```
git clone https://github.com/moha-55/SpaceX-Falcon-9-Data-Analysis_and_predictions.git
cd SpaceX-Falcon-9-Data-Analysis_and_predictions
```

2. Set Up a Python Environment:
 Install Python 3.8 or higher and create a virtual environment:
```
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
```
3. Install Required Packages:
```
pip install -r requirements.txt
```
4. Download the Data:
```
requests.get("https://api.spacexdata.com/v4/rockets/"+str(x)).json()
```

