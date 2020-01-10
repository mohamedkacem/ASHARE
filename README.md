# ASHARE

Libraries used
* Pandas and Numpy
* Plotting libraries (Matplotlib and Seaborn)
* SkLearn for preprocessing (LabelEncoder), train_test_split and performing Hyperparameter Tuning
* Keras in Tensorflow for creating and training the Neural Network model


Steps: 
* Downloading the dataset via Kaggle CLI and loading into Pandas DataFrames
* Exploaratory data analysis: Plotting distrubutions, checking columns with null values, Checking categorical data value counts, correlation with target variable, plotting skewed features or features with outliers
* Data processing pipeline: for easy transformation of both train and test datasets. Performing data cleaning, replacing null values, label encoding, feature engineering, fixing formats like timestamps and merging datasets
* building Keras neural network, creating callback for training (model saving, reducing learning rate on plateau), training the model.
Submission: performing data processing pipeline on test datasets, getting test results and submitting via Kaggle CLI
Model
Keras Deep Neural Network with layer sizes (128, 64, 1), with dropout and batch normalization and relu activations for all neurons (relu layer in output ensures that the meter_reading prediction is positive), trained using Adam optimizer and a variable learning rate.
