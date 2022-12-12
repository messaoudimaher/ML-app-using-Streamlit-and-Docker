# Diabetes Prediction App [![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/arunnthevapalan/diabetes-prediction-app/app.py)
Streamlit Web App to predict the onset of diabetes based on diagnostic measures. 

## Data

The data for the following example is originally from the [National Institute of Diabetes and Digestive and Kidney Diseases](https://www.niddk.nih.gov/) and is [available on Kaggle.](https://www.kaggle.com/uciml/pima-indians-diabetes-database) The data contains information on females at least 21 years old of Pima Indian heritage.
Since the data has been added to the `data/` directory, cloning this repository would suffice.

## Getting Started
Open the terminal in you machine and run the following command to access the web application in your localhost.
```bash
streamlit run app.py
```

## Run on Docker
Alternatively you can build the Docker container and access the application at `localhost:8051` on your browser.
```bash
docker build --tag app:1.0 .
docker run --publish 8051:8051 -it app:1.0

## Acknowledgements

[Kaggle](https://kaggle.com/), for providing the data for the machine learning pipeline.  
[Streamlit](https://www.streamlit.io/), for the open-source library for rapid prototyping.
