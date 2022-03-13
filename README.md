# final-project-genius


Hello! This is the final project in Python for MACS 30122 Computer Science with Social Science Applications 2 at The University of Chicago. Our project is: Prediction of Austin Restaurants’ Rating. The goal of our project is: Help those who want to start a restaurant business in Austin to find the important factors that could affect the restaurant rating. Figure out the contributions of some social science features (population density, people’s reactions and feedback after visiting a restaurant) to the rating. Our team members are: Zhiyun Hu, Xin Li, Linhui Wu, Yujing Sun.


Instructions to run the code:

- Make sure the data file is in the same directory as the ipython notebook or edit the ipython notebook accordingly.     
- Make sure to run the notebook in python 3 environment. Make sure all the dependencies used in the notebook are installed in the local machine.     
- Run the code sequentially as given in the notebook.


Files:

- web_scraping.ipynb: IPython notebook showing scraping from Web. tripadvisor and zipatlas.     
- yelp_reviews_analysis.ipynb: IPython notebook including reviews data clean and analysis.      
- data_cleaning_and_regression.ipynb: IPython notebook including data clean and analysis for building prediction model.


Data Sourse:

- Dataset:
  
    Yelp dataset restaurant: https://drive.google.com/file/d/1i3wH2eUaF1tD6fqk-IzPcjkFJQElpMlu/view?usp=sharing
    
    Yelp dataset reviews: https://drive.google.com/file/d/1PG1D6KgEVX5_sJ2TMCD_uxKQFeQsAVKP/view?usp=sharing
    
- Webscraping:
  
    TripAdvisor: https://www.tripadvisor.com/Attractions-g30196-Activities-c
    
    Population Density: http://zipatlas.com/us/tx/austin/zip-code-comparison/population-density.htm



Required libraries:

  [ import requests; from bs4 import BeautifulSoup; import pandas as pd; import numpy as np; import json; import re; import csv; import seaborn as sns; import matplotlib.pyplot as plt; import statsmodels.api as sm; from math import pi; from collections import Counter; from sklearn.preprocessing import StandardScaler; from sklearn.feature_extraction import text; from bokeh.palettes import Category20c; from bokeh.plotting import figure, show; from bokeh.transform import cumsum; from textblob import TextBlob; from wordcloud import WordCloud]
  
