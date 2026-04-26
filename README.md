# 🧹 Site de Micro-Entreprise : Automatisation des Services de Ménage & Repassage
### Une Solution Digitale Intégrée avec IA et Data Pipeline

<p align="center">
  <img src="https://img.shields.io/badge/Systeme.io-Landing%20Page-blue?logo=systemeio" />
  <img src="https://img.shields.io/badge/Google%20Sheets-Data%20Storage-green?logo=googlesheets" />
  <img src="https://img.shields.io/badge/Google%20Apps%20Script-Automation-orange?logo=google" />
  <img src="https://img.shields.io/badge/HTML%2FCSS%2FJS-AI%20Generated-red?logo=html5" />
  <img src="https://img.shields.io/badge/IA-Code%20Generation-purple?logo=openai" />
</p>

---

## 📋 Résumé du Projet

Ce projet présente la conception et le déploiement d'un site web pour une micro-entreprise de services de ménage et repassage. L'innovation majeure réside dans l'intégration poussée de l'**intelligence artificielle** pour la génération de code et la mise en place d'une **chaîne d'automatisation complète** (Data Pipeline) pour la gestion des réservations, la collecte de données, la génération de devis et la communication client. Ce projet met en lumière mes compétences en **Data Engineering**, **automatisation des processus métier** et **intégration de solutions technologiques**.

---

## 🎯 Problématique & Solution

**Problématique :** Gérer efficacement les réservations, les informations clients, la génération de devis et la communication pour une micro-entreprise de services, tout en minimisant l'intervention manuelle.

**Solution :** Un site web interactif développé avec Systeme.io, intégrant un formulaire de réservation multi-étapes. Les données collectées sont automatiquement traitées via un backend sans serveur (Google Apps Script) pour :
- Stocker les informations client dans Google Sheets.
- Générer des devis contractuels personnalisés (Google Docs).
- Envoyer des notifications SMS automatiques.
- Planifier des rendez-vous dans Google Calendar.

---

## ⚙️ Architecture & Flux de Données (Data Pipeline)

L'architecture du système est conçue pour une automatisation maximale, transformant les données brutes des clients en informations exploitables et en actions concrètes :

1.  **Interface Client (Frontend)** : Site web hébergé sur Systeme.io avec un formulaire de réservation HTML/CSS/JS (code généré par IA).
2.  **Collecte de Données** : Soumission du formulaire via une requête `POST` vers un script Google Apps Script.
3.  **Traitement & Stockage (Backend)** : Le script Google Apps Script (`doPost`) :
    -   Récupère les paramètres du formulaire.
    -   Enregistre les données dans une feuille Google Sheets dédiée (`data particulier`).
    -   Déclenche la génération automatique d'un devis personnalisé.
    -   Envoie une notification SMS au prestataire.
    -   Crée un événement dans Google Calendar.
4.  **Génération de Documents** : Utilisation de Google Docs comme modèle pour générer des devis contractuels, pré-remplis avec les informations du client.
5.  **Communication Automatisée** : Envoi de SMS via l'API Textbelt pour informer le prestataire d'une nouvelle réservation.

Ce flux de données illustre une approche "no-code" / "low-code" complétée par des scripts personnalisés, optimisant l'efficacité opérationnelle et la gestion de la relation client.

---

## 🛠️ Technologies & Compétences

*   **Plateforme Web** : Systeme.io (création de pages, formulaires, hébergement)
*   **Collecte & Stockage de Données** : Google Sheets (base de données client, suivi des réservations)
*   **Automatisation & Backend** : Google Apps Script (traitement des formulaires, intégration API, logique métier)
*   **Développement Frontend** : HTML, CSS, JavaScript (pour le formulaire interactif, code généré par IA)
*   **Intégration API** : Textbelt API (envoi de SMS), Google Drive API (génération de devis), Google Calendar API (gestion des rendez-vous)
*   **Intelligence Artificielle** : Utilisation d'outils d'IA pour la génération et l'optimisation des codes HTML/CSS/JS et des scripts d'automatisation.
*   **Compétences Data Analyst** : Conception de formulaires pour la collecte de données structurées, gestion de flux de données, automatisation de rapports (devis), analyse des données de réservation (potentiel).

---

## 📁 Livrables

*   `amzarepassage.fr/page web/pages en html/Menage et repassage a domicile _ Formulaire de reservation et demande de devis.html` : Page principale du formulaire.
*   `amzarepassage.fr/appscript code feuille de calcul amza.rtf` : Script Google Apps Script pour l'automatisation.
*   `amzarepassage.fr/amza repassage particulier .xlsx` : Exemple de feuille Google Sheets pour le suivi des réservations.
*   `images/` : Captures d'écran du site et du processus.

---

## 📸 Aperçu du Projet

Voici quelques aperçus du site et de son fonctionnement :

### Page d'accueil du site

[AJOUTER IMAGE ICI : Capture d'écran de la page d'accueil de votre site amzarepassage.fr]

### Formulaire de réservation

[AJOUTER IMAGE ICI : Capture d'écran du formulaire de réservation multi-étapes]

### Exemple de devis généré

[AJOUTER IMAGE ICI : Capture d'écran d'un devis généré automatiquement]

---

*Par Hamza Yousfi, Data Analyst (2026)*
