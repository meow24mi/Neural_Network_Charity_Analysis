# Neural Network Charity Analysis

## Purpose
The goal of this analysis is to help Alphabet Soup determine which organizations to sponsor by offering financial support. Alphabet soup has provided data on the each organizaations' purpose, sponsorship amount, income, affiliation and etc for their past sponsorships. Base on the data provided, we are to make a prediction to see if current applicants will be successful if sponsored by Alphabet soup. 

## Results

### Data Preprocessing
* The column, Is Successful is the target for our machine learning model.
* Most of the other columns are considred features, with the exception of EIN, NAME, and Is Successful. 
* The columns EIN and NAME add no value to the analysis, and will be removed from the input data. 

### Compiling, Training, and Evaluating
* There are two hidden layers, and 80 neurons in the first layer, 30 neurons in the second layer. It was trial and error that I ended up with 80 and 30 neurons. 
* Relu activation function for both hidden layers and sigmoid activation function for the outer layer. Other activation functions did not yield as high of accuracy. 
* The highest accuracy I was able to acheive was 72.7%
* I attempted to increase more neurons and increased hidden layers, tried different activation functions, and varied the number of epochs to increase the model's performance. 

## Summary

Based on the data provided, we could predict with approximately 72% accuracy the charities that will succeed with funding from Alphabet Soup. To produce greater accuracy, we could collect more data from past organizations and current applicants for more features. 