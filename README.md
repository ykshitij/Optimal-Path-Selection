# Optimal-Path-Selection

The main objective was to develop an optimal path for a node which travels from a source to base station. Key constraints were time varying network, due to which predicting the path any instant of time became more difficult.
A cost function was formulated which jointly considered the data latency and the packet loss risk for optimizing the relay-node selection. Several shortest paths were selected using DJIKSTRA algorithm. Selection of best path was done choosing past history in account. 
Two methods were implemented. One was through training on the dataset and applying it to new dataset taking all the past history in account and other was through taking partial history in account and regularly updating history.
The result showed overfitting in case of Number of data points to be less than 40 and were accurate when points were more than 100. 
Proposed future work in this with the usage of reinforcement learning. Studied theoretical usage of reinforcement learning in this work. Published those results in Conference held in New Delhi.  

