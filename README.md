# VBA Refactoring

## Overview of Project

An analysis of and refactoring of a program to analyze the data of many stocks at one time. 

### Purpose

Steve has tasked us with creating a program to analyze a small number of green energy stocks. Although we have created a program to run this analysis, we now are interested in editing the program to run quicker and more efficiently in order to be able to run smoothly for a dataset that would include the entire stock market.

## Results

### Stock Analysis for 2017

In refactoring the script we got rid of the nested for loop and added a ticker index that adds up all of the total daily volumes for the entire year for each ticker before moving to the next ticker. In doing this, we see from the two screenshots below, that the script ran much more efficiently and returned the same results.

![alt text](https://github.com/tmidcalf/VBA_Challenge/blob/main/Resources/Origanal_Script_2017.png?raw=true)

![alt text](https://github.com/tmidcalf/VBA_Challenge/blob/main/Resources/VBA_Challenge_2017.png?raw=true)

### Stock Analysis for 2018

Similarly with the 2017 analysis, we see in the two screenshots posted below that the script ran much more efficiently while working through the 2018 data.

![alt text](https://github.com/tmidcalf/VBA_Challenge/blob/main/Resources/Origanal_Script_2018.png?raw=true)

![alt text](https://github.com/tmidcalf/VBA_Challenge/blob/main/Resources/VBA_Challenge_2018.png?raw=true)


## Summary

- One of the advantages of refactoring code is that, in most cases, it would speed up the program and possibly allow the program to be run on larger datasets. It also creates code that is less complex, making it more easily read and understood for people to reading or using the code in the future. Although, going line by line refactoring code to run more efficiently also takes much time and if there are deadlines to meet you might run out of time or resources to complete the refactored program.

- 
 