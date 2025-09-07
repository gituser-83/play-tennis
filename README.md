# Decision Tree Classifier - Play Tennis Dataset

This project demonstrates the use of a Decision Tree Classifier to predict whether a tennis game will be played based on various weather features. The dataset used is the `PlayTennis.csv`, which contains weather-related attributes such as Outlook, Temperature, Humidity, and Wind, along with a target variable (`PlayTennis`) indicating if a tennis game is played (Yes or No).

## Dataset

The dataset contains the following columns:
- **Outlook**: Weather outlook (Sunny, Overcast, Rain)
- **Temperature**: Temperature (Hot, Mild, Cool)
- **Humidity**: Humidity (High, Normal)
- **Wind**: Wind (Weak, Strong)
- **PlayTennis**: Target variable (Yes/No)

> Note: This dataset is very small and hence may lead to overfitting. The model achieves 100% accuracy on the test set due to the simplicity and size of the dataset.

## Requirements

- Python 3.x
- pandas
- scikit-learn
