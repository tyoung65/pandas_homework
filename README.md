# pandas_homework

# Conduct Quantitative Analysis
# Analyze the data to see if any of the portfolios outperform the stock market (i.e., the S&P 500).

## Performance Analysis
### Calculate and plot cumulative returns. Does any portfolio outperform the S&P 500?
## Risk Analysis
### Create a box plot for each of the returns. Which box has the largest spread? Which has the smallest spread?

### Calculate the standard deviation for each portfolio. Which portfolios are riskier than the S&P 500?

## Rolling Statistics
### Plot the rolling standard deviation of the firm's portfolios along with the rolling standard deviation of the S&P 500. Does the risk increase for each of the portfolios at the same time risk increases in the S&P?

### Construct a correlation table for the algorithmic, whale, and S&P 500 returns. Which returns most closely mimic the S&P?

### Choose one portfolio and plot a rolling beta between that portfolio's returns and S&P 500 returns. Does the portfolio seem sensitive to movements in the S&P 500?

### Plot Sharpe Ratios




## Create Custom Portfolio
### Add your portfolio returns to the DataFrame with the other portfolios and rerun the analysis. How does your portfolio fair?

Resources
Pandas API Docs

Hints
After reading each CSV file, don't forget to sort each DataFrame in ascending order by the Date using sort_index. This is especially important when working with time series data as we want to make sure Date indexes go from earliest to latest.

The Pandas functions used in class this week will be useful for this assignment.

Be sure to use head() or tail() when you want to look at your data but don't want to print to a large DataFrame.

Submission
Create a Jupyter Notebook containing your data preparation, analysis, and visualizations. Put your analysis and answers to the assignment questions in raw text (markdown) cells in the report.