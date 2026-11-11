# Diabetes Prediction Using Machine Learning

A machine learning project that predicts whether a person is likely to have diabetes based on health-related features such as glucose level, blood pressure, BMI, insulin, and age. The project uses Python and common data science libraries to clean, analyze, and model the dataset.

## Project Overview

This project demonstrates a complete machine learning workflow:

- Data loading and inspection
- Data preprocessing and cleaning
- Exploratory data analysis
- Feature selection and modeling
- Model evaluation and prediction
- Result interpretation

The solution is implemented in the Jupyter notebook:

- `ML project Diabetes.ipynb`

## Dataset

The model is trained on a diabetes dataset containing patient health metrics and a target label indicating whether the patient is diabetic.

Typical features may include:

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age

## Tech Stack

- Python
- Jupyter Notebook
- pandas
- NumPy
- scikit-learn
- matplotlib
- seaborn

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/tejaspalekar/Diabetes-Prediction-Using-Machine-Learning.git
   cd Diabetes-Prediction-Using-Machine-Learning
   ```

2. Create and activate a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter
   ```

## Usage

Open the notebook and run all cells in order:

```bash
jupyter notebook "ML project Diabetes.ipynb"
```

You can also load the notebook in VS Code or JupyterLab to inspect the code and outputs.

## Machine Learning Approach

The project typically follows a supervised learning workflow:

- Split data into training and testing sets
- Train a classification model
- Evaluate accuracy and other metrics
- Make predictions on unseen data

A common model used for this task is a logistic regression classifier or other classification algorithms from scikit-learn.

## Model Evaluation

The notebook can evaluate performance using metrics such as:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix

## Project Structure

```text
Diabetes-Prediction-Using-Machine-Learning/
├── README.md
├── ML project Diabetes.ipynb
└── .gitignore (if present)
```

## License

This project is available for educational and learning purposes.

## Author

- tejaspalekar

## Contributing

Contributions, suggestions, and improvements are welcome. Feel free to open an issue or submit a pull request.
