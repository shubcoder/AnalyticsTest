# Graduate Data Analyst: Assessment

Please refer to the accompanying email for the deadline for this task. You may access the internet/refer to other sources for help or inspiration if you wish.

# Part1

This part will consist of two coding exercises, A and B. We would like you to answer the following questions using the code-based analytical tool of your choice (e.g. Python, R).

## Exercise A: 
You have a device; this device shows a sequence of changes in electro-magnetic charges (your puzzle input). Input values are fed into your device. If the input value of 6 is displayed this means the last charge value will increment by 6 ; a negative value like -3 will result in a decrease of 3 of the last charge value. 
 
Here we have an example; consider the inputs of +1, -2, +3, +1. Starting from the charge value of zero. The device's last charge value will be 3.
  
Starting with a charge value of 0, what is the value of the last charge after all the inputs have been applied? Your exercise input is saved here https://github.com/Lambeth-DAI-Team/AnalyticsTest/tree/main/data. 


## Exercise B: 
Now you will need to calibrate your device. In order to do this your task is to locate the first charge value that is reached twice. 
 
Again, as an example and using the same list of charges above, the device would loop as below:
 
    The initial charge value is 0,  a change of +1 which results in a current charge of 1.
    The last charge value is  1, a change of –2  which results in a current charge of -1.
    The last charge value is -1, a change of +3 which results in a current charge of  2.
    The last charge value is 2, a change of +1 which results in a current charge of 3.
    > End of input values reached,  start again from the beginning <
    The last charge value is 3, a change of +1 which results in a current charge of  4.
    The last charge value is 4, a change of -2 which results in a current charge of 2, this value has already been seen. 
 
In this example, the first charge value reached twice is 2. Note that your device might need to repeat its list of inputs many times before a duplicate is found. Also, note that duplicates can be found while in the middle of processing the list of inputs. 

Starting with the initial charge value of 0. What is the first duplicated charge found? 
Your puzzle input is the same as Exercise A and its saved here https://github.com/Lambeth-DAI-Team/AnalyticsTest/tree/main/data. 


# Part 2

This exercise uses two publicly available data files. The first file contains population estimates for the UK at local authority level from the 2021 Census:

https://www.ons.gov.uk/peoplepopulationandcommunity/populationandmigration/populationestimates/datasets/populationandhouseholdestimatesenglandandwalescensus2021

The second dataset is a population time series for the UK from 1971 to 2020:

https://www.ons.gov.uk/peoplepopulationandcommunity/populationandmigration/populationestimates/datasets/populationestimatestimeseriesdataset


## Tasks:
Please create visualisations for each task. We are looking for clear, interpretable visualisations that are suitable for sharing with the public.

We would like you to answer the following questions using the code-based analytical tool of your choice (e.g. Python, R). 

## Exercise C:
Visualise the distribution of total usual resident population across all local authorities. Could we say that the data is normally distributed?

## Exercise D:
Create a visualisation of the distribution of population by five-year age bands by sex in Lambeth. 

## Exercise E:
Using the data from the time series dataset, visualise the trend in historical population in England, as well as the predicted population in 2030.


We will be assessing both the techniques you use to calculate the answers to these questions and the way in which your answers are visualised.

Send you answers plus any code to msinclair@lambeth.gov.uk before the deadline. Please email us if you have trouble accessing the above datasets


Good Luck!
