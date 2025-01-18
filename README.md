# ANN for Predicting Dataset Values

This project demonstrates how to build, train, and evaluate an Artificial Neural Network (ANN) model using Python and TensorFlow. The data used for this project comes from an Excel dataset, and the goal is to make predictions based on the features.

---

## Project Structure

The main stages of this project include:

1. **Data Loading and Preprocessing**
   - The dataset is loaded from an Excel file using `pandas`.
   - Features (`X`) and the target (`y`) are split into separate variables.
   - Dataset is split into training and testing sets using `scikit-learn`.

2. **Building the ANN**
   - The model is initialized as a sequential ANN using `tensorflow.keras`.
   - Layers:
     - Two hidden layers with ReLU activation functions.
     - One output layer.

3. **Training the ANN**
   - The ANN is compiled with:
     - **Optimizer**: Adam.
     - **Loss Function**: Mean Squared Error.
   - Fitted to the training data for 100 epochs with a batch size of 32.

4. **Making Predictions**
   - Predictions are made on the test set (`X_test`) and formatted using `numpy`.

---

## How to Use this Project

### Prerequisites
Make sure you have Python 3.7+ installed on your system. Install the required dependencies listed in the `requirements.txt` file.

### Installation
1. Clone this repository:
   ```bash
   git clone <repo-link>
   ```
2. Navigate to the project directory:
   ```bash
   cd <project-folder>
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Steps to Run
1. Place your dataset file (e.g., `Folds5x2_pp.xlsx`) in the `data/` directory.
2. Open and run the Jupyter Notebook (`ann.ipynb`) to execute all the cells sequentially.

---

## Requirements
The packages required for this project are:
- `numpy`
- `pandas`
- `tensorflow`
- `scikit-learn`
- `openpyxl`

You can install them all at once using:
```bash
pip install -r requirements.txt
```

---

## Project Highlights
- **Models:** Sequential ANN for predicting numeric values.
- **Libraries:** TensorFlow for deep learning, pandas for data manipulation, and scikit-learn for data splitting.
- **Dataset:** Provided in Excel format (`data/Folds5x2_pp.xlsx`).

---

## Acknowledgments
- This project uses TensorFlow for creating artificial neural networks.
- The dataset used in this example needs to be prepared in an accessible format (e.g., `.xlsx`).

Feel free to modify and enhance the project for your specific use case.

---

## License
This project is shared under the MIT License. Feel free to use, modify, and share it as per the license terms.