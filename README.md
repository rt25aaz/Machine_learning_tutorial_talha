# How Do SVM Kernels Change Classification?  
## A Tutorial Using the Banknote Authentication Dataset

This project explains how Support Vector Machine (SVM) kernel choice affects classification performance and decision boundaries.  
It compares linear, polynomial, and RBF kernels on the Banknote Authentication dataset, and then explores how the RBF hyperparameters `C` and `gamma` change model behaviour.

## Repository contents

- `svm_banknote.ipynb` — main notebook with full code, results, and figures
- `SVM_Kernels_Banknote_Tutorial.pdf` — tutorial PDF
- `banknote_authentication.csv` — dataset used in the notebook
- `requirements.txt` — Python package requirements
- `LICENSE` — licence for this repository

## Installing dependencies

It is recommended to create a virtual environment first, then install the required packages:

```bash
pip install -r requirements.txt
