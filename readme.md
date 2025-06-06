# 📘 Cours Git – Commandes essentielles

Ce fichier contient un résumé des commandes Git les plus utiles pour suivre, versionner et collaborer sur un projet.

---

## 🧱 1. Initialiser un dépôt Git

```bash
git init
```
> Initialise un dépôt local dans le dossier courant (`.git`)

---

## 📄 2. Créer un fichier

```bash
echo "# Mon Projet" > README.md
```
> Crée un fichier avec un titre

---

## 🔍 3. Vérifier l'état du dépôt

```bash
git status
```
> Affiche les fichiers modifiés, non suivis ou prêts à être commités

---

## 📥 4. Ajouter des fichiers à l'index

```bash
git add nom_du_fichier
git add .
```
> Prépare les fichiers pour le commit (les ajoute à l’index)

---

## 💬 5. Commit : enregistrer une version

```bash
git commit -m "Message clair du commit"
```
> Enregistre les changements dans l’historique Git

---

## 🌐 6. Lier un dépôt distant

```bash
git remote add origin https://github.com/utilisateur/nom-repo.git
```
> Connecte ton dépôt local à GitHub ou GitLab

---

## 📤 7. Pousser vers GitHub

```bash
git push -u origin main
```
> Envoie le code vers la branche `main` du dépôt distant

---

## 🔁 8. Tirer les dernières modifications

```bash
git pull
```
> Récupère les modifications distantes

---

## 🌿 9. Branches

Créer une branche :
```bash
git branch nom-branche
```

Changer de branche :
```bash
git checkout nom-branche
```

Créer + changer :
```bash
git checkout -b nom-branche
```

Fusionner :
```bash
git checkout main
git merge nom-branche
```

---

## 🧹 10. Ignorer des fichiers

Créer un fichier `.gitignore` :
```
node_modules/
.env
*.log
```
> Empêche Git de suivre certains fichiers ou dossiers

---

## 🕓 11. Historique

```bash
git log
git log --oneline
```
> Voir l'historique des commits

---

## 🗑️ 12. Supprimer un fichier suivi

```bash
git rm fichier.txt
```

---

## 📂 Exemple complet

```bash
git init
echo "# Projet" > README.md
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/utilisateur/projet.git
git branch -M main
git push -u origin main
```

---

## 👨‍💻 Auteur

Nom Prénom – Formation Fullstack  
[GitHub](https://github.com/ton-utilisateur)

---

