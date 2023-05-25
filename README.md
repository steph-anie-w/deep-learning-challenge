# Neural Network Modeling
This code was written to aid a charity ('Alphabet Soup') in choosing which applicants have the best chance for success and thus should be awarded funding.

## Data Preprocessing
The target variable for this model is the success of past applicants ('IS_SUCCESSFUL'), the features are all other variables included minus the EIN and Name categories as they do not provide any useful data for the target results.

## Compiling, Evaluating, Optimizing
The initial model has two hidden layers with 80 and 30 neurons, the activation is relu; this yielded 5,981 parameters with an accuracy of 0.7258. In the attempt of reaching the target goal of 75% accuracy, the next three models have variance within the neurons and number of hidden layers. The model that obtained the highest accuracy has two hidden layers with 7 and 14 neurons, 428 total parameters and after 100 epochs an accuracy of 0.7272.

## Final Thoughts
Though the target accuracy was not reached, there are other avenues that have yet to be fully explored. In the preprocessing, it may prove beneficial to alter the bin sizes allowed (both larger and smaller) or potentially binning an additional value. There are minor tweaks to activation functions found within the various models, however, this may be another area to improve the final accuracy.
