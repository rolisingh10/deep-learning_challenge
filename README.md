# deep-learning-challenge


## Overview of the analysis: 
   The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. Using machine learning and neural networks, we have to use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.
   In the first attempt, the columns EIN and NAME were dropped, since they were insignificant for the analysis. The bins for columns CLASSIFICATION and APPLICATION_TYPE were created. The categorical columns were converted to numerical coulmns. The preprocessed data was divided into features and target arrays. Then the data was split into training and testing datasets.After that the data was scaled and then the model was compiled, trained and evaluated.
   

## Results:

#### Data Preprocessing

What variable(s) are the target(s) for your model?

**The variable "IS_SUCCESSFUL" is the target of the model.

What variable(s) are the features for your model?

** All the other variables except "EIN" and "NAME" are the fetures of the model in the first attempt.
What variable(s) should be removed from the input data because they are neither targets nor features?

** The variables "STATUS"and "SPECIAL_CONSIDERATIONS" in the last two attempts.

#### Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?

** I selected 4 layers in the last attempt with 10, 8, 6, 2 nodes in the respective layers. I chose relu and sigmoid activation functions. I chose more layers and nodes since I was not getting the desired accuracy.

Were you able to achieve the target model performance?

** I was not able to achieve the target model performance.

What steps did you take in your attempts to increase model performance?

** I added one more layer and increased the number of nodes in the previous layers.
** I dropped two columns in the dataset.
** I increased and decreased the number of epochs.

#### Summary: 

I got accuracy rate of .72 first time and even after trying three more times I could not accuracy rate more than .73. I can add more layers and increase the number of nodes in each layer to get the desired accuracy.
