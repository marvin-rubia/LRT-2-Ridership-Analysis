# 2022 LRT-2 Ridership and Passenger Traffic Analysis
## Problem

![image](https://github.com/marvin-rubia/2022-LRT-2-Ridership-Analysis/assets/140475770/5049542c-3427-4f4d-993f-c7a418214c0c)

I am a regular passenger of Light Rail Transit (LRT) trains here in Metro Manila. I observe that there are business kiosks near the station's entrance and exit areas. This made me wonder: __if I would franchise a siomai-rice* business (for example), which offers instant food for our hurrying commuters, in what LRT-2 station should I place it?__ In other words, what LRT-2 station has the highest passenger traffic? 

As a curious passenger, I also like to know: what day is the most hectic (i.e. highest ridership) and least hectic (i.e. lowest ridership)? 

These are only two of the six questions I explored in this analysis. The six questions are given below and all of them try to extract LRT-2-related business and transportation insights using its daily ridership data in 2022.

1. Is there a trend for LRT-2 ridership as a function of the months?
2. How can we describe the annual passenger traffic (entry + exit) for each station? 
3. Which station has the highest daily passenger traffic on average?
4. What is the average daily ridership of LRT-2, and what day has the highest ridership on average?
5. In what station do passengers of LRT-2 tend to enter?
6. In what station do passengers of LRT-2 tend to exit?

*I have eaten too many siomai (a variant of Chinese dumplings) before or after my train rides since college.

## Plan 
Since LRT Authority is owned by the government, my plan is to get LRT-2 data from the Freedom of Information (FOI) website. Due to the long waiting time before one can get the data upon their requests (with a possibility of being unsuccessful after the wait), I am going to use the available 2022 LRT-2 data that another person already requested. (The conversation between the FOI officer and the citizen is public.) The ridership data goes from January 1, 2022 to Dec 31, 2022. These are enough to extract insights about our problem. Unfortunately, the daily ridership data for each month of 2022 are in PDF format. I have to convert the twelve PDF files into twelve Excel files before doing the data wrangling and exploratory data analysis.

![image](https://github.com/marvin-rubia/2022-LRT-2-Ridership-Analysis/assets/140475770/6b757d8f-a911-4c4b-b66c-5f0aad01900f)

## How to see my data wrangling, analysis, and insights?
Refer to the uploaded Jupyter Notebook that contains the full report, from the problem to the insights. You can view it here on GitHub or download it to run in your Jupyter environment. Check the Data folder to see the source files for the LRT-2 monthly ridership data in 2022.
