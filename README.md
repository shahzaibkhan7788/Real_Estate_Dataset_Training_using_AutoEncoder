# Real_Estate_Dataset_Training_using_AutoEncoder
**Real Estate Price Prediction using Auto encoder with the Regression Decisson Tree**
This project aims to predict real estate prices using a dataset with 7 continuous features and 424 samples. The goal was to compare a simple regression tree with a more advanced approach that combines an autoencoder and a regression tree. The dataset was augmented to improve model generalization.

The simple regression tree achieved an R-squared value of 0.92. To enhance performance, I implemented an autoencoder to extract features before applying the regression tree. This combined approach significantly improved the R-squared value to 0.97, demonstrating the effectiveness of neural network-based feature extraction.

I used several frameworks and libraries for this project. Keras was used to build and train the autoencoder, with TensorFlow as the backend. Scikit-learn was employed to implement the regression tree and evaluate model performance. These tools facilitated a smooth workflow from data preprocessing to model training and evaluation.
