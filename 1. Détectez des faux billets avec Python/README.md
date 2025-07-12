<img src="../Images/money.png" alt="Dashboard Profil" width="1100"/>

# Projet 1 – Détection de faux billets avec Python
## Contexte du projet

Dans le cadre d’une mission pour l’ONCFM (Organisation nationale de lutte contre le faux-monnayage), il m’a été confié la création d’un outil permettant de distinguer les vrais billets des contrefaçons à partir de mesures physiques réalisées par scan.
L’enjeu est double : fiabiliser et accélérer la détection directement sur le terrain, via une solution basée sur le machine learning, utilisable facilement par les agents

---

## Démarche suivie

- **Traitement des données** : 1 500 billets (1 000 authentiques / 500 faux), 6 caractéristiques géométriques par billet.
- **Analyse exploratoire** : traitement des valeurs manquantes (imputation par régression linéaire), visualisation des distributions, corrélations, outliers, etc.
- **Séparation du jeu d’entraînement et de test**.
- **Test de plusieurs algorithmes de classification** :
  - Régression logistique
  - K plus proches voisins (KNN)
  - Random Forest
  - K-means (non supervisé, utilisé pour la comparaison)
- **Évaluation comparative** : précision, rappel, F1-score, matrice de confusion (analyse des faux positifs et faux négatifs).
- **Choix du modèle final** : sélection du modèle le plus robuste et interprétable.
- **Développement d’un outil métier :**, Création d’une mini-application (notebook interactif) permettant aux agents de charger facilement un fichier et d’obtenir la prédiction pour chaque billet.

<img src="../Images/billet.png" alt="Dashboard Profil" width="400"/>

---

## Livrables du dossier

- **Livrables** :
    - *Notebook analyse* : Préparation des données, analyse exploratoire, entraînement, comparaison et sélection des modèles
    - *Notebook application* : Application prête à l’emploi, utilisable directement sur de nouveaux lots de billets
    - *Présentation finale* : support PPT synthétique des résultats et recommandations

---

## Ce que ce projet démontre

- Pilotage d’un projet machine learning complet, du cadrage à la mise à disposition d’un outil fonctionnel
- Maîtrise et comparaison d’algorithmes de classification supervisée et non supervisée
- Justification des choix techniques et pédagogie pour un public non technique
- Une documentation claire, vulgarisée et structurée pour un public métier.
- Une approche réutilisable, prête à être adaptée à d’autres cas de détection.

---

## Pour aller plus loin

- Les notebooks sont documentés et commentés pas à pas.


