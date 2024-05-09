# LOS Regression Models with Azure Notebooks

This repository contains machine learning models developed to predict the Length of Stay (LOS) in hospitals using a toy dataset provided by Microsoft. The models are built and trained using Azure Notebooks, showcasing the capabilities of cloud-based data science environments.

## Project Structure

- **data/**: Contains the Microsoft toy LOS dataset.
- **notebooks/**: Jupyter notebooks for model training and evaluation.
- **src/**: Source code for data preprocessing, model building, and evaluation.
- **requirements.txt**: List of Python packages required.

## Dataset

The dataset used in this project is a toy dataset provided by Microsoft, designed to simulate hospital stay data. It includes features such as patient demographics, admission details, and previous medical history.

## Models

We employ various regression techniques to predict the length of hospital stays. The models include:

- Linear Regression
- Decision Tree Regression
- Random Forest Regression
- Gradient Boosting Machines (GBM)

## Setup and Installation

Ensure you have an Azure account and access to Azure Notebooks. Follow these steps to set up the project environment:

1. Clone the repository:
   ```bash
   git clone https://github.com/smgpulse007/AzureLOSPrediction.git
   cd los-regression-models
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch Azure Notebooks and upload the notebooks from the `notebooks/` directory.

4. Load the dataset from the `data/` folder into your Azure Notebook environment.

## Running the Notebooks

Open the Jupyter notebooks within Azure Notebooks and run them sequentially:
1. Data Preprocessing
2. Model Training
3. Evaluation

Each notebook contains detailed instructions on the steps performed and the reasoning behind model choices and configurations.

## Contributing

Contributions to improve the models or extend the dataset are welcome. Please follow the standard pull request process:
- Fork the repository.
- Create a new branch for your feature.
- Submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

