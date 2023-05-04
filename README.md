# L-715-Final-Project


### Description
For the final project, I decided to use the data from the [EXIST 2023 Shared Task] (http://nlp.uned.es/exist2023/) about sexism detection in English and Spanish. Here, I only used the Spanish data, along with hard labels. The Shared Task provides a set of six labels by different annotators. Ties were broken by siding with the majority vote.

### Files
- **train_data_spanish.pkl**: the actual tweets
- **train_hard_labels_spanish.pkl**: the hard labels for each tweet
- **neuralnetwork2.ipynb**: the code for the neural net

### Libraries Used
- **pickle**: loading the data
- **numpy**: the math
- **matplotlib**: to plot the losses

### Overview
Here is an overview of the code:
1. Import the libraries and the data
2. Define functions to create a term-frequency inverse document frequency (TF-IDF) matrix
3. Define the functions related to the neural network (uses ReLU and sigmoid activation functions with binary cross entropy loss)
4. Train the neural network on the tf-idf matrix
5. Plot the loss




