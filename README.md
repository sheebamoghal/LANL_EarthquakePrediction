# LANL_EarthquakePrediction

Abstract: 

In this project, you will address when the earthquake will take place. Specifically, you’ll predict the time remaining before laboratory earthquakes occur from real-time seismic data.

Market Outlook: 

![image](https://user-images.githubusercontent.com/93851545/180209549-9228a155-1a85-45cc-b255-9a8e6f4cf93a.png)

Features :

A) Indepedent variables: 1) acoustic_data - the seismic signal [int16] 2) time_to_failure - the time (in seconds) until the next laboratory earthquake [float64]

B) Dependant variable: 1) seg_id - the test segment ids for which predictions should be made (one prediction per segment)

## Overview of the Problem

Forecasting earthquakes is one of the most important problems in Earth science because of their devastating consequences. Current scientific studies related to earthquake forecasting focus on three key points: when the event will occur, where it will occur, and how large it will be.

For this project, we have built an supervised learning model using XGBoost and SVR.


## Libraries Used

- Pandas
- Numpy
- Seaborn
- Matplotlib
- sklearn
- gc
- Catboost

## License

[Kaggle](https://www.kaggle.com/terms)

## Data 

The data is taken from [here](https://www.kaggle.com/c/LANL-Earthquake-Prediction)


## Appendix

Through this project, I tried out an ensemble method (Catboost) and SVR. I was taught SVM at Imarticus but tried SVR (Support Vector Regression). Although this is the most basic ML project, it was still interesting to work on this especially for visualisation.  

## Contributing

Contributions are always welcome! However, a prior intimation to my work email is important.
