# Tyto Invest Website

Ce dossier contient le site vitrine de Tyto Invest.
Il est destiné à être hébergé gratuitement sur **GitHub Pages**.

## Comment mettre en ligne ?

1.  Ouvrez un terminal dans ce dossier :
    ```bash
    cd tyto-website
    ```

2.  Initialisez un nouveau dépôt Git :
    ```bash
    git init
    git add .
    git commit -m "Initial commit"
    ```

3.  Créez un nouveau dépôt **PUBLIC** sur GitHub (nommez-le par exemple `tyto-website`).

4.  Liez ce dossier à votre nouveau dépôt (remplacez l'URL par la vôtre) :
    ```bash
    git remote add origin https://github.com/VOTRE_NOM/tyto-website.git
    git branch -M main
    git push -u origin main
    ```

5.  Activez GitHub Pages :
    *   Allez sur GitHub > Settings > Pages.
    *   Source : `Deploy from a branch`.
    *   Branch : `main` / `root`.

## Nom de Domaine
Une fois votre domaine acheté (ex: `tytoinvest.com`), ajoutez-le dans les réglages "Custom domain" de GitHub Pages.
Cela créera automatiquement un fichier `CNAME` ici.
