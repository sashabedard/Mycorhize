# 🌿 Guide GitHub Desktop

### Pour collaborer sur un dépôt existant

(sans créer de branches ni de dépôts)

## 🛏️ Introduction

GitHub Desktop est une application qui permet de collaborer sur un projet GitHub sans utiliser la ligne de commande.Elle simplifie les actions principales :

Pull → récupérer les dernières modifications

Commit → sauvegarder vos changements localement

Push → envoyer vos changements sur GitHub

Merge / Resolve conflicts → fusionner ou corriger les versions différentes

🩴 1. Cloner le dépôt (une seule fois)

a) Ouvrir GitHub Desktop

Lancez l’application et connectez-vous à votre compte GitHub.

b) Cliquer sur

File → Clone Repository…

c) Sélectionner le dépôt du projet

Il apparaîtra dans l’onglet GitHub.com.Cliquez sur Clone.

💡 Cela crée une copie locale du projet sur votre ordinateur.

🔄 2. Pull — Mettre à jour votre copie avant de travailler

Avant de modifier un fichier, faites toujours un Pull pour être à jour.

Dans la barre supérieure :➡️ Cliquez sur “Fetch origin”, puis sur “Pull origin” si disponible.

🔸 Fetch = vérifier s’il y a des nouveautés sur GitHub🔸 Pull = télécharger ces nouveautés dans votre copie locale

⚠️ Faites-le chaque fois avant de commencer à travailler.

✏️ 3. Commit — Enregistrer vos changements localement

Quand vous modifiez ou ajoutez des fichiers dans le dossier du projet :

Revenez dans GitHub DesktopVous verrez la liste des fichiers modifiés dans la colonne de gauche.

Cochez les fichiers que vous voulez enregistrer.

En bas à gauche, écrivez :

Summary : phrase courte et claire

(Optionnel) Description plus longue en dessous

Exemples :

Ajout du schéma du rhizome

Correction du bug d’affichage de la canopée

Mise à jour du moodboard

Cliquez sur Commit to main.

💾 Vous venez de créer un commit local, une sauvegarde de vos changements sur votre machine.

☁️ 4. Push — Envoyer vos changements sur GitHub

Une fois votre commit créé, un bouton “Push origin” apparaît en haut.➡️ Cliquez dessus.

Cela envoie vos modifications sur GitHub pour que toute l’équipe les voie.

🧠 Astuce : attendez quelques secondes après un push pour que le dépôt en ligne se mette à jour.

🔁 5. Merge automatique (Pull avec changements)

Si quelqu’un d’autre a modifié les mêmes fichiers pendant que vous travailliez :

Quand vous cliquerez sur Pull origin, GitHub Desktop essaiera de fusionner (merge) automatiquement.

Si tout se passe bien, un message s’affiche :✅ This branch is up to date with origin/main.

⚠️ 6. Conflits (quand deux versions se contredisent)

Il peut arriver qu’un fichier ait été modifié en même temps par deux personnes.

Symptômes :

Le pull échoue.

Message rouge :“We found some conflicts that need to be resolved.”

Étapes à suivre :

GitHub Desktop vous indique le ou les fichiers en conflit.Cliquez sur “Open in Visual Studio Code” (ou l’éditeur par défaut).

Dans le fichier, vous verrez ceci :

<<<<<<< HEAD
Votre version locale
=======
Version sur GitHub
>>>>>>> main

Choisissez ce que vous voulez garder, supprimez les lignes inutiles et les marqueurs (<<<<<<<, =======, >>>>>>>).

Enregistrez le fichier.

Retournez dans GitHub Desktop :

Cochez le fichier résolu.

Écrivez un message de commit commeRésolution du conflit dans fichier.txt.

Cliquez sur Commit merge.

Enfin, cliquez sur Push origin.

📊 7. Vérifier l’historique

Vous pouvez voir toutes les modifications passées dans l’onglet History :

Nom de la personne

Message du commit

Fichiers modifiés

Très pratique pour comprendre l’évolution du projet.

🤌 Schéma récapitulatif

🚞️ Étapes de base :

1️⃣ Fetch / Pull origin  →  récupérer la dernière version
2️⃣ Modifier vos fichiers
3️⃣ Commit to main       →  sauvegarder localement
4️⃣ Push origin          →  envoyer sur GitHub

🔁 Répétez ce cycle chaque fois que vous travaillez sur le projet.

💡 Bonnes pratiques d’équipe

✅ Toujours Pull avant de commencer à travailler✅ Commit souvent avec des messages clairs✅ Push dès que possible pour éviter les conflits✅ Si vous voyez un conflit, respirez 😄, puis suivez les étapes ci-dessus✅ Ne supprimez pas de fichiers du projet sans en parler à l’équipe

🛠️ Résumé visuel (terminologie)

Terme

Action

Ce que ça fait

Pull

Récupérer

Met à jour votre dossier avec les dernières versions du projet

Commit

Sauvegarder localement

Enregistre vos modifications sur votre ordinateur

Push

Envoyer

Met à jour GitHub avec vos commits

Merge

Fusionner

Combine deux versions différentes d’un fichier

Conflict

Désaccord

Git vous demande de choisir entre deux versions
