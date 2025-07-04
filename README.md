# Quantum vs Classical Generative Models

This project explores and compares the performance of classical and quantum generative models in the context of molecular generation. We evaluate models including Variational Autoencoders (VAE), Wasserstein GANs (WGAN), and Quantum Circuit Born Machines (QCBM) on SMILES-derived molecular fingerprints.

Our goal is to investigate whether quantum models offer any practical advantages over classical models in low-data and evaluation-limited regimes — a step toward identifying **Potential Practical Quantum Advantage (PPQA)** in real-world applications like drug discovery.

## 📄 Project Components

- `code/model_comparison.py`: Core implementation of QCBM, VAE, and WGAN models
- `report/QML_Report.pdf`: Detailed technical report with methodology and results
- `presentation/Quantum_Presentation.pdf`: Final presentation slides

## 🧪 Models Included

- **Quantum Circuit Born Machine (QCBM)**
- **Variational Autoencoder (VAE)**
- **Wasserstein GAN (WGAN)**

## 🧬 Dataset

Molecular fingerprints derived from SMILES strings using RDKit. (Not included due to restrictions.)

## 📊 Evaluation Metrics

- **Minimum Value (MV)**
- **Utility (Top 5% Avg.)**
- **Quality Coverage (Cq)**

> ⚠️ This project is part of academic research and is shared for educational purposes only. Please do not copy or reuse without permission.
