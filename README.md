# Deep Learning for Vulnerability Detection: A Hybrid Model with Code Gadgets and Images

**Author:** Jerome Masilungan Brazil  
**Supervisor:** Lorena González Manzano  
**Institution:** Universidad Carlos III de Madrid  
**Program:** Master in Big Data Analytics  
**Thesis Year:** 2024–2025  

---

## Overview

This repository contains the code, models, and input files for my Master Thesis:

> **"Deep Learning for Vulnerability Detection: A Hybrid Model with Code Gadgets and Images"**

The project presents a hybrid deep learning system that combines semantic analysis (BiLSTM) and visual inspection (CNN) to detect vulnerabilities in C/C++ code. It reimplements and extends VulDeePecker and IVul under a shared framework. Two fusion strategies are evaluated on CWE-119 and CWE-399, showing that hybrid models outperform standalone baselines.

---

## Contents

| File | Description |
|------|-------------|
| `cwe119_cgd.txt`, `cwe399_cgd.txt` | Datasets for CWE-119 and CWE-399 from [VulDeePecker CGD](https://github.com/CGCL-codes/VulDeePecker). |
| `lstm_cwe119_tuning.ipynb`, `lstm_cwe399_tuning.ipynb` | Hyperparameter tuning for BiLSTM models (VDPython), adapted from [johnb110/VDPython](https://github.com/johnb110/VDPython). |
| `lstm_cwe119_tuned.ipynb`, `lstm_cwe399_tuned.ipynb` | Final training scripts for the tuned BiLSTM models. |
| `CNN.ipynb` | Tuning and training of CNN models based on the [IVul architecture](https://github.com/lgmanzan/IVul). |
| `hybridA.ipynb`, `hybridB.ipynb` | Implementation of two hybrid models combining semantic and visual features. Includes tuning and training. |
