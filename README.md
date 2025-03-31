# **Lab 2: Deep Learning for Computer Vision with PyTorch** 🖥️🔬  

![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red?style=flat&logo=pytorch)  
![Status](https://img.shields.io/badge/Status-Completed-success)  
![License](https://img.shields.io/badge/License-MIT-blue)  

## **📌 Overview**  
Bienvenue dans **Lab 2: Deep Learning for Computer Vision**, un projet qui explore différentes architectures pour la classification d’images avec le dataset **MNIST** 🖼️. Ce projet fait partie du cours **Deep Learning** de l’**Université Abdelmalek Essaadi**.  

### **Modèles développés :**  
✅ **CNN (Convolutional Neural Network)** : Un réseau de neurones convolutionnel classique pour la classification des chiffres manuscrits.  
✅ **Faster R-CNN (Region-Based CNN)** : Un modèle avancé basé sur ResNet50 pour une classification plus robuste.  
✅ **VGG16 & AlexNet** : Deux modèles pré-entraînés affinés sur MNIST via *Transfer Learning*.  
✅ **Vision Transformer (ViT)** : Un modèle *Transformer* entraîné de zéro pour explorer une approche moderne en Vision par Ordinateur.  

Ce projet inclut l'**implémentation**, l'**entraînement**, l'**ajustement des hyperparamètres**, et la **comparaison des performances** entre ces architectures. L'ensemble est exécuté sur **Google Colab** avec accélération **GPU**.  

---

## **🔧 Features**  
📌 **Classification MNIST** : Implémente et compare 5 architectures (CNN, Faster R-CNN, VGG16, AlexNet, ViT).  
📌 **Analyse de Performance** : Évaluation basée sur l'**accuracy**, le **F1-score**, la **perte (loss)** et le **temps d'entraînement**.  
📌 **GPU Accéléré** : Utilisation d'un GPU **T4** pour des entraînements plus rapides.  
📌 **Fine-Tuning** : Adaptation de **VGG16 et AlexNet** à MNIST (1 canal, 10 classes).  
📌 **Vision Transformer** : Implémentation de ViT avec **patch embeddings** et **transformer layers**.  

---

## **📌 Table of Contents**  
- [Installation](#installation)  
- [Utilisation](#utilisation)  
- [Architecture du Projet](#architecture-du-projet)  
- [Résultats](#résultats)  
- [Conclusion](#conclusion)  
- [Auteur](#auteur)  
- [License](#license)  

---

## **🛠️ Installation**  

### **📌 Pré-requis**  
Avant de commencer, assure-toi d'avoir :  
✅ **Python 3.8+**  
✅ **Google Colab ou Jupyter Notebook**  
✅ **Une machine avec GPU (optionnel, mais recommandé)**  

### **📦 Dépendances**  
Installe les bibliothèques nécessaires avec :  
```bash
pip install torch torchvision numpy scikit-learn matplotlib tqdm
```
Si tu utilises un **environnement virtuel** :  
```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
```

### **📂 Cloner le projet**  
```bash
git clone https://github.com/votre-utilisateur/lab2-computer-vision.git
cd lab2-computer-vision
```

---

## **🚀 Utilisation**  

1️⃣ **Lancer le Notebook**  
📜 Ouvre **`lab2_computer_vision.ipynb`** sur Jupyter ou **Google Colab**.  

2️⃣ **Exécuter le code**  
Clique sur **"Run All"** ou exécute chaque cellule individuellement :  
- Télécharge **MNIST** via `torchvision`.  
- Entraîne et évalue **tous les modèles**.  
- Affiche les résultats sous forme de **graphes et métriques**.  

3️⃣ **Accélération GPU**  
Active le **GPU** sur Colab :  
📌 **Runtime > Change runtime type > GPU**  

---

## **📂 Architecture du Projet**  
```
lab2-computer-vision/
├── lab2_computer_vision.ipynb  # Notebook principal avec implémentation
├── requirements.txt            # Liste des dépendances
├── results/                    # Dossier contenant les résultats et graphiques
└── README.md                   # Ce fichier 📄
```

Le dataset **MNIST** est téléchargé dynamiquement via `torchvision.datasets.MNIST`.

---

## **📊 Résultats**  

📌 **Comparaison des Modèles** (après exécution)  

| Modèle       | Accuracy | F1-Score | Loss  | Training Time |
|-------------|----------|---------|------|--------------|
| **CNN**     | [TBD] % | [TBD]   | [TBD] | [TBD] s |
| **Faster R-CNN** | [TBD] % | [TBD] | [TBD] | [TBD] s |
| **VGG16**   | [TBD] % | [TBD]   | [TBD] | [TBD] s |
| **AlexNet** | [TBD] % | [TBD]   | [TBD] | [TBD] s |
| **ViT**     | [TBD] % | [TBD]   | [TBD] | [TBD] s |

---

## **📌 Conclusion**  
💡 *Les réseaux convolutionnels classiques restent dominants pour MNIST, mais ViT montre un potentiel intéressant pour des datasets plus complexes.*  

---

## **👨‍💻 Auteur**  

| Nom | GitHub |
|----|--------|
| 🎓 **[ sihamErmk]** | [@sihamErmk](https://github.com/sihamErmk) |

---

## **📜 License**  
🔖 Ce projet est sous licence **MIT** – Utilisation libre, mais sans garantie.  

---

## **🙌 Remerciements**  
🔥 **PyTorch Team** – Pour une librairie incroyable.  
💻 **Google Colab** – Pour un accès GPU gratuit.  
📊 **MNIST Dataset** – Pour être un benchmark essentiel en Deep Learning.  

---

🚀 **Bon apprentissage et bon code !** 🎯
