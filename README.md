# Anomalous Transport Scaling Analysis

This repository contains the Jupyter notebook and numerical data used for the **scaling analysis of anomalous transport** near the transition between the **Anderson insulator (AI)** and **critical regime**.

## Contents

* `AICI_tranition_RBCI_p04.ipynb` — Jupyter notebook containing the complete scaling analysis.
* `sigmaxy_L32.txt` — Data for system size \(L=32\).
* `sigmaxy_L64.txt` — Data for system size \(L=64\).
* `sigmaxy_L96.txt` — Data for system size \(L=96\).
* `sigmaxy_L128.txt` — Data for system size \(L=128\).
* `sigmaxy_L192.txt` — Data for system size \(L=192\).
* `sigmaxy_L256.txt` — Data for system size \(L=256\).
* `sigmaxy_L384.txt` — Data for system size \(L=384\).

## Analysis

The notebook performs the finite-size scaling analysis of the conductivity data for different system sizes. It can be used to reproduce the scaling plots and extract the critical behavior and associated scaling parameters.

## Requirements

The analysis requires Python with the following packages:

* NumPy
* SciPy
* Matplotlib
* Jupyter Notebook

Install the required packages using:

```bash
pip install numpy scipy matplotlib jupyter
```

## How to use

Clone or download this repository and open the notebook:

```bash
jupyter notebook AICI_tranition_RBCI_p04.ipynb
```

Make sure that the notebook and all the corresponding `.txt` data files are located in the same directory.

Run the notebook cells sequentially to reproduce the analysis and figures.

## Data

The `.txt` files contain the conductivity data for the different system sizes used in the finite-size scaling analysis.

## Reproducibility

The repository is provided to facilitate reproduction and further exploration of the scaling analysis presented in the associated research work.

## Author

**Naba Prakash Nayak**

Department of Physics, Universität Regensburg

---

If you use this repository or the accompanying analysis in your work, please cite the associated research publication/preprint.
