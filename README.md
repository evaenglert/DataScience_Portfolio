# Data Science - Portfolio
Hi there! Please find below some projects I have worked on in the past. 


## 1. [Sign Language - real-time translation](https://share.streamlit.io/evaenglert/flykrapp)
![Image](https://raw.githubusercontent.com/evaenglert/DataScience_Portfolio/main/SignLanguage2.png)

- Website: [https://share.streamlit.io/evaenglert/flykrapp](https://share.streamlit.io/evaenglert/flykrapp)
- Repos: model: [https://github.com/rkumar-slim/flykr](https://github.com/rkumar-slim/flykr), front-end: [https://github.com/rkumar-slim/flykrinterface](https://github.com/rkumar-slim/flykrinterface)

I have worked in a team of 4 to create an app that can predict letters and digits from the American Sign Language in real-time, using the webcam. We used transfer learning (VGG-16) for the image classification part (trained on some amazing kaggle datasets) and used mediapipe & cvzone for the object-detection part. Additionally, I have build a flashcard functionality that can be used to learn the basics of ASL. For this bit, I deployed APIs through Cloud Run and FastAPI, and the whole app was made available via Streamlit Cloud. 


## 2. [Time series forcasting - hybrid ARIMA Random Forest model](https://github.com/evaenglert/RandomForestHybridModel)
![Image](https://raw.githubusercontent.com/evaenglert/DataScience_Portfolio/main/TimeSeriesForecasting.png)

- Paper: [here](https://github.com/evaenglert/RandomForestHybridModel/blob/master/Time_series_forecasting_using_a_hybrid_ARIMA_and_Random_Forest_Model%20(1).pdf)
- Repo : [https://github.com/evaenglert/RandomForestHybridModel](https://github.com/evaenglert/RandomForestHybridModel)

This work was created as a final project for the Empirical Finance Research Program by Corvinus University Budapest. I explored the idea of using hybrid models for time series forcasting, the concept originating from a [paper by G.P.Zhang](https://www.sciencedirect.com/science/article/abs/pii/S0925231201007020), who combined an ARIMA model with a neural network. I tried to replicate the structure described in the paper using MATLAB, but used a Random Forest model instead of neural networks. Even though results were not great (the baseline models performed better than the my hybird one) I summarized my work in a working paper, that you can find attached. 

## 3. [Zoopla web scraping]()

This is a still ongoing project. Since I am looking for a new apartment I wanted to set up a daily job that scrapes newly available rentals and summarizes these in a nice format. There is an already available functionality on Zoopla, however the only possiblily provided is to have a different email alert for each area. 



## 4. [Olist data exploration](https://github.com/evaenglert/data-exploration-olist)
![Image](https://raw.githubusercontent.com/evaenglert/DataScience_Portfolio/main/Olist.png)

- Repo: [https://github.com/evaenglert/data-exploration-olist](https://github.com/evaenglert/data-exploration-olist)

Data exploration of db containing 100.000 orders from the Brazilian eccomerce business Olist. Dataset was sourced from [kaggle](https://www.kaggle.com/olistbr/brazilian-ecommerce) .
Packages used: numpy, pandas, matplotlib




