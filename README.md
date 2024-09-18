# Classify-country-of-origin-for-Wikipedia-user-contributions-on-Zambian-Wikipedia-pages.

1. Introduction
In the era of globalization and digital collaboration, understanding the geographic origins of contributions to online platforms is of significant interest. Wikipedia, one of the most widely used repositories of knowledge, allows users from around the world to edit and contribute to its vast array of articles. These contributions can be analyzed to glean insights into the demographics of contributors, particularly their countries of origin.
The objective of this project is to classify the country of origin for user contributions to Zambian Wikipedia pages, such as the Zambia page. This involves extracting edit histories from Wikipedia, processing the data to obtain relevant metadata, and employing machine learning techniques to predict the contributors' countries of origin based on features derived from their edits.
Understanding where contributions are coming from can provide valuable insights into the global reach and impact of Wikipedia content related to Zambia. This information can be useful for various purposes, including academic research, understanding global engagement with specific topics, and improving the targeting of information campaigns or educational resources.


2. Libraries and Imports
The following libraries are used in the project:
requests:
Used for making HTTP requests to Wikipedia's API to fetch edit histories.
pandas:
Provides data structures and data analysis tools. Used for handling data frames and various data manipulation operations.
ipwhois:
Used for performing WHOIS lookups to obtain information about IP addresses, specifically their country of origin. This library helps in identifying the geographic location of IP addresses.
sklearn.model_selection:
Provides tools for splitting the dataset into training and testing sets and for performing hyperparameter tuning (GridSearchCV).
sklearn.ensemble:
Contains ensemble algorithms like RandomForestClassifier, used for building the machine learning model.
sklearn.metrics:
Used for evaluating the performance of the machine learning model (e.g., classification report, confusion matrix, accuracy score).
matplotlib and seaborn:
Libraries for creating visualizations to better understand the data and model performance.
