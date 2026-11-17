# 23009361-Salmane-Khaoula-G3-FIN
# F3 — Prévision de l'inflation (Maroc)

**Auteur :** Salmane Khaoula  
**Code Apogée :** 23009361  
**Groupe :** 3  
**Filière :** S7 FIN / S7 CI  
**Sujet :** F3 – Prévision de l'inflation  

**Dépôt :** https://github.com/[ton-identifiant]/CodeApogee-Nom-Groupe]

---

## 1. Résumé du projet

Ce projet vise à prévoir l'inflation mensuelle marocaine à horizon 1 mois à partir des données officielles de la Banque Al-Maghrib (BKAM).

**Problématique :**  
Peut-on prévoir l'inflation mensuelle avec une erreur absolue moyenne inférieure à celle d'une marche aléatoire ?

**Objectif mesurable :**  
Obtenir une MAE inférieure d'au moins 15 % à celle de la référence naïve (dernière valeur observée) sur la période de test 2024-2026.

**Algorithme principal :** Ridge Regression (n°2 du support)
---

## 2. Données

- **Source :** Banque Al-Maghrib (BKAM) – Inflation et inflation sous-jacente
- **Fichier :** `data/raw/BKAM Inflation et inflation sous jacente.xlsx`
- **Période :** Janvier 2018 → Septembre 2026
- **Fréquence :** Mensuelle
- **Date d'extraction :** Novembre 2026
- **Licence :** Données publiques

---

## 3. Installation

```bash
pip install -r requirements.txt
