# vba_challenge

## Overview of Project
As Steve's parents are passionate about green energy and planning to invest all of their money in (DQ) DAQO New Energy Corp a company that makes parts for solar panels. Steve's parents are his first clients, he wants to look for some Green Energy stocks performance during the years 2017 and 2018 so that some analysis could be concluded from the data. Our main purpose is to make a Visual Basic for Applications (VBA) programming script so that the analysis can be done using basic calculations and use complex logic to perform analysis.

## Results
Using the VBA programming script we performed some calculations to get the Total Daily Volume and Annual Return of all stocks to further do our analysis.

First,  it can be seen in [2017](https://drive.google.com/file/d/1vJqDN5lfpoRA2IRf0dTuV1HaUt1BVPFW/view?usp=sharing) that almost all the Green Energy stocks performed very well except one stock TERP. The annual return of DQ stock was highest in that year even when the volume was the lowest of all.

On the other hand, the year [2018](https://drive.google.com/file/d/1XOn3Clqklign_aDJpEVWUQ-ZTv1QZ3Pi/view?usp=sharing) was not so great for green energy stocks. The DQ stock which previously in 2017 returned almost 200% gain, by the end of 2018 returned a negative 62.6% value. We can see in the images that,  it was the worse performing stock in the given list during [2018](https://drive.google.com/file/d/1XOn3Clqklign_aDJpEVWUQ-ZTv1QZ3Pi/view?usp=sharing)  even when its volume increased by more than 3 times than [2017](https://drive.google.com/file/d/1vJqDN5lfpoRA2IRf0dTuV1HaUt1BVPFW/view?usp=sharing).

##
In our original script, we performed analysis on just DQ stock but later on, the script was refactored to get an analysis of all stocks during the year, and the execution time of [refactored script](https://drive.google.com/file/d/1PBlg9L2S016IKQemGDaz2fNqGuEapaxR/view?usp=sharing) increased by 14 times than the [original script](https://drive.google.com/file/d/1JzsBpSFtZ-qnnuVD5Nrg3wln1QLKkk8_/view?usp=sharing).


## Summary
There are always some advantages and disadvantages of refactoring the code:

### Advantages
- You don't have to write a different code for each ticker.
- Performing analysis is easy as all the results are present on the same sheet.
- Saves time as in our case to get a year's analysis it's just a simple click process.

### Disadvantages
- It increases the execution time for the code.
- It can be hard to understand if you are refactoring someone else's code.
---
Upon refactoring the original script, we got the total volume and return of all the stocks in the same sheets. It fastens the process to do the analysis even when colors(red/green) are present in the annual return cells. with our new code we can just enter the year we want to perform the analysis and see the results. on the other hand, our execution time increased by 14 times as we have seen earlier because of the nested loops we while refactoring. In last even if is a small code right now but later on, if someone else tries to understand the code it could be a little hard and tricky to understand.

