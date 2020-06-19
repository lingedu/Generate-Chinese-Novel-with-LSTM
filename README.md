# Generating Chinese Novel with LSTM
In this repository, I generate a chinese novel using a character-based RNN. First, we vectorize our text and create training examples and targets based on the novel. Then we fit our dataset into our sequntial model which consist of embbeding, LSTM and Dense layers and start to train the model. After model is trained, we can send a prefix to the model and generate the text. We can find the text is meaningful while the roles, places we generate is related to the original novel. We also tune the parameters and change the temporature to compare in what kind of condition can make the semantic more consistent and close to humans. The experiment result of different parameters is show in [result.png](https://github.com/s99436q/Generate-Novel/blob/master/result.png).


![](img/cover.jpg)
Credit: [coursera](https://www.coursera.org/learn/deep-learning-business) 
