# stock-analysis
Performing analysis on green energy stocks' market trends

## Overview
In this project I will be working with Steve, a recent finance graduate. We are helping Steve examine his parents investment into alternative energy, namely DAQO New Energy Corp (DQ), an alternative energy company that specializes in producing silicon wafers for solar panels. Steve wants to check 2 things throughout this project, the first being that his parents have chosen the right company to invest in. The second is whether it would be benefical to diversify thier portfolio by examining other green energy companies, over a 2 year performance. We will start by analyzing and organizing the data using VBA in excel and end by draw our own conclusions based on the data we were given.
	
## Results
### Stock performance
Looking at our results of the stock performances between the two years, we can see that stocks in 2017 generally outperformed stocks in 2018. There was a higher trade volume (how much the stocks were bought and sold) as well as better return values (the percentage increase in the stocks trading value) in the majority of them (Seen in the chart below).
	
![2017 Results](https://github.com/tateml0000/stock-analysis/blob/main/2017%20results.png)
![2018 Results](https://github.com/tateml0000/stock-analysis/blob/main/2018%20results.png)
	
The important thing thing to notice is the following change in both volume and return. In this chart below showing the difference in trading and performance of the stocks, there was a general increase in trading while a major decrease in return. This would mean, although the stocks became more popular they did not perform as well in these years. The limiting part of our results here is that this happens to many companies, as people start becoming aware of them, they need to start performing and may just be getting financing or maybe have gotten other investors due to green energy taking off as a whole, while still underperforming compared to their competitors. 
	
![Difference in Performance](https://github.com/tateml0000/stock-analysis/blob/main/change.png)
	
### Refactored Code
To analyze our data we used two different methods


## Summary
  1. The main advantage of refacorting code is seen in the run time. We are able to see a decrease of about 5-6 times using the refactored code. This difference isn't that noticable with the size of our data set, but if we were using this on the stock market with 100 times more data, this could save us minutes each time we run the code and allow for more immediate results and a smaller chance of our computers freezing or results being delayed. Another advantage seen here is the consolidation of two macros and the allowance for more flexibility in our code. If data were to be added we would simply need to add in the new tickers and change a few numbers to match the amount of tickers we are evaluting, while in the original code although the changes are just as easy, there are less options for storage of data compared to the arrays we use. A disadvantage we see in this method is initializing more variable and creating more arrays. This means this caused more work in the front end, but we see the flexibility and ease of it after it's written. These problems could be a simple spelling mistake or an array size wrong, but ultimately these issues would be quickly resolved while debugging.

  2. All of these pros and cons were seen in our data other than the addition of new data for the refactored code. We had to take a lot of work from the original code and add in 3 new arrays and a tickerIndex. If this was the only project that Steve had to work on and nothing further, than I would suggest going with the original code. It was much quicker to write and reported the same results. But our refactored code combined two macros into 1 (the analysis and formatting) and is much quicker, in case Steve wants to evaluate different stocks or more of them.


![2017 Execution Times](https://github.com/tateml0000/stock-analysis/blob/main/VBA_Challenge_2017.png)
![2018 Execution Times](https://github.com/tateml0000/stock-analysis/blob/main/VBA_Challenge_2018.png)

