# Bootstrapping

## What is bootstrapping?
Bootstrapping is a resampling technique that can be used to price derivatives that have no analytical formula like exotic derivatives, or simply to simulate equity or bond prices. Contraly to other methods like the Monte Carlo simulation, bootstrapping does not make assumptions about the population's distribution, rather it uses a sample size of n historical observations to build the distribution by resampling with replacement.

## The process
There are many variations of bootstrapping, so we will start with one of the most common and taught approaches, the i.i.d. bootstrap, where we generate a sample assuming identical and independently distributed observations. 
1. Specify the quantity of interest. For example, it could be a stock price.
2. Specify the number of simulations (N)
3. Define the number of observations (n) for each bootstrap sample i: the length of the bootstrap sample. For example, for monthly stock prices over one year the length would be 12.
4. Construct bootstrap sample i by taking n observations at random from the sample size.
5. Repeat step 4 for the N number of simulations.







