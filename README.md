# House Price Prediction Project

## Project Overview

Welcome to the House Price Prediction Project, a machine learning initiative designed to forecast future house prices using data from the Federal Reserve and Zillow. This project involves combining economic indicators with housing data to train a random forest model. The goal is to predict whether house prices will rise or fall, leveraging modern data analysis and machine learning techniques.

## Technologies Used

### Backend:
- Python 3.8+
- JupyterLab
- Pandas
- Scikit-learn
- yfinance

### Frontend:
- N/A (Project is primarily backend-focused)

## Features

- Integration of economic and housing datasets.
- Random forest model for predicting house price movements.
- Backtesting for model performance evaluation.
- Incremental model refinement with additional predictors.

## Installation

### Prerequisites

- Python 3.8+
- JupyterLab
- Necessary Python packages (listed in `requirements.txt`)

### Local Setup

#### Clone the Repository:

```sh
git clone https://github.com/yourusername/house-price-prediction.git
cd house-price-prediction
```

#### Create and Activate a Virtual Environment:

```sh
python3 -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

#### Install Required Packages:

```sh
pip install -r requirements.txt
```

#### Install JupyterLab:

```sh
pip install jupyterlab
```

#### Launch JupyterLab:

```sh
jupyter lab
```

Open the JupyterLab interface in your web browser and navigate to the `notebooks` directory to access the project notebooks.

## Usage

1. **Open JupyterLab:**

   Navigate to the project directory and start JupyterLab to access and run the notebooks.

2. **Run the Notebooks:**

   Follow the instructions in the notebooks to preprocess the data, train the random forest model, and evaluate its performance.

3. **Model Refinement:**

   Experiment with additional predictors and model parameters to improve accuracy.

## Contribution

We welcome contributions to enhance the project. Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix:

   ```sh
   git checkout -b feature/your-feature-name
   ```

3. Commit your changes:

   ```sh
   git commit -m "Add your message here"
   ```

4. Push to your branch:

   ```sh
   git push origin feature/your-feature-name
   ```

5. Open a Pull Request.

## What I Learned

- **Data Integration**: Gained experience in merging datasets from different sources to create a comprehensive data set for modeling.
- **Machine Learning**: Developed skills in applying random forest models to real-world problems and understanding their performance through backtesting.
- **Model Refinement**: Learned how to iteratively improve model accuracy by experimenting with different predictors and tuning model parameters.
- **Data Analysis**: Enhanced ability to preprocess and analyze data using Python tools, leading to better insights and predictions.
