# Sacristie St Corentin - PWA

Application pour l'équipe de sacristie de la paroisse St Corentin.

## 🚀 Déploiement sur Vercel (le plus simple)

### Étape 1 : Préparer le projet
1. Créez un compte sur [GitHub](https://github.com) si vous n'en avez pas
2. Créez un nouveau repository (dépôt)
3. Uploadez tous les fichiers de ce dossier dans le repository

### Étape 2 : Déployer sur Vercel
1. Allez sur [vercel.com](https://vercel.com)
2. Cliquez sur "Sign Up" et connectez-vous avec GitHub
3. Cliquez sur "New Project"
4. Sélectionnez votre repository "sacristie-st-corentin"
5. Cliquez sur "Deploy"
6. Attendez 2-3 minutes... C'est en ligne ! 🎉

Vous recevrez une URL du type : `https://sacristie-st-corentin.vercel.app`

## 📱 Installer sur téléphone

### Sur iPhone (Safari)
1. Ouvrez l'URL dans Safari
2. Appuyez sur le bouton "Partager" (carré avec flèche)
3. Appuyez sur "Sur l'écran d'accueil"
4. Appuyez sur "Ajouter"

### Sur Android (Chrome)
1. Ouvrez l'URL dans Chrome
2. Appuyez sur les 3 points en haut à droite
3. Appuyez sur "Installer l'application" ou "Ajouter à l'écran d'accueil"

## 📁 Structure du projet

```
sacristie-pwa/
├── public/
│   ├── index.html          # Page HTML principale
│   ├── manifest.json       # Configuration PWA
│   ├── service-worker.js   # Pour le mode hors-ligne
│   └── icon-512.svg        # Icône de l'app
├── src/
│   ├── index.js            # Point d'entrée
│   └── App.js              # Application principale
├── package.json            # Dépendances
└── README.md               # Ce fichier
```

## 🔧 Développement local

Si vous voulez modifier l'application localement :

```bash
# Installer les dépendances
npm install

# Lancer en mode développement
npm start

# Créer la version de production
npm run build
```

## ✨ Fonctionnalités

- 📅 Calendrier des célébrations
- ✅ Checklists de préparation
- 👥 Gestion de l'équipe
- 📦 Inventaire du matériel
- 📝 Notes partagées
- 📖 Lectures du jour avec références

## 🎨 Personnalisation

Pour changer le nom de la paroisse, modifiez :
- `src/App.js` : ligne avec "Sacristie St Corentin"
- `public/manifest.json` : champs "name" et "short_name"
- `public/icon-512.svg` : texte "St Corentin"

## ❓ Besoin d'aide ?

L'application fonctionne même sans connexion internet une fois installée !
