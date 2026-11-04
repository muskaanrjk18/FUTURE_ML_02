# Support Ticket Classification

## Project Overview
This project uses Machine Learning to automatically classify customer support tickets into different categories and priorities.

## Internship
Future Interns – Machine Learning Internship  
Task 02: Support Ticket Classification

## Objective
The objective is to classify customer support messages into categories and identify their priority levels.

## Dataset
A sample dataset containing 120 customer support tickets was created for this project.

**Dataset Columns:**
- Ticket_ID
- Ticket_Text
- Category
- Priority

**Categories:**
- Payment
- Refund
- Technical
- Account
- Shipping
- Product

**Priority Levels:**
- High
- Medium
- Low

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TF-IDF
- Logistic Regression
- Jupyter Notebook

## Project Workflow
1. Dataset creation and loading
2. Data exploration
3. Text cleaning and preprocessing
4. TF-IDF vectorization
5. Train-test split
6. Model training using Logistic Regression
7. Ticket category prediction
8. Ticket priority prediction
9. Model evaluation using accuracy, precision, recall and F1-score
10. Confusion matrix visualization

## Machine Learning Models
Two Logistic Regression models were developed:
- Category Classification Model
- Priority Classification Model

## Evaluation
The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Project Outputs
- Category and priority prediction CSV files
- Confusion matrix visualizations
- Trained ML models
- TF-IDF vectorizer

## How to Run
1. Clone or download this repository.
2. Install the required libraries using:

`pip install -r requirements.txt`

3. Open the Jupyter Notebook.
4. Run the notebook cells sequentially.

## Limitations
This project uses a small, artificially created sample dataset for learning and demonstration. Therefore, the evaluation scores may not represent real-world performance. A larger and more diverse real-world dataset would be required for reliable deployment.

## Conclusion
This project demonstrates how Natural Language Processing and Machine Learning can help automate customer support ticket categorization and priority classification.