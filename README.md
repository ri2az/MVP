# 🏀 NBA Stats & MVP Predictor – Streamlit App

Une application Streamlit interactive qui affiche les statistiques des joueurs NBA pour une saison donnée, tout en proposant un système de scoring pour estimer les candidats au titre de MVP (Most Valuable Player).

---

## 🚀 Fonctionnalités

- 🔍 **Exploration des stats NBA par saison (1981 à 2025)**
- 👤 **Consultation individuelle des statistiques d’un joueur**
- 🏆 **Calcul d’un score MVP basé sur les performances brutes**
- 🔮 **Intégration de statistiques avancées (PER, TS%, WS)**
- 📈 **Graphique interactif des scores MVP avec nuances de couleur**
- 🕰️ **Simulation de l’évolution historique des scores ou probabilités MVP**
- 📊 **Tri automatique des joueurs selon les points par match (PTS)**
- 🔁 **Suppression automatique des doublons de joueurs (ex : changement d’équipe)**

---

## ⚙️ Installation

1. Clone ce dépôt :

```bash
git clone https://github.com/ton-profil/https://github.com/ri2az/MVP.git
cd mvp
```

### 2️⃣ Installer les dépendances
Assurez-vous d'avoir Python 3 installé, puis exécutez :
```sh
pip install -r requirements.txt
```

### 3️⃣ Lancer l'application
```sh
streamlit run app.py
```

### 4️⃣ Lancer l'application sur Streamlit !

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://riaaz-mvp.streamlit.app//)

## 🧠 Logique MVP
Le **MVP Score** combine plusieurs métriques pondérées :
- 📌 PTS (40%)
- 📌 AST (20%)
- 📌 TRB (15%)
- 📌 STL, BLK, FG%, 3P%, FT%…
- 📌 Statistiques avancées : PER, TS%, WS

## ⚙️ Technologies utilisées
- **Python 3** 🐍
- **Streamlit** 🖥️ (interface utilisateur)
- **Plotly** 📊 (visualisation des graphiques)
- **Pandas** 📄 (gestion des données)
- **Scikit-learn** 🌐

## 📜 Licence
Ce projet est sous licence **MIT**. Vous pouvez le modifier et l'utiliser librement.

 🚀

