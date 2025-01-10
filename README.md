# Milyes

Ce projet est une application mobile gérant divers modules tels que le Bluetooth, la gestion des cartes SIM et IMEI, la connexion LTE, et bien plus encore.

## Installation

1. **Cloner le dépôt :**

    ```bash
    git clone https://github.com/milyes/milyes.git
    cd milyes
    ```

2. **Créer un environnement virtuel et l'activer :**

    ```bash
    virtualenv venv
    source venv/bin/activate
    ```

3. **Installer les dépendances Python :**

    ```bash
    pip install -r requirements.txt
    ```

4. **Initialiser et configurer les modules :**

    ```bash
    ./setup.sh
    ```

5. **Lancer le serveur :**

    ```bash
    python manage.py runserver
    ```

## Modules

1. **Bluetooth :** Gestion du module Bluetooth.
2. **SIM & IMEI :** Gestion des cartes SIM et des IMEI.
3. **LTE :** Partage de connexion LTE.
4. **Numéros de Mobile :** Gestion des numéros de mobile.
5. **Services Client :** Gestion des services client.
6. **IA :** 
    - Analyse des Données
    - Réponses Intelligentes
    - Optimisation des Performances
    - Personnalisation et Recommandations

## Configuration des APIs REST

Les endpoints de l'API sont configurés de la manière suivante :

- **GET /api/items** : Récupérer les éléments.
- **POST /api/items** : Ajouter un nouvel élément.
- **PUT /api/items/{id}** : Mettre à jour un élément existant.
- **DELETE /api/items/{id}** : Supprimer un élément.

## Déploiement

1. **Migrer la base de données :**

    ```bash
    python manage.py migrate
    ```

2. **Collecter les fichiers statiques :**

    ```bash
    python manage.py collectstatic --noinput
    ```

3. **Lancer le serveur :**

    ```bash
    python manage.py runserver
    ```

## Auteur

Créé par [Milyes](https://github.com/milyes).

---

Pour toute question ou assistance, n'hésitez pas à contacter l'auteur du projet.
