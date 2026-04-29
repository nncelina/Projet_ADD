# 📊 Analyse Discriminante de la Pauvreté monétaire au Sénégal (EHCVM 2022)

## 🚀 Aperçu du projet

Ce projet vise à identifier les caractéristiques qui distinguent les ménages pauvres des ménages non pauvres au Sénégal en 2022.

L’approche repose sur une **Analyse Factorielle Discriminante (AFD)** appliquée aux données de l’**Enquête Harmonisée sur les Conditions de Vie des Ménages (EHCVM 2022)**.

---

## 🎯 Objectifs

* Identifier les variables les plus discriminantes du statut de pauvreté
* Dresser un profil type des ménages pauvres vs non pauvres

---

## 📁 Contenu du repository

* `Base_finale.dta` : base de données utilisée (échantillon nettoyé)
* `Projet_ADD.ipynb` : notebook principal (prétraitement, analyse, modélisation)
* `README.md` : présentation du projet

---

## 🧠 Méthodologie

### 1. Préparation des données

* Sélection de **7038 ménages**
* Construction d’un ensemble de **11 variables explicatives** (âge, taille du ménage, équipements, dépenses, etc.)
* Définition de la variable cible :

  * **Pauvre / Non pauvre** selon le seuil de consommation par tête

### 2. Réduction de dimension

* Application d’une **Analyse des Correspondances Multiples (ACM)** pour intégrer les variables qualitatives

### 3. Modélisation

* Utilisation de l’**Analyse Factorielle Discriminante (AFD)** pour :

  * Construire un axe discriminant (LD1)
  * Séparer les deux groupes de ménages

---

## 📊 Résultats clés

### 🔍 Profil des ménages pauvres

* Taille élevée (~11–12 individus)
* Faible niveau d’équipement
* Dépenses non alimentaires faibles
* Chef de ménage :

  * masculin
  * en couple
  * vivant en zone rurale
  * actif dans le secteur primaire ou sans emploi
  * peu ou pas bancarisé

### ⚡ Performance

* **Précision globale : 80,23 %**

---

## 📈 Variables les plus discriminantes

* Axes issus de l’ACM
* Nombre d’équipements
* Taille du ménage
* Nombre de souscriptions financières

---

## 🎥 Ressources complémentaires

* 📓 Notebook interactif :
  https://nbviewer.org/github/nncelina/ADD_ISE1/blob/main/Projet_ADD.ipynb

* 🎬 Vidéo de présentation :
  https://kcgu.my.canva.site/video-add-afd

---

## 📌 Conclusion

Ce projet montre que la pauvreté ne se limite pas à un seuil monétaire.
Elle est fortement liée à des facteurs structurels comme :

* la taille du ménage
* l’accès aux ressources
* l’insertion économique
---

## 👥 Auteurs

* COULIBALY Khadidiatou
* DIENG Samba
* HABA Fromo Francis
* KAFANDO G Judicaël Oscar
* NGUEMFOUO NGOUMTSA Célina

Encadré par : Mme SARR Iphygénie

