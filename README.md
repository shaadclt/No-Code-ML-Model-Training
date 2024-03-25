# No-code ML Model Training

![nocodeml](https://github.com/shaadclt/No-Code-ML-Model-Training/assets/98437584/dd1d15fd-e9b2-41d0-ada6-f1595c931389)

This project aims to provide a user-friendly interface for training machine learning models without the need for coding. It allows users to select a dataset, preprocess it, choose a model, train the model, and evaluate its performance, all through an intuitive web interface built with Streamlit.

## Features
- **Dataset Selection**: Users can choose from a list of available datasets to train their models on.
- **Data Preview**: Provides a preview of the selected dataset, displaying the first few rows.
- **Target Column Selection**: Allows users to specify the target column for prediction.
- **Scalability**: Supports both standard and min-max scaling for numerical features.
- **Model Selection**: Offers a variety of models to choose from, including Logistic Regression, Support Vector Classifier, Random Forest Classifier, and XGBoost Classifier.
- **Model Training**: Trains the selected model on the preprocessed data and saves the trained model for future use.
- **Model Evaluation**: Evaluates the trained model's performance using accuracy score on the test data.

## Usage
1. Clone the repository:

```bash
git clone https://github.com/shaadclt/No-Code-ML-Model-Training.git
cd No-Code-ML-Model-Training
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

3. Run the Streamlit app:
```bash
streamlit run main.py
``` 
4. Access the app through your browser at **http://localhost:8501**.

## Dependencies
1. Streamlit
2. scikit-learn
3. xgboost
4. pandas

## Author
This project was developed by Mohamed Shaad. You can connect with me on LinkedIn and check out my other projects on GitHub.

