# Analysis of Stock Performance
## Overview of Project
### Purpose
The purpose of this project is to analyze the performance of different stocks, to make a wise investment choice. Stocks were analyzed on the basis of the Total Volume of Shares Outstanding and also its Return. In 2017, most stocks had a positive change in price by the end of the year, however in 2018 only two stocks had a positive change in their stock price, ENPH and RUN.

This project also looked at the result of refactoring VBA code to see its effect on the runtime of the code.

## Analysis and Challenges
### Analysis of 2017 Data
In 2017 all the stocks observed a positive change in their price at the end of the year compared to what they started at, as can be seen in the chart below:

![2017 Stock Performances](https://github.com/msshahid21/stock-analysis/blob/main/resources/Stock_Performance_2017.png)

Looking at this alone, the conclusion could be made that any of the stocks here could be a wise investment decision, however when stocks have very varied changes and any single year would not be a good indicator of the performance and relative return of a stock. Therefore, the data from other years would have to be observed in conjunction with the 2017 data to provide a better picture.

### Analysis of 2018 Data
Now looking at the 2018 data it can be seen that almost all of the stocks have had a turn for the worse, as can be seen in the chart below:

![2018 Stock Performances](https://github.com/msshahid21/stock-analysis/blob/main/resources/Stock_Performance_2018.png)

Looking at this, a clearer picture is provided, and it is seen that only two stocks continued to have a positive performance going into 2018. Those stocks are ENPH and RUN.

### Challenges and Difficulties Encountered
#### Dataset Issues
This dataset only looks at 12 different stocks, and all of them are from the same industry. Additionally, this data is only available for two years, which does not help with creating a better trendline for each of the stocks.

#### Runtime Issues for Analysis
When it came to the runtime, the initial code used was very slow (for computers), therefore changes were made to the code to provide a much faster runtime using refactoring. This helped reduce the runtime significantly. The results are shown below in the table and supporting pictures.

|  | 2017 Runtime | 2018 Runtime |
|---|---|---|
| Before Refactoring | 0.8047s | 0.8203s |
| After Refactoring | 0.0781s | 0.0781s|

Runtime Before Refactoring:

![2017 Runtime Before Refactoring](https://github.com/msshahid21/stock-analysis/blob/main/resources/Runtime_2017_Before.png)
![2018 Runtime Before Refactoring](https://github.com/msshahid21/stock-analysis/blob/main/resources/Runtime_2018_Before.png)

Runtime After Refactoring:

![2017 Runtime After Refactoring](https://github.com/msshahid21/stock-analysis/blob/main/resources/VBA_Challenge_2017.png)
![2018 Runtime After Refactoring](https://github.com/msshahid21/stock-analysis/blob/main/resources/VBA_Challenge_2018.png)

## Results
### Conclusion of Stock Analysis
For investment purposes it is very clear that either the ENPH or RUN stocks should be invested in, with the RUN stock being a stronger candidate as it improved by 78.5 percentage points over the two years. However, this was not enough data to analyze and it cannot be used to provide a strong recommendation. This is because of the limitations of the dataset. This data only contains the two years of stock history and cannot be used to create a better trendline.

### Advantages and Disadvantages of Refactoring in General
[to be completed]
