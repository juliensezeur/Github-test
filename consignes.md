# Activité: Utilisation de GitHub avec Visual Studio Code

## Objectif

Publier un fichier sur GitHub en utilisant Visual Studio Code.

## Modalités d'évaluation

Réponses aux questions d'introduction (à intégrer dans un fichier .txt et à ajouter au Repository)

Publication du fichier dans un Repository sur votre compte GitHub.

## Durée

4H

## Questions d'introduction à GitHub et Linux

Quelques questions pour découvrir l'outil GitHub :

1) Qu'est ce que Git ? Quelle différence avec GitHub ?
2) Qu'est ce qu'un Repository ?
3) Qu'est ce qu'un commit ? Un push ? Un pull ?
4) A quoi sert le fichier README.md dans un repository GitHub ?
5) Comment récupérer un repository GitHub en ligne de commande sur un invite de commande ?

Quelques questions sur les OS et plus particulièrement Linux :

1) Qu'est ce qu'un OS ? A quoi cela sert il ?
2) Quelles sont les 3 principales familles d'OS ?
3) Linux est-il un OS ou une famille d'OS ?
4) Donnez moi 4 OS á noyau Linux
5) Quelle est la particularité principale des OS Linux par rapport aux autres ?

## Étape 1: Création d'un compte GitHub

- Avez-vous déjà un compte GitHub? Si non, créez-en un sur [GitHub](https://github.com/).

## Étape 2: Installation de Visual Studio Code et de l'extension GitHub

- Dans un invite de commande, vérifiez que Git est installé avec la commande git --version (si il ne l'est pas --> [Git](https://git-scm.com/download/win), ou pour Linux : sudo apt install git )

- Dans ce même invite de commande, configurez votre compte avec les commandes suivantes (les "John Doe" sont à remplacer par vos noms d'utilisateur et mails configurés dans GitHub) : `git config --global user.name "John Doe"` et `git config --global user.email johndoe@example.com`.

- Avez-vous installé Visual Studio Code sur votre machine? Si non, téléchargez et installez-le depuis [Visual Studio Code](https://code.visualstudio.com/).

- Avez-vous installé l'extension `GitHub Pull Requests ans Issues` dans Visual Studio Code? Si non, installez-la à partir de l'onglet Extensions.

## Étape 3: Initialisation d'un repository local

1. Ouvrez Visual Studio Code.
2. Utilisez la commande `Ctrl + Shift + P` (ou `Cmd + Shift + P` sur Mac) pour ouvrir la palette de commandes.
3. Tapez "Git: Initialize Repository" et sélectionnez le dossier de votre site internet.

## Étape 4: Ajout des fichiers au suivi de version

1. Dans l'onglet Source Control (icône en forme de branche à gauche), vous verrez les fichiers non suivis. Cliquez sur le "+" à côté des fichiers pour les ajouter au suivi de version.
2. En bas, saisissez un message pour votre commit et appuyez sur la coche pour valider.

## Étape 5: Réalisation d'un premier commit

1. Toujours dans l'onglet Source Control, cliquez sur la coche pour valider vos changements. Cela crée votre premier commit.

## Étape 6: Création d'un repository sur GitHub

1. Allez sur [GitHub](https://github.com/) et connectez-vous à votre compte.
2. Cliquez sur le "+" en haut à droite de la page et sélectionnez "New repository".
3. Remplissez les informations du repository (nom, description, etc.) et cliquez sur "Create repository".

## Étape 7: Lier le repository local au repository GitHub

1. Dans Visual Studio Code, allez à l'onglet Source Control et cliquez sur les trois points (ellipsis).
2. Sélectionnez "Publish to GitHub".
3. Choisissez le repository que vous avez créé sur GitHub et cliquez sur "Publish Repository".

## Étape 8: Pousser les changements sur GitHub

À partir de maintenant, lorsque vous effectuez des changements dans votre code, Visual Studio Code vous permettra de pousser ces changements directement en utilisant les boutons d'interaction avec GitHub présents dans l'interface.
