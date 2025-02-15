# Tabular Data Analysis with FastAI 📊🤖

This project demonstrates **tabular data analysis** using the **FastAI** library on the **Bluebook for Bulldozers** dataset from Kaggle. The goal is to predict the sale price of bulldozers using **Random Forest** and **Neural Network** models. 🎯📈

---

## Table of Contents 📑
1. [Overview](#overview-)
2. [Installation](#installation-)
3. [Usage](#usage-)
4. [Code Structure](#code-structure-)
5. [Results](#results-)
6. [License](#license-)

---

## Overview 🚀

This project:
- Uses **Random Forest** and **Neural Network** models for tabular data analysis. 🤖📊
- Preprocesses the dataset by handling categorical variables, missing values, and date features. 🧠🔍
- Evaluates model performance using RMSE (Root Mean Squared Error). 📊📉

---

## Installation 🛠️

To run this project, you need to install the required libraries. Run the following commands:

```bash
!pip install fastai
!pip install kaggle
!pip install pandas numpy seaborn
!pip install scikit-learn
!pip install treeinterpreter waterfallcharts
```

---

## Usage 🖥️

1. **Load Dataset**: The script downloads and loads the Bluebook for Bulldozers dataset from Kaggle.
2. **Preprocess Data**: Handles categorical variables, missing values, and date features.
3. **Build Models**: Implements Random Forest and Neural Network models for prediction.
4. **Train Models**: Trains the models and evaluates their performance using RMSE.
5. **Analyze Results**: Visualizes feature importance and model predictions.

---

## Code Structure 🗂️

- **Data Preparation**:
  - Downloads and preprocesses the dataset.
  - Splits the data into training and validation sets.

- **Random Forest Model**:
  - Implements a Random Forest model for prediction.
  - Evaluates feature importance and removes low-importance features.

- **Neural Network Model**:
  - Implements a Neural Network model using FastAI's `tabular_learner`.
  - Trains the model and evaluates its performance.

- **Ensemble Model**:
  - Combines predictions from Random Forest and Neural Network models for improved accuracy.

---

## Results 📊

- **Random Forest RMSE**: Achieves low RMSE on the validation set.
- **Neural Network RMSE**: Achieves competitive RMSE using a neural network.
- **Feature Importance**: Visualizes the most important features for prediction.

---

## License 📜

This project is licensed under the **MIT License**. Feel free to use, modify, and distribute it as needed.

---

## Example Output 🖼️

Here’s an example of the model's performance:

```plaintext
Random Forest RMSE: 0.123
Neural Network RMSE: 0.115
Ensemble RMSE: 0.110
```

---

## Dependencies 📦

- `fastai`
- `kaggle`
- `pandas`
- `numpy`
- `seaborn`
- `scikit-learn`
- `treeinterpreter`
- `waterfallcharts`

---

## Author 👨‍💻

This project was created by **[Navid Falah](https://github.com/navidfalah)**. Feel free to reach out for questions or collaborations at **navid.falah7@gmail.com**! 🤝
