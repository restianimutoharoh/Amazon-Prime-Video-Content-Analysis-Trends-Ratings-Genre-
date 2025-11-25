# **Amazon Prime Video Content Analysis: Trends, Ratings & Genre**

![alt text](https://github.com/restianimutoharoh/Amazon-Prime-Video-Content-Analysis-Trends-Ratings-Genre-/blob/master/Amazon%20Prime.jpg?raw=true)


## Executive Summary

### *Number of Title per Year*

### Problem 

What is the trend in the number of movies and TV shows added each year? 

###  Insights

* The amount of Prime Video content jumped sharply to 1,425 titles in 2021.
* This increase was largely triggered by the COVID-19 pandemic and the ease of access factor.

### Recommendations

* Capitalize on the post-pandemic trend by strengthening customer retention.
* Strengthen accessibility and continue the strategy of adding quality content to maintain growth momentum.


### *Most Popular Genre by Year*

### Problem 

What are the most available genres?

###  Insights

* The Drama genre is the most popular on Prime Video, driven by relevant and immersive stories.
* The genre's primary audience is adults, with the majority being female.

### Recommendations

* Prioritize the acquisition of Drama content, specifically targeting the female adult audience.
* Use content marketing and personalization strategies that focus on this core audience.


### *Top Rating by Year*

### Problem 

What is the distribution of ratings (e.g., G, PG, R) for movies and TV shows?

###  Insights

* The 13+ rating is the most dominant content on Prime Video due to its broad themes, which appeal to the platform's core teenage and adult user base.

### Recommendations

* Prioritize acquiring and producing 13+ content to meet audience demand.
* Implement focused marketing campaigns and diversify sub-genres within this rating to attract and retain the core audience.


### *Movie & TV Show*

### Problem 

What is the comparative number of movies and TV shows on the platform?

###  Insights

* Movies are strongly preferred over TV shows on Prime Video, making up 78.5% of total viewing time.
* This preference is driven by shorter durations and broader themes offered by movies.

### Recommendations

* Prioritize acquiring and producing movies to meet this high demand.
* Optimize the TV show strategy by focusing on shorter series, and use marketing to highlight movies as a time-efficient entertainment choice.


### *Duration by Type*

### Problem 

Changes in the average duration of movies and TV shows from year to year. Are movies getting longer or TV shows getting shorter?

###  Insights

* The long duration of TV shows poses a risk of viewer boredom, causing them to switch to movies, which are preferred due to their concise length.

### Recommendations

* Prioritize acquiring mini-series to reduce audience saturation.
* Maintain and expand the catalog of movies with popular durations (around 90 minutes) while ensuring consistent story quality for longer TV shows.


## Introduction

Amazon Prime Video is a global video streaming service developed by Amazon, offering thousands of movies and TV shows to be watched on demand. The service is one of the main benefits included with an Amazon Prime subscription. Here is a summary of the key points regarding the Amazon Prime Video service:

* **Subscription Service:** This streaming service is part of the Amazon Prime subscription, which provides access to thousands of content at no additional cost.
* **Content Catalog:** Offers a diverse selection, including movies, TV shows, as well as exclusive home-grown content known as “Amazon Originals.”
* **User Features:** Supports streaming in HD and 4K quality, allows downloads for offline viewing, and also provides the option to rent or purchase the latest content.
* **Subscription Model:** Amazon now offers a subscription model with ads and an ad-free option for an additional fee.


### *Project Objectives*

Analyze and present deep insights into the catalog of movies and TV shows on Amazon Prime Video through an interactive dashboard.

### *Analysis Focus*

This project will focus on identifying key year-on-year trends by release year (release_year), comparing characteristics between movies and TV shows (type), and evaluating the distribution of rating and list_in (genre) content.

### *Expected Results*

The dashboard is expected to provide a clear understanding of the evolution and composition of content on the platform, which can be used as a basis for strategic decision-making regarding future content acquisition.


## Data Source

This analysis project will dive into comprehensive data from Amazon Prime Video, sourced from Kaggle, covering movies and TV shows released from 1920 to 2021. The dataset consists of 12 columns, including show_id (with 9,668 unique values), type, title, director, cast, country, date_added, release_year, genre, rating, and duration. By exploring this data, we will gain valuable insights into the evolution of content on the platform, which can serve as a strategic foundation for future content acquisition and production decisions.


## Analysis Approach

This dataset consists of 12 columns with 9,669 rows from the list of movies and tv shows on Prime Video. In the dataset there are several columns that have no or null values, to avoid errors in data interpretation, data cleaning is required. The data cleaning process is to clean columns and rows that are considered irrelevant and have null values, such as: date, country, cast, director, and description columns. Data cleaning resulted in a total of 9332 rows to enter the analysis process.

**In the Outlier Detection process, an outlier analysis is performed which calculates the quartile value in the release year column. This calculation is done to identify outliers by calculating the values in Quartile 1, Quartile 3, IQR (Interquatile Range), Upper Quartile, and Lower Quartile.**


## **Dashboard Analysis: Unlocking Insights from Amazon Prime Video**

![alt text](https://github.com/restianimutoharoh/Amazon-Prime-Video-Content-Analysis-Trends-Ratings-Genre-/blob/master/Full%20Dashboard.png?raw=true)




![alt text](https://github.com/restianimutoharoh/Amazon-Prime-Video-Content-Analysis-Trends-Ratings-Genre-/blob/master/Number%20of%20Title%20per%20Year.png?raw=true)


###  Insights

* **Significant Content Growth:** In 2021, the number of movies and TV shows on Prime Video jumped sharply to 1,425 titles. This reflects a significant surge in production and content addition.
* **COVID-19 as a Major Catalyst:** The COVID-19 pandemic served as a major driving factor in changing consumer habits, with people turning to streaming services for entertainment while at home.
* **Importance of Accessibility:** The ease of accessing services anywhere and anytime is a key factor supporting the growth of viewership and subscribers.


![alt text](https://github.com/restianimutoharoh/Amazon-Prime-Video-Content-Analysis-Trends-Ratings-Genre-/blob/master/Most%20Popular%20Genre%20by%20Year.png?raw=true)


###  Insights

* **Drama Genre Domination:**  The Drama genre is the most popular genre with the highest number of viewers, showing that Prime Video audiences are highly interested in in-depth and relatable stories.
* **Emotional Appeal:** The popularity of the Drama genre is driven by its ability to offer stories that relate to everyday life, such as family and friendship.
* **User Segmentation:** The Drama genre audience is predominantly adult and dominated by female users, indicating a clear and specific market segmen.



![alt text](https://github.com/restianimutoharoh/Amazon-Prime-Video-Content-Analysis-Trends-Ratings-Genre-/blob/master/Top%20Rating%20by%20Year.png?raw=true)


###  Insights

*  **13+ Content Domination:** The 13+ rating is the highest rating with the largest amount of content on Prime Video.
* **Broad Theme Appeal:** The popularity of this rating is due to more diverse and interesting themes, which suit the teen to adult audience.
* **Audience Alignment:** The dominance of the 13+ rating aligns well with Prime Video's user segment, which is predominantly in the teen and adult age range.


![alt text](https://github.com/restianimutoharoh/Amazon-Prime-Video-Content-Analysis-Trends-Ratings-Genre-/blob/master/Movie%20%26%20TV%20Show.png?raw=true)


###  Insights

* **Strong Preference for Movies:** 78.5% of total viewing on Prime Video is movies, indicating a much greater user preference for movies over TV shows.
* **Duration and Storyline Factors:** This preference is influenced by shorter movie durations and themes and storylines that users find broader and more interesting.


![alt text](https://github.com/restianimutoharoh/Amazon-Prime-Video-Content-Analysis-Trends-Ratings-Genre-/blob/master/Duration%20by%20Type.png?raw=true)


###  Insights


* **Impact of TV Show Duration:** The long and season-long duration of TV shows has the potential to bore viewers and switch to movies, especially if the storyline is inconsistent.
* **Movie Duration Preferences:** Movies of around 91 minutes are one of the most widely available movie durations, indicating the audience's preference for concise and compact content.




