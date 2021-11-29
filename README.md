# Starbuck Captone Project
Udacity Data Science Nanodegree

### Introduction
The project is the capstone project set up for the completion of Udacity Data Scientist Nanodegree. The reason why I chose this project is not only because I am a coffee aficionado, but also I want to have exposure to how to build up a recommendation system to distribute promotional offers to customers, which would generate sales leads for the business to better predict sales through the process. In terms of marketing analytics, recommendations of promotional offers are the biggest challenge that has a lot of potentials to grow business.

### Built with
- Python Pandas
- Python NumPy
- Python Sklearn
- Python Matplotlib

### This project is divided in the following key sections:
- Exploratory data analysis with data visualization
- Data preprocessing and cleanning
- Variable Creation and data manipulaiton
- Train a Recommendation System to recommend top 3 offers from our portfolio dataset
- Train a classification to compute the probability of offer being viewed by customers
- A deep dive into recommendation results 
- Improvement

### Code and data
The `data` folder contains in three files:

* portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
* profile.json - demographic data for each customer
* transcript.json - records for transactions, offers received, offers viewed, and offers completed

Here is the schema and explanation of each variable in the files:

**portfolio.json**
* id (string) - offer id
* offer_type (string) - type of offer ie BOGO, discount, informational
* difficulty (int) - minimum required spend to complete an offer
* reward (int) - reward given for completing an offer
* duration (int) - time for offer to be open, in days
* channels (list of strings)

**profile.json**
* age (int) - age of the customer 
* became_member_on (int) - date when customer created an app account
* gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
* id (str) - customer id
* income (float) - customer's income

**transcript.json**
* event (str) - record description (ie transaction, offer received, offer viewed, etc.)
* person (str) - customer id
* time (int) - time in hours since start of test. The data begins at time t=0
* value - (dict of strings) - either an offer id or transaction amount depending on the record

All codes and analysis works are contained in the file `Starbucks_Capstone_notebook.ipynb`


Acknowledgements

- Udacity for providing an amazing Data Science Nanodegree Program
- Richard Sharp, Data Scientist at Starbucks, provides the dataset for the capstone project.
