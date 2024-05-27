# Rossmann Sales Forecasting

This repository contains the code and resources for forecasting sales for Rossmann Pharmaceuticals' stores across various cities. The goal is to predict daily sales up to six weeks ahead of time, leveraging both traditional machine learning and deep learning techniques.

## Repository Structure



## Getting Started

### Prerequisites

- Python 3.8+
- Required libraries are listed in `requirements.txt`

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/kiraassefa19/rossmann-sales-forecasting.git
    cd rossmann-sales-forecasting
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

### Running the Project

1. **Exploratory Data Analysis**:
    - Open and run `notebooks/eda.ipynb` to explore the data.

2. **Preprocessing**:
    - Open and run `notebooks/preprocessing.ipynb` to clean and preprocess the data.

3. **Model Training**:
    - Open and run `notebooks/modeling.ipynb` to train machine learning models.
    - Open and run `notebooks/deep_learning.ipynb` to train the LSTM model.

4. **Serving Predictions**:
    - Scripts and notebooks will guide you to serialize models and serve predictions.

### Logging

- Logs are stored in the `logs/` directory. They provide detailed information about each step of the process.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any changes.

## License

This project is licensed under the MIT License.


