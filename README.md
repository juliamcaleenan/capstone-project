<img src="http://imgur.com/1ZcRyrc.png" align="left" height="55px">

# Predicting rental prices and identifying ‘systemised’ listings using Airbnb data

### Final Capstone project for General Assembly Data Science Immersive course

> Part 1 - Can we predict rental prices for Airbnb properties in London? Which factors have the greatest influence on the price?   

> Part 2 - Can we use network analysis to identify ‘systemised’ listings on Airbnb?

## Introduction and aims

### Part 1
The dataset came from Inside Airbnb and was scraped on 16 December 2020. It contains ~77,000 listings for London including information on the property, the location, the host and ratings. In addition, there are over 1.1 million reviews associated with the listings.

The aim of Part 1 was to use this data with some additional engineered features (for example, using NLP on listing descriptions, doing sentiment analysis on the reviews) to predict listing prices for Airbnb properties in London and to determine which factors have the greatest influence on the price.

### Part 2
The second part of the project was inspired by an article published in February 2020 which describes in great detail an Airbnb scam uncovered by the journalist in London. The scam centres around a de facto hotel built for short-term rentals which breaches both Airbnb policies and local planning laws (London’s 90-day law).

There are duplicate listings for apartments, most listings use the same photos or mirror image photos and some of the listings don’t exist. Guests often complain of being put into a different apartment to the one they booked and sometimes apartments are double-booked. Many of the reviews and host profiles are fake or misleading.

The article identifies a network of connected host accounts behind 200 ‘systemised’ listings. Listings hosted by these accounts have many fake reviews from a small group of reviewers. All of these accounts are essentially one person, or at least one company.

The aim of Part 2 was to use network analysis to find host accounts which are connected via reviewers to identify this network and potentially other similar networks.

## Files in this repository
- [Project Presentation](Capstone_Project_Presentation.pdf): This was prepared to present the project and its findings to a non-technical audience.
- Jupyter Notebook files:
  - [Part 1 - Data cleaning](part-1/data-cleaning/)
  - [Part 1 - Exploratory data analysis](part-1/EDA/)
  - [Part 1 - Modelling](part-1/modelling/)
  - [Part 2 - Network analysis](part-2/)
