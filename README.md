# Data Engineering & Visualization Milestone 1
Exploring the Poland cars for sale
-----------------------------------------
- The project aims to explore the poland cars for sale dataset and to answer few questions been conducted on the dataset
- the source of the dataset : https://www.kaggle.com/datasets/bartoszpieniak/poland-cars-for-sale-dataset

Basic project structure 
------------------------

- The project is consisted of the two files:-
  - DE_Project.ipynb
  - README.md


EDA Process Explained
----------------------

Overview of the used dataset

The dataset that was used for this project was the 'Car_sale_ads.csv' this dataset was created by webscraping over 200,000 car offers from one of the largest car advertisement sites in Poland. The code used to collect and clean the data is available at github in the link source in kaggle.


Content
The dataset contains 208,304 observations of 25 variables.

Variables describtion:

- ID - unique ID of offer
- Price - value of the price
- Currency - currency of the price (mostly polish złoty, but also some euro)
- Condition - new or used
- Vehicle_brand - brand of vehicle in offer
- Vehicle_model - model of vehicle in offer
- Vehicle_generation - generation of vehicle in offer
- Vehicle_version - version of vehicle in offer
- Production_year - year of car production
- Mileage_km - total distance that the car has driven in kilometers
- Power_HP - car engine power in horsepower
- Displacement_cm3 - car engine size in cubic centimeters
- Fuel_type - car fuel type
- CO2_emissions - car CO2 emissions in g/km
- Drive - type of car drive
- Transmission - type of car transmission
- Type - car body style
- Doors_number - number of car doors
- Colour - car body color
- Origin_country - country of origin of the car
- First_owner - whether the owner is the first owner
- First_registration_date - date of first registration
- Offer_publication_date - date of publication of the offer
- Offer_location - address provided by the issuer
- Features - listed car features (ABS, airbag, parking sensors e.t.c)

- we ran some commands for the dataset exploration part like dataset.info(), and dataset.describe() and some other commands to check the null values and some statistical measurements related to the dataset like the count, the mean, the max, etc... .

Concluded many attributes that has null values:-

    - Vehicle_version got 70,222 null values
    - Vehicle_generation got 60,444 null values
    - Mileage_km got 983 null values
    - Power_HP got 643 null values
    - Displacement_cm3 got 1,966 null values
    - CO2_emissions got 114,257 null values
    - Drive got 15,076 null values
    - Transmission got 479 null values
    - Doors_number got 1,487 null values
    - Origin_country got 89,992 null values
    - First_owner got 143,210 null values
    - First_registration_date got 121,859 null values
    
Project Goals and Motivation for it
--------------------------------
This project is a school project that was assigned to us, to document the EDA process that we take towards this dataset. We were tasked to come up with a few research questions and explore them using the dataset at hand and indeed that is what we do. the Research questions proposed are:

  - 
  - 
  -
  -
  -
  -
  
  
  
General Description of steps taken in the project
----------------------------------------

  - As mentioned above, we first started by describing and seeing what the data is like:
  - After which we realized that there are null values in the dataset and proceed to impute the dataset.
  - After imputing / cleaning the dataset, we proceed to explore our research questions.
  - We visualized data when needed to help pass through the information to the reader / viewer in an easier to digest way.
  - All the data and in detail implementations of steps taken to reach research questions, exploring dataset, imputation techniques used are all mentioned in the           notebook markdown.
  
  


