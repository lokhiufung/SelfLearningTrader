# SelfLearningTrader
about applying reinforcement learning in trading


## environment 
you can create episodic data in arbitary episode length. The data is from the file 'historicaldata'. Each episode is normalized by its first value. This make the price in each episode will be in a similar range. I mixed up all companies in the historical data to make episodes. By doing this i want to invesetigate that whether we can have a general rule in traing different stock. 

## prepare_data
make episodes and pull data from 'historicaldata'. Maybe i can do with real time data or can directly download data for google finance 

## agent
a trading agent defined by user. 
