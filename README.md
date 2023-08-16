# App Type Prediction with TensorFlow

This project aims to predict the type of mobile apps (e.g., Education, Entertainment, Health, etc.) using machine learning techniques, specifically employing TensorFlow. The prediction is based on features extracted from the Google Play Store dataset.

## Libraries Used

- `numpy` and `pandas` for data manipulation and analysis.
- `plotly.express` for data visualization.
- `re` for regular expressions (if applicable).
- `sklearn` for various machine learning preprocessing tasks such as label encoding and scaling.
- `tensorflow` for building and training machine learning models.

## Dataset

The project uses the following datasets:

- `googleplaystore.csv`: This dataset contains information about different apps available on the Google Play Store, including features like app name, category, ratings, reviews, etc.
- `googleplaystore_user_reviews.csv`: This dataset contains user reviews for various apps on the Google Play Store.

## Usage

1. Make sure you have the required libraries installed. You can install them using the following command:

```bash
pip install numpy pandas plotly scikit-learn tensorflow
```

2. Download the dataset files (`googleplaystore.csv` and `googleplaystore_user_reviews.csv`) and place them in the appropriate directory.

3. Open the project's main code file and modify the file paths if necessary to point to the downloaded datasets.

4. Run the code to preprocess the data, build and train the TensorFlow model, and perform predictions.

## Code Overview

- Import necessary libraries: Import the required Python libraries such as numpy, pandas, plotly.express, sklearn, and tensorflow.

- Data Preprocessing: Load and preprocess the dataset, including handling missing values, encoding categorical features, and scaling numerical features.

- Model Building: Build a machine learning model using TensorFlow, define layers, and compile the model.

- Model Training: Train the model on the preprocessed data.

- Prediction: Use the trained model to make predictions on new data.

- Data Visualization: Create visualizations using plotly.express to understand the data distribution and relationships.

## Contributing

Contributions to this project are welcome! If you find any issues or have improvements to suggest, please open an issue or submit a pull request.
