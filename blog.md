# How to relate Boston AirBNB Residences to the renters and their satisfaction

![intro_image](https://github.com/fatma-hassanein/BostonAirBNB_Dataset_Analysis/blob/main/Analysis_introImage.jpg?raw=true)

## Overview

There are a lot of places to go around the world and renting houses became the new trend for tourism and short stay for people who are facing budget crunches but at the same time, cannot bear to be a Wanderlust.

Boston is the capital and most populous city of the Commonwealth of Massachusetts in the United States, and the 21st most populous city in the United States. Its rich history attracts many tourists, with Faneuil Hall alone drawing more than 20 million visitors per year. It is also a thriving center of scientific research and considered to be a global pioneer in innovation and entrepreneurship, with nearly 5,000 startups. That is why it is perfectly normal to attract a lot of people to visit it every year and even move to it for the sake of work opportunities, business or education.

In this blog, I want to show some results after using Boston AirBNB dataset to perform some analysis and find out more information about the renting times, prices and the availability of residences throughout the year. This will may help to be a start of a deeper analysis and creating a model to help predict more scientifically defined prices or improve renters experience and make use of this great city attractive aspects.

## Business Understanding

My main focus for my analysis was to answer the below questions:

1. When was the most expensive month to rent in Boston ?
2. What is the average availability each month ?
3. What is the most used cancelation policy in Boston ?
4. What is the average review score for Boston residences ?
5. Is the reviews correlated with the price ?

I used the calendar and the listings files to be able to extract analysis about these questions and some how reach a good answer for my readers. 
In the next section, you will find explanation for each question in brief and a figure to visualize the findings and facilitate understanding.

## Findings

#### *Q1. When was the most expensive month to rent in Boston ?*

To answer my first question, an analysis was done by averaging the renting prices of residences for a month and plotting the trend for the available year as shown in the figure below.

![figure_1](https://github.com/fatma-hassanein/BostonAirBNB_Dataset_Analysis/blob/main/images/figure1.png?raw=true)

The figure showed significant increase in the prices aprroaching the end of the year and Christmas Holidays. 
November, December and January ranked to have the highest prices throughout the year, this is expected since most of the world has higher renting prices during holidays specially New Year's Eve.

#### *Q2. What is the average availability each month ?*

For this question, I wanted to analyze the occupation of the residences in Boston throughout the year so I measured the availability each month and plotted it as well in the figure below.

![figure_2](https://github.com/fatma-hassanein/BostonAirBNB_Dataset_Analysis/blob/main/images/figure2.png?raw=true)

It shows that the occupation increased during almost the same months that the prices increased which is near the Holidays season and during the Winter.
This indicates that Boston is one of the targeted destinations during Winter and Holidays season.

In my next three questions, I wanted to figure out the aspects that can affect or be affected by the price so I made some analysis to study some of the properties in the dataset and correlate its relation to the price if needed.

#### *Q3. What is the most used cancelation policy in Boston ?*

Well, I looked at the cancellation policies to find if there is a specific policy used mostly around Boston and then, I checked as well if the cancelation policy is correlated with the prices offered for this residence. 

The below figure showed that strict policy was the mostly used at that time followed by the flexible and the moderate policies.

![figure_3](https://github.com/fatma-hassanein/BostonAirBNB_Dataset_Analysis/blob/main/images/figure3.png?raw=true)

Moreover, in the second figure below, it is obvious that the policies become more strict when the price of the resident is more expensive which some how makes sense since as a resident owner, the place is probably more valuable and affecting more his/her revenue in case of cancelation.

![figure_4](https://github.com/fatma-hassanein/BostonAirBNB_Dataset_Analysis/blob/main/images/figure4.png?raw=true)

#### *Q4. What is the average review score for Boston residences ?*

Analysis was done on the available reviews scores in Boston. 
The results as shown below in the figure were very positive showing that most renters are very satisfied with theier residences which is a very encouraging indicator to recommend AirBNB as an option for residences renting in Boston. 

![figure_5](https://github.com/fatma-hassanein/BostonAirBNB_Dataset_Analysis/blob/main/images/figure5.png?raw=true)

#### *Q5. Is the reviews correlated with the price ?*

Further analysis was done to correlate the relation between reviews and prices but turned out to be a bit disappointing. 
That is because as shown in the below figure, price is not that related to the customer satisfaction and his/her review about the residence.

![figure_6](https://github.com/fatma-hassanein/BostonAirBNB_Dataset_Analysis/blob/main/images/figure6.png?raw=true)

## Conclusion

Suming all up after these long analysis:
* It seems like Boston is a touristic destination specially during Winter and Holiday season. 
* The prices of its rentals increase during these times and the occupation increases.
* The cancellation policies are divided almost equally between strict and moderate to flexible but the policy can be a great indicator for the offered price since they turned to be correlated.
* The reviews average is significantly great in Boston rentals but it is not related to the price of the resident which can be a start of a new analysis to find out more aspects that can correlate with the renters satisfaction like the location of the place, its quality and size.
