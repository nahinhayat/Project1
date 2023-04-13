# Project1
Project Summary:
The goal of our project was to use the historical data of five investment options and use this information to create forecasts of possible outcomes after 5 years if an individual were to invest $350,000 into any of these options. These options being: gold, silver, BitCoin, a house in either the southern or northeastern region of the USA, and the S&P 500 index. We were able to find the possible outcomes of this $350,000 investment by computing the maximum and minimum returns for each option with 95% confidence intervals. 

Installation Guide:
This program requires the following libraries: numpy, pandas, yfinance, hvplot, and pathlib. 
Install the numpy library by typing "pip install numpy" command in the terminal
Install the pandas library by typing "pip install pandas" command in the terminal.
Install the yfinance library by typing "pip install yfinance" command in the terminal.
Install the hvplot library by typing "pip install hvplot" command in the terminal.
Install the pathlib library by typing "pip install pathlib" command in the terminal.

Description: 

The first step is to import the libraries for each file. Each asset has its own file for data analysis and there is another jupyter notebook for comparing the data. 
![screenshot1](https://github.com/nahinhayat/Project1/blob/main/FinTechProject1/Project1Screenshots/Screen%20Shot%202023-04-12%20at%209.25.51%20PM.png)

Next we will import the closing price data and read them as dataframes. Some assets use the yf library and some use csv files. The different processes are shown below.
![screenshot2](https://github.com/nahinhayat/Project1/blob/main/FinTechProject1/Project1Screenshots/Screen%20Shot%202023-04-12%20at%209.26.17%20PM.png)
![screenshot3](https://github.com/nahinhayat/Project1/blob/main/FinTechProject1/Project1Screenshots/Screen%20Shot%202023-04-12%20at%209.26.42%20PM.png)

Then the closing prices were plotted as line charts
![screenshot4](https://github.com/nahinhayat/Project1/blob/main/FinTechProject1/Project1Screenshots/Screen%20Shot%202023-04-12%20at%209.28.03%20PM.png)

This leads to the analysis portion, so we begin by configuring and running the Monte Carlo Simulation
![screenshot5](https://github.com/nahinhayat/Project1/blob/main/FinTechProject1/Project1Screenshots/Screen%20Shot%202023-04-12%20at%209.28.27%20PM.png)

After running the simulations wew got the summary statistics, calculated the maximum and minimum returns and stored each variable
![screenshot6](https://github.com/nahinhayat/Project1/blob/main/FinTechProject1/Project1Screenshots/Screen%20Shot%202023-04-12%20at%209.28.27%20PM.png)

We then plotted the returns
![screenshot7](https://github.com/nahinhayat/Project1/blob/main/FinTechProject1/Project1Screenshots/Screen%20Shot%202023-04-12%20at%209.31.47%20PM.png)

Finally on the jupyter lab for data comparison all the stored variabled were called
![screenshot8](https://github.com/nahinhayat/Project1/blob/main/FinTechProject1/Project1Screenshots/Screen%20Shot%202023-04-12%20at%209.33.36%20PM.png)

This lead us to creating a bar graph with each asset's maximum and minimum to compare
![screenshot9](https://github.com/nahinhayat/Project1/blob/main/FinTechProject1/Project1Screenshots/Screen%20Shot%202023-04-12%20at%209.34.00%20PM.png)

Contributors:
Nahin Hayat
Rosie Dabbaghi
Bubba Earnest
