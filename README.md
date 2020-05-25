# Neural-Networks-Deep-Learning-Models

##  How many neurons and layers did you select for your neural network model? Why?
    *  Neurons: 98*2 = Thumb of rule: A good rule of thumb for a basic neural network is to have two to three times the amount of neurons in the hidden layer as the number of inputs.
    * Layers: 2 
    
##  Were you able to achieve the target model performance? What steps did you take to try and increase model performance? 
    * No, average accuracy was ~72%; 
    * By changing the bucket size(counts) 
    * By adjusting Epochs # 100 —> 50 
    
##  If you were to implement a different model to solve this classification problem, which would you choose? Why?
    * Random forest 
—> faster performance , easy to transform; the random forest classifier was able to train on the large dataset and predict values in seconds, while the deep learning model required a couple minutes to train on the tens of thousands of data points. 
In other words, the random forest model is able to achieve comparable predictive accuracy on large tabular data with less code and faster performance. The ultimate decision of whether to use a random forest versus a neural network comes down to preference. However, if your dataset is tabular, random forest is a great place to start.
