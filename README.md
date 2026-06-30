DevSetup

Bienvenue dans **DevSetup**, un projet de préparation de l'environnement de développement destiné aux débutants. Ce dépôt regroupe toutes les étapes nécessaires pour mettre en place un environnement de travail moderne avec **Visual Studio Code**, **Git** et **GitHub**.


Objectifs du projet

À travers ce projet, vous apprendrez à :

* Installer et configurer Visual Studio Code.
* Installer et configurer Git.
* Créer et gérer un dépôt GitHub.
* Utiliser les commandes Git essentielles.
* Organiser correctement un projet.
* Rédiger une documentation claire avec Markdown.



 Technologies utilisées

* Visual Studio Code
* Git
* GitHub
* Markdown

---

Structure du projet

text
DevSetup/
│
├── README.md
├── .gitignore
├── .editorconfig          (Bonus)
│
└── notes/
    ├── git.md
    ├── vscode.md
    └── github.md


Prérequis

Avant de commencer, assurez-vous d'avoir installé :

* Visual Studio Code
* Git
* Un compte GitHub

Installation

 1. Cloner le dépôt

```bash
git clone https://github.com/VOTRE_USERNAME/DevSetup.git
```

2. Accéder au dossier

```bash
cd DevSetup
```

Ouvrir le projet avec VS Code

```bash
code .
```

---

Commandes Git essentielles

Initialiser un dépôt

```bash
git init
```

Vérifier l'état du projet

```bash
git status
```

Ajouter les fichiers

```bash
git add .
```

ou

```bash
git add nomDuFichier
```

### Créer un commit

```bash
git commit -m "Premier commit"
```

### Connecter le dépôt à GitHub

```bash
git remote add origin https://github.com/VOTRE_USERNAME/DevSetup.git
```

### Envoyer les modifications

```bash
git push -u origin main
```

---

 Gestion des branches (Bonus)

Créer une branche de développement

```bash
git checkout -b dev
```

Basculer sur une branche

```bash
git checkout main
```

Fusionner la branche

```bash
git merge dev
```

---

Notes

Le dossier **notes/** contient plusieurs fichiers expliquant :

* Les commandes Git essentielles.
* La configuration de Visual Studio Code.
* Les bases de GitHub.

---
Bonus

Le projet peut également contenir :

* Un fichier `.editorconfig`
* La configuration de Nodemon
* Une branche `dev`
* Un historique Git propre avec plusieurs commits

---

Compétences acquises

À la fin de ce projet, vous serez capable de :

* Configurer un environnement de développement complet.
* Utiliser Git au quotidien.
* Héberger un projet sur GitHub.
* Gérer les versions de votre code.
* Documenter correctement un projet avec Markdown.

---

Licence

Ce projet est destiné à un usage éducatif et peut être librement utilisé pour apprendre Git, GitHub et Visual Studio Code.

---

Auteur

**Lys de Sharon**

Passionné(e) par le développement web, les technologies modernes et l'apprentissage continu.
N'hésitez pas à cloner ce dépôt, à expérimenter et à contribuer pour améliorer vos compétences !
