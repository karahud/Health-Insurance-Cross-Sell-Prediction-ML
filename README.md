# Predicting Customer Interest in Health Insurance Cross-Sell

## Problem Statement

In the competitive insurance industry, maximizing revenue through cross-selling additional products to existing customers is a key strategy. This project focuses on predicting customer interest in purchasing a vehicle insurance policy, specifically targeting those who already have a health insurance policy. Accurately identifying potential customers for this cross-sell opportunity is essential for optimizing marketing efforts, reducing customer acquisition costs, and enhancing overall customer satisfaction.

## Objective

The primary objective of this project is to develop a machine learning model that predicts the likelihood of a customer being interested in purchasing a vehicle insurance policy. The model will leverage various customer attributes, including demographics, vehicle details, insurance history, and interaction channels, to make these predictions. The key target variable is **Response**, which indicates whether or not a customer is interested in the cross-sell offer.

## Key Challenges

- **Data Imbalance**: The dataset may have an unequal distribution of interested versus uninterested customers, potentially leading to biased model predictions.
- **Feature Engineering**: Creating and identifying relevant features that can enhance model accuracy.
- **Scalability**: Ensuring the model's efficiency in handling large datasets.
- **Model Evaluation**: Choosing appropriate metrics, such as precision, to accurately measure the model's ability to predict true positives while minimizing false positives.

## Deliverables

- A machine learning model capable of predicting the likelihood of a customer responding positively to a vehicle insurance cross-sell offer.
- A comprehensive report detailing:
  - Data preprocessing steps
  - Feature engineering techniques
  - Model selection and optimization
  - Performance evaluation using appropriate metrics
  - Key business insights derived from the model's predictions

## Business Impact

Accurately predicting customer interest allows the insurance company to:
- Better allocate marketing resources to target the most promising customers.
- Increase the conversion rate of cross-sell campaigns.
- Enhance operational efficiency by focusing efforts on customers most likely to respond positively.
- Improve overall customer experience by offering relevant products to those who would benefit the most.

## Project Structure

The repository is organized as follows:

- **`Machine_Learninig_Capstone_Project.ipynb`**: The main Jupyter notebook containing the code, data processing steps, model training, evaluation, and deployment instructions.
- **`data/`**: Directory containing the datasets used for training and testing the model.
- **`models/`**: Pre-trained models and saved model files.
- **`requirements.txt`**: List of Python libraries required to run the notebook and replicate the results.
- **`README.md`**: This file, providing an overview and instructions for the project.

## Usage

To run the notebook:

1. Ensure your environment is set up as described in the Installation section.
2. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
3. Open the `Machine_Learninig_Capstone_Project.ipynb` file and run the cells sequentially.

## Model Performance

The final model achieved the following performance metrics:

- **Accuracy**: 94.89%
- **Recall**: 99.83%
- **Precision**: 90.87%
- **F1-Score**: 95.14%

These metrics demonstrate the model's effectiveness in predicting customer interest and its readiness for deployment in a real-world setting.

## Conclusion

This project successfully developed a machine learning model that predicts customer interest in a vehicle insurance cross-sell offer. By leveraging this model, the insurance company can enhance marketing efficiency, improve customer targeting, and ultimately increase the conversion rate of their cross-sell campaigns.

## License

This project is licensed under the MIT License.

## Acknowledgments

- Special thanks to **AlmaBetter** for providing resources and support.



