# 🧃 Machine à Boissons – Simulation en Python

Ce projet est une **simulation en ligne de commande** d’une machine à boissons, développée en Python, avec une logique orientée objet. Le programme utilise 4 agents principaux pour gérer les différentes étapes de la commande d'une boisson.

## 🚀 Fonctionnalités

- Choix entre 4 boissons :  
  - ☕ Café  
  - 🍵 Thé  
  - 🍫 Chocolat  
  - 🥤 Coca Cola
- Prix personnalisés pour chaque boisson
- Stock initial configurable
- Vérification du paiement
- Préparation virtuelle de la boisson
- Messages clairs étape par étape

## 🧠 Architecture

Le programme repose sur 4 classes/agents :

| Classe             | Rôle                                                                 |
|--------------------|----------------------------------------------------------------------|
| `AgentPrincipal`   | Orchestration globale, interaction avec l'utilisateur                |
| `AgentBoisson`     | Gestion du stock, vérification et retrait de boisson                 |
| `AgentPaiement`    | Suivi de l'argent inséré et validation du paiement                   |
| `AgentPreparation` | Simule la préparation d'une boisson                                  |

---

## 📦 Fichiers

- `main.py` : fichier principal contenant tout le code de simulation

---

## ▶️ Exécution

```bash
python main.py
