# Support Vector Machine (SVM) from Scratch 💻🧠

This project implements a **Support Vector Machine (SVM)** classifier using only low-level tools like `NumPy`, without relying on machine learning libraries such as `scikit-learn`. It walks through the theory and practical application of SVM on a real-world dataset.

## 📁 Project Structure

```
SVM_from_scratch/
├── data/
│   └── breast-cancer (3).csv       # Binary classification dataset
├── notebooks/
│   └── SVM_from_scratch.ipynb      # Jupyter notebook with full implementation
└── README.md
```

## 🧬 Dataset

- **breast-cancer (3).csv**: Dataset used to classify tumors as malignant or benign.
- Features: medical metrics describing cell properties.
- Target: `0` for benign, `1` for malignant.

## 🚀 Features

- Manual implementation of:
  - Kernelized SVM (Linear Kernel by default)
  - Hinge loss
  - Gradient descent optimization
- Data preprocessing
- Training & evaluation
- Accuracy score reporting

## 🧪 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/SVM_from_scratch.git
   cd SVM_from_scratch
   ```

2. Open the Jupyter notebook:
   ```bash
   jupyter notebook notebooks/SVM_from_scratch.ipynb
   ```

3. Run the cells to:
   - Load and preprocess the dataset
   - Train the SVM model
   - Evaluate performance on test data

## 🛠 Technologies Used

- Python 3.x
- NumPy
- Pandas
- Jupyter Notebook

## 🎯 Learning Outcomes

- Understand the intuition behind SVM
- Implement SVM with gradient-based optimization
- Apply preprocessing to real-world data
- Interpret model performance metrics

## 📌 Credits

- Dataset: [UCI Machine Learning Repository](https://archive.ics.uci.edu/)
- Author: FW

---

