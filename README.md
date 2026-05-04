# 💪 Fitness Tracker — Programme Remise en Forme 8 Semaines

> Un tableau de suivi interactif pour accompagner une remise en forme progressive, conçu pour les débutants reprenant l'activité physique.

---

## 📋 À propos

Ce projet est une application React interactive permettant de suivre un programme de remise en forme sur **8 semaines**, basé uniquement sur :
- 🏋️ Exercices au poids de corps
- 🪢 Corde à sauter (progression 300 → 1000 sauts)
- 🧘 Séances d'étirements en alternance

**Profil cible :** Personne débutante, sédentaire, souhaitant reprendre progressivement.

---

## ✨ Fonctionnalités

- 📅 Navigation semaine par semaine (8 semaines)
- ✅ Tracker journalier interactif (cocher les jours accomplis)
- 📈 Progression automatique des exercices (durée, sauts)
- 💬 Conseil motivant personnalisé chaque semaine
- 🥗 Rappels nutrition constants
- 📊 Barre de progression globale

---

## 🚀 Installation

### Prérequis
- Node.js ≥ 18
- npm ou yarn

### Lancer le projet

```bash
# Cloner le repo
git clone https://github.com/TON_USERNAME/fitness-tracker.git
cd fitness-tracker

# Installer les dépendances
npm install

# Lancer en développement
npm run dev
```

---

## 🏗️ Stack technique

| Outil | Usage |
|-------|-------|
| React 18 | UI / composants |
| Vite | Bundler |
| CSS-in-JS | Styles inline |

---

## 📁 Structure du projet

```
fitness-tracker/
├── public/
│   └── index.html
├── src/
│   ├── App.jsx          # Composant principal
│   ├── data/
│   │   └── weeks.js     # Données des 8 semaines
│   └── main.jsx         # Point d'entrée
├── package.json
├── vite.config.js
└── README.md
```

---

## 📊 Programme détaillé

| Semaine | Thème | Effort | Sauts corde |
|---------|-------|--------|-------------|
| 1 | 🌱 Mise en route | 30 sec | 3 × 100 |
| 2 | 🔥 Prise de rythme | 30 sec | 3 × 150 |
| 3 | ⚡ Montée en charge | 35 sec | 3 × 200 |
| 4 | 🏗️ Consolidation | 35 sec | 3 × 250 |
| 5 | 💪 Passage à 40 sec | 40 sec | 3 × 300 |
| 6 | 🎯 Endurance | 40 sec | 3 × 333 |
| 7 | 🚀 Cap des 1000 sauts | 45 sec | 2 × 500 |
| 8 | 🏆 Bilan & nouveau départ | 45 sec | 2 × 500 |

### Exercices (4 par séance, 3 séries)
- Squats
- Pompes (genoux possibles en début)
- Gainage planche
- Fentes alternées

### Repos entre exercices : 60 secondes

---

## 🥗 Nutrition associée

Basé sur la formule **Mifflin-St Jeor** pour un profil 29 ans / 90 kg / 1m86 :

| Indicateur | Valeur |
|------------|--------|
| Calories/jour | 1 900 – 2 000 kcal |
| Protéines | 150 – 160 g/jour |
| Glucides | 180 – 200 g/jour |
| Lipides | 60 – 70 g/jour |
| Hydratation | 2 – 2,5 L/jour |

---

## 🧠 Base scientifique

> L'exercice physique régulier est reconnu comme aussi efficace qu'un antidépresseur léger dans les cas de dépression légère à modérée.
>
> — Schuch et al., 2016, *JAMA Psychiatry*

---

## 🤝 Contribution

Les PR sont les bienvenues. Pour les changements majeurs, ouvrez d'abord une issue.

---

## 📄 Licence

MIT — Libre d'utilisation, de modification et de distribution.

---

*Fait avec 💪 et beaucoup d'endorphines*
