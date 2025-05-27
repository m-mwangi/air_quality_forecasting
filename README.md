# Beijing PM2.5 Forecasting Challenge  
Air pollution is a critical global issue, and PM2.5 concentrations are among the most harmful pollutants due to their ability to penetrate deep into the lungs and even enter the bloodstream. Accurate forecasting of PM2.5 concentrations is essential for timely public health interventions, such as issuing air quality advisories and enacting pollution control measures to reduce exposure and protect vulnerable populations.

This project focuses on the Beijing PM2.5 Forecasting Challenge, which aims to predict PM2.5 concentrations in Beijing using historical air quality and weather data. Several experiments are made while tuning parameters to achieve better results.

## Repository structure
air_quality_forecasting/

│── train/ # Contains the training dataset

│── test/ # Contains the test dataset

│── notebook/ # Contains the Colab notebook for model development

│── README.md # Project documentation

## Instructions for reproducing results
- Download the Datasets
  The training dataset is located train/ folder (air_quality_forecasting/train/) while
  The test file is located test/ folder (air_quality_forecasting/test/).

- Open the Notebook
  The Colab notebook, which contains the full workflow (preprocessing, model training, evaluation, and saving), is located in the notebook/ folder (air_quality_forecasting/notebook/).

- Upload the Dataset
  Upload the train and test datasets to the file browser in Colab.
  Alternatively, upload the datasets to your Google Drive and mount your drive to access them.

- Run the code
  Execute the notebook step by step to preprocess the data, train the model, and evaluate results.

## Suggestions
You can experiment by either checking parameters, model architecture or different models.
