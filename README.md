# World GDP and COVID-19 Case Visualizer

Collaborators: Miku Nambara (https://www.linkedin.com/in/mikunambara/), Mugdha Sinha (https://www.linkedin.com/in/mugdha-sinha-255043231/), and Isabella Blair (@isabellagblair)

This repository contains our BME 231: Foundations of Biomedical Computing final project. The premise of this project was to apply machine learning concepts and Python data science techniques we had learned in class to a real world biomedical issue. We attempted to analyze world GDP and Covid-19 case data in order to create a predictive model that could potentially predict mortality rates for countries in future pandemics with the goal of determining which nations would be most affected so that more resources could be directed there for prevention and case minimization. 

-- 

For the first part of this project, we imported and cleaned up two csv files from Kaggle, one containing world GDP information per capita and the other containing various information about Covid-19 cases worldwide per country. This process involved a lot of dataframes, finding missing values, nonsensical values, and then more dataframes. Eventually, we were able to combine the Covid-19 data with our GDP data and merge them on their country names. We then applied several machine learning models (SVM, KNN, Decision Tree, and Gaussian Naive Bayes) to the data in order to determine which model was best at predicting the Covid-19 mortality rate of countries based on their GDP. 

As a secondary addition to this project, we explored GeoPandas functionality and created a choropleth map of the world with world GDP in the background and varying sized markers over each country to represent their reported number of Covid-19 cases. This was super fun!

We came to the conclusion from our low accuracy scores that there is no strong correlation between GDP and mortality rate, confronting westernized superiority attitudes in the face of a global pandemic.
