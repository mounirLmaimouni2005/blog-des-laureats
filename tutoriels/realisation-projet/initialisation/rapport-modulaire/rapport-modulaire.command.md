# Journal des commandes — Rapport modulaire

## 1. Création de la structure du rapport

```bash
mkdir rapport/chapitres
```

## 2. Initialisation des fichiers Markdown

```bash
touch rapport/README.md
touch rapport/chapitres/README.md
touch rapport/chapitres/01-introduction.md
touch rapport/chapitres/02-conclusion.md
```

## 3. Création du script Node.js

Créer le fichier :

```text
rapport/concat-chapitres.js
```

## 4. Initialisation du package Node.js

Créer le fichier :

```text
rapport/package.json
```

## 5. Compilation automatique du rapport

```bash
cd rapport
node concat-chapitres.js
cd ..
```

## 6. Résultat de la compilation

Le script génère automatiquement le fichier :

```text
rapport/rapport-blog.md
```

Ce fichier contient le rapport consolidé à partir des chapitres Markdown.