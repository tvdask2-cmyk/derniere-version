# GUIDE D'INSTALLATION GITHUB (TRÈS IMPORTANT)

Bonjour,

Si vous lisez ce fichier, c'est que vous avez bien téléchargé le projet.
Le dossier `.github` (invisible sur Windows) a été remplacé par un dossier VISIBLE nommé **`github_config`**.

## VOICI LA MARCHE À SUIVRE (3 ÉTAPES SIMPLES) :

### 1. SUR VOTRE ORDINATEUR
Vérifiez que vous voyez bien le dossier **`github_config`** dans ce dossier.

### 2. SUR LE SITE GITHUB
Envoyez TOUS les fichiers (y compris le dossier `github_config`) sur votre dépôt GitHub en cliquant sur "Upload files" puis "Commit changes".

### 3. L'ASTUCE FINALE (SUR LE SITE GITHUB)
Une fois les fichiers envoyés, GitHub ne sait pas encore que ce dossier est spécial. Vous devez le renommer.

1.  Cliquez sur le dossier **`github_config`** dans la liste des fichiers sur GitHub.
2.  Cliquez sur les **3 petits points (...)** en haut à droite de la liste des fichiers -> **Rename**.
3.  Changez le nom : effacez `github_config` et écrivez **`.github`** (N'oubliez pas le point au début !).
4.  Cliquez sur le bouton vert **Commit changes**.

**C'EST TOUT !**
Dès que vous avez renommé ce dossier, l'onglet **"Actions"** en haut de la page va s'allumer et commencer à fabriquer votre logiciel `.msi` (Windows) et `.dmg` (Mac).

Attendez 15 minutes, et votre logiciel sera disponible dans la section **"Releases"** (à droite de la page d'accueil de votre dépôt).
