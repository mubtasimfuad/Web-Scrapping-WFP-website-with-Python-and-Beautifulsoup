
## Task: Scrapping Web Data and analyzing it.
Source URL: https://www.wfp.org/
## Key Procedures I followed:
1.	Firstly, I Scrapped the  webpages  using the BeutifulSoup Library
2.	Found out the core domains that WFP works on 
3.	Then,  selected out the necessary data from the scrapped pages along with the data of core domains.
4.	Afterward, I made a dataframe using the those data with Pandas
5.	While, the files(e.g. country_name_details.txt, country_name_projects.txt) were being saved in the respective folder(e.g. country_name) 
6.	Then tried to demonstrate the relation between  Population VS Poverty and the output of Linear regression prediction model .
7.	But the degree of variations in the data was not feasible with the LR model. So, I applied the polynomial regression on it and it works better.
8.	Then, I considered the data table to demonstrate the relation between Population VS the ratio of  Stunted Children and the Prediction model by applying Linear regression on it 9.	But the degree of variations in the data was not feasible again with the LR model. So, I applied the polynomial regression on it and it works better.
 

## Key Findings: 
•	As the graph line(Fig:3-4) of actual data suggests that, there is significant effect  of the size of population to intensify the poverty problem. Though as per the graph tells, size of the population of some country  didn’t cause much affects in poverty , as they must have some other domain effect to sustain it.
•	As the graph line(Fig:5-6) of actual data suggests that, there is significant effect  of the size of population to increase the number of stunted children. Though as per the graph tells, size of the population of some country didn’t cause much affects in increasing stunted children, as they must have some other domain effect to sustain it.
•	To make  a prediction model on such data collection that satisfies y= b0+b1x1+ b2x12+ b2x13+...... bnx1n, we must try using polynomial regression mode.






~: Mubtasim Fuad

