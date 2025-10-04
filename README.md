# Login Checker 

This project is an assignment exploring different data structures for efficiently checking login (username) uniqueness at scale.  
It compares the performance of:
- Linear Search
- Binary Search
- Hashing
- Bloom Filter
- Cuckoo Filter

## 📂 Files
- `login_checker.ipynb` – Jupyter/Colab notebook with dataset generation, algorithms, and experiments
- `results/` – Plots and experiment outputs
- `datasets/` – Generated usernames dataset (compressed)

## ⚡ Features
- Dataset generation for millions of usernames
- Implementation of multiple search/check algorithms
- Runtime and memory usage comparison
- Plots showing performance across scales
- Parallelized experiments for speed (works in Google Colab)

## 🚀 How to Run
1. Open the notebook in **Google Colab**:
   - [Open in Colab](https://colab.research.google.com/) and upload `login_checker.ipynb`
2. Run all cells in order.
3. Adjust `ns` in the code to change dataset size, e.g.:
   ```python
   ns = [10000, 100000, 1000000]  # experiment sizes
4. Plots and CSV results will be saved under the results/ folder.


## 🧰 Requirements
pip install numpy matplotlib joblib pybloomfiltermmap3 cuckoopy

## 📁 Dataset
https://drive.google.com/drive/folders/1mm2xzQQ9HhaFuP4tf9muwaXtuVSrVd_e?usp=drive_link

