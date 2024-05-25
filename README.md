# Heart Disease Prediction

Leveraging the potency of machine learning, particularly Random Forest classifiers, is catalyzing a paradigm shift in healthcare, notably in heart disease prediction. These sophisticated models harness vast health data to predict heart disease risk with remarkable accuracy, facilitating tailored risk assessments and optimizing healthcare resource allocation. By championing data transparency and guiding individuals towards healthier lifestyles, these models aspire to mitigate complications associated with stroke and heart disease and bolster preventive healthcare strategies.

## Project Overview

This project aims to predict heart disease risk using a Random Forest classifier. The model analyzes multifaceted variables, including demographics, lifestyle habits, and medical history, to forecast the decade-long risk of heart disease. Early identification of risk factors is imperative for proactive healthcare management, and this model epitomizes the profound potential of machine learning in advancing public health outcomes and enhancing societal well-being.

## Features and Methods

### Data Source
- Datasets obtained from Kaggle are imported as CSV files, initiating an exploratory analysis phase.

### Data Visualization
- Visualizations such as histograms, box plots, and pie charts were used to examine underlying data patterns.

### Data Preprocessing
- Handling missing values.
- Managing outliers through winsorization.
- Encoding target variables for model compatibility.

### Model Training
- The Random Forest classifier was trained using selected features and labels.
- Hyperparameter tuning was conducted to optimize model performance.

### Model Evaluation
- Performance assessed using metrics such as confusion matrix, accuracy score, and classification report.

### User Interaction
- Users can input new instances for prediction, highlighting the model's practical application.
- Iterative deployment for continuous predictions until user conclusion.

## Hyperparameter Tuning

The table below illustrates the impact of hyperparameter tuning on the accuracy of the model:

| Test Size | Accuracy (%) |
|-----------|---------------|
| 0.10      | 88.04         |
| 0.15      | 86.23         |
| 0.20      | 83.15         |
| 0.25      | 84.78         |
| 0.30      | 86.23         |

| Estimators | Accuracy (%) |
|------------|---------------|
| 10         | 88.04         |
| 20         | 89.13         |
| 30         | 88.04         |
| 100        | 88.04         |
| 200        | 88.04         |

## Improvements

1. **Pairplot**: Visualizes pairwise relationships between numerical features in the dataset, colored by the target variable, heart disease.
2. **Line Plot**: Illustrates the distribution of heart disease occurrences across different age groups.
3. **Pie Chart**: Visualizes the distribution of different categories within the RestingECG feature.
4. **Semi-Autonomous Deployment**: Iterative deployment using a semi-autonomous while loop for continuous predictions.

## Usage

To run the project, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/heart-disease-prediction.git
    ```
2. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
3. **Run the script**:
    ```bash
    python heart_disease_predictor.py
    ```

## Results

1. **Data Loaded**: Dataset loaded into a DataFrame, displaying the first five rows and shape.
2. **Data Visualization**: Insights into age-related heart disease risk.
3. **Pair Plot**: Pairwise relationships between different features.
4. **Pie Chart**: Distribution of RestingECG categories.
5. **Preprocessing**: Cleaning data, encoding columns, and dataset splits.
6. **Model Performance**: Confusion matrix, accuracy score of 88.04%, precision, recall, and F1 scores.
7. **Prediction Instances**: Demonstrates predictions with patient data.

## Comparative Analysis: Decision Tree vs. Random Forest

| Metric       | Random Forest | Decision Tree |
|--------------|----------------|---------------|
| Accuracy     | 88.04%         | 82.60%        |
| Precision (0)| 0.91           | 0.76          |
| Precision (1)| 0.86           | 0.88          |
| Recall (0)   | 0.80           | 0.84          |
| Recall (1)   | 0.94           | 0.81          |
| F1-score (0) | 0.85           | 0.80          |
| F1-score (1) | 0.90           | 0.85          |

The Random Forest classifier demonstrates higher accuracy, precision, and F1 scores compared to the Decision Tree model, underscoring its superior performance.

## Conclusion

The Random Forest model's ensemble approach leads to improved generalization and robustness, making it the preferred choice for heart disease prediction. Its ability to handle high-dimensional datasets with correlated features effectively contributes to its superior performance, highlighting its potential in predictive healthcare applications.

## Contact

For more information, feel free to contact:

**Mohammed Abdulai**  
Email: [your-email@example.com](mailto:your-email@example.com)  
GitHub: [your-github-username](https://github.com/your-github-username)

---

Feel free to contribute to the project by submitting issues or pull requests on the [GitHub repository](https://github.com/yourusername/heart-disease-prediction).
