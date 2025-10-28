# Household-Power-Prediction
Forecasted power usage using regression and IoT data.
The dataset includes features such as time and voltage and the corresponding global active power. 
The dataset is retrieved from: https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption
# Outcome
breif description on what each graph represents

- heatmap (hour vs day of week)
it shows the average consumption patterns by time of day across different weekdays, it reveals daily routines, like higher usage evenings, and weekly cycles (weekends vs weekdays)

- seasonal decomposition
it splits the power signal into trend, seasonality, and residual (noise) it lets us see long-term trends, like gradual increase, repeated daily cycles (seasonality), and random fluctuations

- holiday boxplots
it shows a distribution of power usage on weekends vs weekdays, and holidays vs regular days. it captures behavioral effects, like people stay home more on weekends/holidays, often raising/lowering consumption patternsS

- boxplots across hours & months
it shows: by hour: variability of consumption during the day (morning peaks, night lows) by month: seasonal variations (winter heating vs summer cooling). it helps us model time-of-day and seasonal dependence

- rolling window statistics
it shows moving averages and standard deviations of power consumption like in a 24-hour window it highlights short term trends and volatility, smoothing out noise to see consumption shifts more clearly
