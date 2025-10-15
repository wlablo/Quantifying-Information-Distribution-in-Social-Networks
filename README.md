# Quantifying Information Distribution in Social Networks
This repository contains the full dataset, analysis scripts, and figures accompanying the paper:

**“Quantum Graph Theory as a Novel Framework for Analyzing Social Communication Networks”**

---

## 📘 Overview
The project integrates **graph theory**, **quantum information concepts**, and **Shannon entropy** to analyze structural and informational balance in social media communication networks.

We propose a new measure — **Structural Entropy Index of a Community (SEIC)** — that quantifies internal communication balance within detected communities.

---

## 📂 Repository Structure

- **data/** – real-world dataset (Twitter/X network related to #Zandberg)
- **notebooks/** – reproducible Jupyter notebooks for all analyses
- **figures/** – normalized circular graphs and histograms
- **paper/** – final LaTeX source and PDF of the article

---

## 🧮 Key Methods

1. **Network Construction:** directed graph based on mentions and retweets  
2. **Centrality Measures:** degree, betweenness, closeness — normalized to [0,1]  
3. **Entropy Calculation:** Shannon entropy applied at community level  
4. **SEIC Metric:** normalized structural entropy indicator  
5. **Community Detection:** Louvain algorithm with stability checks  

---

## ⚙️ Installation

```bash
git clone https://github.com/wlablo/Quantifying-Information-Distribution-in-Social-Networks.git
cd Quantifying-Information-Distribution-in-Social-Networks
pip install -r requirements.txt
