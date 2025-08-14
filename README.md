
# 📊 Tableau de Bord CRM avec Assistant de Données Local

Ce projet est une application web interactive qui permet de charger des fichiers CSV contenant des données commerciales (ventes, profits, catégories, régions, etc.), et de visualiser automatiquement un tableau de bord analytique enrichi. Il inclut également un **assistant IA local**, des **fonctionnalités de machine learning (ML)** simples, et une **interface responsive** grâce à Tailwind CSS.

## 🧰 Fonctionnalités

### 📁 Chargement de Données CSV
- Importez vos fichiers CSV contenant des colonnes comme `date`, `sales`, `profit`, `category`, `region`.
- Aperçu des 5 premières lignes pour validation.

### 🔢 Indicateurs Clés de Performance (KPIs)
- Ventes Totales
- Profit Total
- Valeur Moyenne des Ventes
- Nombre de Transactions
- Catégorie la plus vendue
- Région la plus profitable
- Marge de profit moyenne
- Croissance mensuelle

### 📈 Graphiques Dynamiques (Chart.js)
- Répartition des ventes par catégorie (camembert)
- Clustering K-Means (ventes vs profits)
- Histogramme des ventes
- Barres empilées (catégories vs régions)
- Tendances mensuelles
- Série temporelle quotidienne (profit)
- Nuage de points (profit vs ventes)
- Prévision de profit (régression linéaire)
- Prévision des ventes (ML)
- Détection d’anomalies dans les ventes (ML)

### 🤖 Assistant IA local (Chatbot)
- Posez des questions simples comme :
  - "ventes totales"
  - "profit total"
  - "nombre de transactions"
  - "ventes pour la catégorie 'Électronique'"
  - "profit pour la région 'Nord'"

### 💬 Analyse de Sentiment Client (Prototype)
- Entrez un commentaire client pour détecter un sentiment **positif**, **négatif** ou **neutre** à l’aide de mots-clés.

## 🧠 Technologies Utilisées

| Outil | Description |
|------|-------------|
| **HTML/CSS/JS** | Application statique et légère |
| **Tailwind CSS** | Mise en page et design réactif |
| **Chart.js** | Graphiques interactifs |
| **PapaParse** | Lecture et parsing des fichiers CSV |
| **JavaScript Vanilla** | Aucune dépendance majeure, tout est local |
| **Chart.js Date Adapter** | Gestion des dates dans les graphiques |

## 🗂 Structure des Fichiers

```
📁 projet/
├── index.html   ← Page principale (ce fichier contient tout le code)
└── README.md    ← Ce fichier de documentation
```

## 🚀 Utilisation

1. Ouvrez `index.html` dans votre navigateur.
2. Cliquez sur **Téléchargez votre fichier CSV** pour importer vos données.
3. Explorez les **KPIs**, les **graphiques**, et discutez avec **l’assistant**.
4. Essayez les fonctionnalités ML dans la section "Fonctionnalités ML avancées".

## 📌 Données attendues dans le CSV

| Colonne | Type attendu |
|---------|--------------|
| `date` | format ISO (`YYYY-MM-DD`) |
| `sales` | numérique |
| `profit` | numérique |
| `category` | texte |
| `region` | texte |

> ⚠️ Le fichier CSV doit avoir une première ligne contenant les en-têtes (`header=true` dans PapaParse).

## 👨‍🔬 Données de Démonstration

Si aucun fichier CSV n’est chargé, l'application génère automatiquement **100 lignes de données fictives** pour tester le tableau de bord.

## 📥 Déploiement

Ce projet peut être :
- ouvert localement dans n’importe quel navigateur moderne ;
- hébergé facilement sur GitHub Pages ou Netlify, car il ne nécessite aucun backend.

## 📝 Auteur

Ce projet est un prototype conçu pour la **visualisation locale de données CRM**, incluant des outils de BI simples et des démonstrations d’IA basées sur des règles.

