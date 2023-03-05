# Mission-to-Mars

## Overview
SpaceForward is an aerospace company that is interested in analyzing resources on other planets, and their extraction potential. For this project, the analysis team is looking specifically at Mars.  Since the data isn't readily available in CSV or JSON format, the team will be extracting the information from publicly available websites.

## Resources
+ mars.csv
+ https://redplanetscience.com/
+ https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html
+ Software: Python 3.7.13, Jupyter Notebook

## Analysis of Results
Deliverable 1: Scrape titles and preview text from Mars news articles.  The team created a Beautiful Soup object and used it to automate browsing at [https://redplanetscience.com/](url).  The titles and previews were extracted and stored in a Python Dictionary.  

![image](https://user-images.githubusercontent.com/113741694/222990986-dbd4a193-8255-46b2-9795-a1c4fc39092e.png)

![image](https://user-images.githubusercontent.com/113741694/222991005-616ea9ca-1060-4f66-b446-dd892b2d1440.png)

Deliverable 2: Scrape and Analyze Mars Data.  Again, the team created a Beautiful Soup object and used it to automate browswing at [https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html](url).  The scraped data was then put into a Panddas DataFrame to help better analyze the data.  The team used the Mars DataFrame to answer 5 specific questions:

1) How many months exist on Mars?

![image](https://user-images.githubusercontent.com/113741694/222991199-4a1583ad-44d6-4120-bf65-165b5e5bcfb7.png)

2) How many Martian (and not Earth) days worth of data exist in the scraped dataset?

![image](https://user-images.githubusercontent.com/113741694/222991228-9d6169e8-3457-4bb0-8716-16688066d667.png)

3) What are the coldest and the warmest months on Mars (at the location of Curiosity)? 

![image](https://user-images.githubusercontent.com/113741694/222991330-f91d8759-9212-4bd5-ac08-745a1bc3cf7b.png)

4) Which months have the lowest and the highest atmospheric pressure on Mars?

![image](https://user-images.githubusercontent.com/113741694/222991359-99e90bc9-a2cd-4918-9ef0-905334e0b44d.png)

5) About how many terrestrial (Earth) days exist in a Martian year?

![image](https://user-images.githubusercontent.com/113741694/222991392-34f9dfcc-4478-4047-b8ff-a4a9e455fc0a.png)


