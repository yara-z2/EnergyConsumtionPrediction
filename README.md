# EnergyConsumtionPrediction

# Project Overview: 
The project aims to predict household energy consumption. it also identifies high periods of consumption and estimates the related carbon emmisions.

# Goal: 
Our goal is to predict household electricity consumption, detect unusually high consumption, estimate the associated electricity-related carbon emissions and cost, and turn the findings into practical recommendations. first by comparing minute-level and hourly household electricity data first, compare Linear Regression and Random Forest on the better resolution, then detect unusually high consumption and estimate the related carbon emissions.

# Dataset: 
The dataset used in this project is the Household Power Consumption Dataset from the UCI Machine Learning Repository.
[Download the Dataset – UCI Repository](https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption)
The input file is household_power_consumption.txt. We use one column, Global_active_power (the household's average active power in kW, recorded every minute).

# Models and Tools:

for our tools and models, because this project is for our introduction to ai course we integrated one of the models we learned in class which is linear regression. The second whcih we researched about was random forest. and some of the tools were pandas, numpy, google colab.

# Project pipline:
 1. Load the data
 2. Clean and preprocess the data
 3. compare minute vs hour level data
 4. Perform EDA.
 5. Create features
 6. Split the data
 7. Train machine models
 8. Evualate and compare model performance
 9. Estimitae carbon emmisions


# Project results:
Our project showed that minute level worked better than hour level since the original dataset is in minutes. The project also showed that random forest worked better than linear regression, it also showed how much of the carbon emmisions were irregular.

# How to run:
1. Download or clone this repository.
2. Open the notebook using Google Colab.
3. Upload the dataset provided in the README and unzip it.
4. Run the notebook cells in order.

# Sustainability link: 
the project supports UN SDG 12 (Responsible Consumption and Production) by making wasteful electricity use visible, and SDG 13 (Climate Action) by estimating the emissions that could be avoided.

# Team Members:

- Yara Alzamel
- Fai Bin Khanjar 
- Aljoharah Altuwaijri

# Refrences:

- [1] United Nations, "The 17 Sustainable Development Goals," https://www.un.org/sustainabledevelopment/sustainable-development-goals/
- [2] G. Hebrail and A. Berard, "Individual Household Electric Power Consumption," UCI Machine Learning Repository, 2006. https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption

- [3] D. P. Kroese, Z. Botev, T. Taimre, and R. Vaisman, Data Science and Machine Learning: Mathematical and Statistical Methods, 1st ed. Boca Raton, FL, USA: Chapman and Hall/CRC, 2019.

- [4] G. James, D. Witten, T. Hastie, R. Tibshirani, and J. Taylor, An Introduction to Statistical Learning: With Applications in Python. Cham, Switzerland: Springer, 2023, doi: 10.1007/978-3-031-38747-0.

- [5] Climatiq, “Electricity supplied from grid—France,” based on ADEME, Base Carbone V21.0, emission factor for 2008. [Online]. Available: https://www.climatiq.io/data/emission-factor/d55e9b8d-8fc5-43ce-92be-2769c2e4ef43. 
