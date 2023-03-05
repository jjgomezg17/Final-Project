# Final-Project

## Selected topic

### The main topic of the project is to create a tool that evaluates the macroeconomic conditions of different countries and industries, by analyzing news articles through PESTEL analysis, to identify potential opportunities for entrepreneurship.

## Reason why of the selected topic

### The main topic of the project is to create a tool that analyzes the macroeconomic environment of different countries and industries and provides a guide for individuals or businesses to identify countries with the best economies and growth potential, as well as the most beneficial industries in each case. The tool uses data from the World Bank database and news articles obtained through the Bing API to evaluate the political, economic, social, technological, environmental, and legal aspects of the chosen countries and industries, and to predict their overall health score. The project involves data cleaning and preprocessing, data analysis, machine learning, and data visualization. 

### The selected topic is valuable because it addresses a common challenge for entrepreneurs who want to expand their businesses into new countries or industries, but are unsure where to start due to the lack of knowledge and insights into the economic and social conditions of those areas. By leveraging PESTEL analysis and the Bing Search API, the project aims to provide a comprehensive and up-to-date evaluation of various countries and industries, allowing entrepreneurs to make more informed decisions about where to invest their time and resources.

## Description of the sources of data

### The project uses several sources of data. The World Bank database is used to extract information related to the GDP and GDP growth rate of various countries. The Ease of Doing Business score is also obtained from the World Bank database. Bing Search API is used to extract news articles related to specific industries and countries. Finally, a labeled dataset of news headlines categorized as positive or negative is used to train a machine learning model for sentiment analysis, this database comes from tweets from http://help.sentiment140.com/for-students/

## Questions to answer with the data

### The project aims to answer several questions to help entrepreneurs make informed decisions. Some of these questions include:
#### What are the top countries to invest in based on their GDP, GDP growth rate, and ease of doing business score?
#### What industries are thriving in these countries?
#### What is the current state of the political, economic, social, technological, environmental, and legal (PESTEL) factors for each country and industry?
#### What are the most relevant and recent news articles related to a particular country, industry, and category?
#### What is the sentiment of the news articles related to a particular country, industry, and category?

## Description of the communication protocols

### The communication between the various components of the project likely involves API calls, such as the Bing Search V7 API, to retrieve and process data from various sources. The data is then processed using Python programming language, and the results are visualized using Tableau.

### As the only person working on this project, I have established communication protocols with myself to ensure that I can complete the project on time. I have set goals and deadlines for each phase of the project and I have been tracking my progress regularly. Whenever I face any challenges or have questions, I document them and find solutions by conducting research and consulting relevant resources. Additionally, I prioritize my tasks based on their urgency and importance and I make sure to take breaks and maintain a healthy work-life balance to avoid burnout. Through these protocols, I am confident that I can successfully complete the project within the given timeframe.

## Steps to complete this analysis

### 1. Extract the GDP (current US$) for 2021 for each country from the World Bank database and keep the top 25 countries.
### 2. Evaluate the GDP growth (annual %) of the last 6 years from 2021 for all the countries and keep the top 25.
### 3. Merge both tables and keep the countries that are in both.
### 4. Obtain Ease of doing business score (0 = lowest performance to 100 = best performance) from the World Bank database and keep only the countries with a score greater than 77.
### 5. Merge the databases again to only keep the top 3 countries evaluating these three characteristics.
### 6. Choose all the industries that currently exist according to the World Bank.
### 7. Create a database that makes all the combinations between the chosen countries, the existing industries and the categories to study PESTEL (political, economic, social, technological, environmental and legal).
### 8. Use the Bing API to get the most relevant and current news related to the country, industry and category to study.
### 9. Use a database with headlines categorized between positive and negative to train a machine learning model to be able to categorize the headlines of the extracted news.
### 10. Categorize the news and calculate an overall health score for each aspect of PESTEL for each industry and each country.
### 11. Use Tableau to display the results in graphs and a matrix that shows the industries by country with the score obtained in each aspect of the PESTEL and a general score.

