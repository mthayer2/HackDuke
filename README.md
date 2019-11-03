# HackDuke-2019 Offensive Language Covolutional Neural Network
This repository contains my team's submission for HackDuke 2019. Our team consists of: Ara Chung, Duc Le, Matthew Thayer, and I, Storm King.

The Twitter_NN.ipynb file is the main file showcasing our work here at the hackathon.

For this project, we trained a neural network using 4,000 unique tweets in order to categorize whether or not a given sentence is potentially offensive. Our network learned from analyzing the context of each word using Google's word2vec corpus rather than simply memorizing the sequence of each word. This means that our algorithm can accurately analyze the meaning of each word in the sentence given that it has adequate training data.

A copy of our neural network is attached to this file for easy import with the Keras and Pytorch frameworks. This network had an ending accuracy on our testing data of 95% with a loss value of 0.16. We have included a text box at the bottom of the Twitter_NN.ipynb file to test our algorithm on any phrases or sentences below 100 words that you may want to try out!

The only file missing from this repository is the word2vec pre-trained Google News corpus (3 billion running words) word vector model due to the size of the file(3.6GB).
That file can be obtained at Google's official website or here: https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit

Note: Although our network only represented cases of Racism/Sexism, we believe with the correct datasets that this neural network could be expanded to represent all cases of offensive language. Our goal with this algorithm is to raise awareness for our presence on social media and how it could potentially affect others. 

Click the image below to see our demonstration video:

<a href="http://www.youtube.com/watch?feature=player_embedded&v=HAQ3fkJq17Y
" target="_blank"><img src="http://img.youtube.com/vi/HAQ3fkJq17Y/0.jpg" 
alt="Demonstration Video" width="240" height="180" border="10" /></a>
