# 🧠 Deep-BBBP-Neural-Classifier

A deep learning project built with **PyTorch** to predict **Blood-Brain Barrier Penetration (BBBP)** from molecular structures using **Morgan Fingerprints** generated with **RDKit**.

---

## 📊 Results

- ✅ Test Accuracy: **87.80%**
- ✅ ROC-AUC Score: **0.8955**

---

## 🛠️ Tech Stack

- Python
- PyTorch
- RDKit
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 📂 Dataset

This project uses the **MoleculeNet BBBP** dataset, where molecules are classified based on their ability to cross the Blood-Brain Barrier.

---

## ⚙️ Workflow

- Processed molecular **SMILES** using **RDKit**
- Generated **2048-bit Morgan Fingerprints (Radius = 2)**
- Built a **Deep Feed-Forward Neural Network (ANN)** using **PyTorch**
- Trained the model using **Binary Cross Entropy Loss** and the **Adam Optimizer**
- Evaluated performance using **Accuracy** and **ROC-AUC**

---

## 🏗️ Model Architecture

```
2048 Input Features
        │
Linear (2048 → 512)
BatchNorm + ReLU + Dropout(0.3)
        │
Linear (512 → 256)
ReLU
        │
Linear (256 → 1)
Sigmoid
```

---

## 🚀 Future Work

- Graph Neural Networks (PyTorch Geometric)
- Molecular Graph Representations
- Hyperparameter Optimization

---

## 👨‍💻 Author

**Tolaram Kewatiya**

Integrated M.Sc. Chemistry (3rd Year)

National Institute of Technology Durgapur

GitHub:
https://github.com/tolaramkewatiya-hub




