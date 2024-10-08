# Diabetes Prediction with gridsearchCV and bayesian opimization
## Description
This project uses Support Vector Machines (SVM) to predict diabetes based on the PIMA Diabetes dataset. It involves data preprocessing, model training, hyperparameter tuning using GridSearchCV and Bayesian Optimization with scikit-optimize, and model evaluation.

## Dependencies
- numpy
- pandas
- scikit-learn
- matplotlib
- seaborn
- scikit-optimize

Install dependencies using:
```
pip install numpy pandas scikit-learn matplotlib seaborn scikit-optimize
```


## Dataset
The PIMA Diabetes dataset is used for this project. It contains health-related data from PIMA Native American women, including features like glucose levels, blood pressure, and BMI, with the target variable indicating diabetes presence (1) or absence (0).

## Getting Started
1. **Clone the repository**: `git clone https://github.com/spexcher/DiabOptiSVM.git`
2. **Navigate to project directory**: `cd DiabOptiSVM`
3. **Run the code**: Follow the code provided in `diabetes_prediction_svm.ipynb` or your Python script.

## Usage
- **Data Preparation**: Load the dataset, preprocess, and standardize the features.
- **Model Training**: Train SVM models using both GridSearchCV and Bayesian Optimization.
- **Model Evaluation**: Evaluate models using accuracy score, classification report, and confusion matrix.
- **Prediction**: Predict diabetes for new input data.

## Results
- **Model Performance**: Achieved accuracy of 77% on test data.
- **Confusion Matrix**: Visual representation of model predictions versus actual outcomes.

## Contributing
Feel free to contribute to this project. Fork the repository and submit pull requests with improvements.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For questions or feedback, please contact [Gourab Modak](mailto:spexcher@gmail.com).

## Acknowledgements
- The PIMA Diabetes dataset is sourced from [source](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database).
