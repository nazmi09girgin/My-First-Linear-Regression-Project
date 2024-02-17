# My-First-Neural-Network-Regression-Project
I tried to make price predictions from the features of Audi brand vehicles with TensorFlow.

1. **Data Reading and Exploration:**
   - The project starts by importing necessary libraries and reading a dataset named "audi.csv" using the Pandas library.
   - The general information and statistical summary of the dataset are examined.

2. **Data Cleaning and Preprocessing:**
   - Checking for and handling any missing values in the dataset.
   - Removing unnecessary columns (model, transmission, fuelType) from the dataset.
   - Eliminating the top 1% of data with the highest prices (106 records) to enhance the model's focus.

3. **Data Visualization:**
   - Utilizing the Seaborn library to create a histogram to visualize the distribution of car prices in the dataset.
   - Generating a scatter plot to explore the relationship between prices and specific features.

4. **Data Scaling and Splitting:**
   - Scaling the dataset to establish a connection between prices and other features.
   - Splitting the dataset into training and testing sets.

5. **Building a Neural Network Model:**
   - Constructing a neural network model using TensorFlow and Keras libraries.
   - The model architecture consists of a 4-layer neural network (4 hidden layers with 12 neurons each and 1 output layer).
   - Training the model for 300 epochs.

6. **Model Evaluation:**
   - Visualizing the loss values during training to assess the model's performance.
   - Evaluating the model's prediction on the test data by calculating the Mean Absolute Error.
   - Creating a scatter plot to compare the actual prices with the predicted prices.
