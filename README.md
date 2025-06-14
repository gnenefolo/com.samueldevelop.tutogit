# Documentation du tuto Github avec Git

## Initialisation du dépôt

```bash
git init
git remote add origin SSH_REPO
```

## Rédiger un commit

```text

Titre du commit

Description de notre commit avec des informations sur
l'évolution du projet
```

## Envoyer un commit sur le dépôt distant

```bash
git add .
git commit -m "Titre du commit"
git push origin main
```

## Création d'une branche

```bash
git checkout -b NOM_BRANCHE
```

## Gestion des Pull Requests (PR)

```text
Pour la bonne pratique, on va intégrer la notion de revue de code. Pour cela, on va créer une branche, faire des modifications, les envoyer sur le dépôt distant et créer une Pull Request (PR) pour que quelqu'un d'autre puisse valider les modifications. Cela nous permetra de tester la gestion des branches et des PR.
```

