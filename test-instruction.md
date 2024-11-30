# Projet : Création utilisateur et mise à jour infos utilisateur

## Objectif
Créer une page web où l'utilisateur peut s'inscrire ou se connecter. Une fois connecté, les boutons *Log in* et *Sign up* disparaissent et sont remplacés par une icône de profil et un bouton *Logout*. Lorsqu'on clique sur l'icône de profil, l'utilisateur est redirigé vers une page où il peut compléter ses informations personnelles.

## Étapes

### 1. Création de la structure de base de la page
- Ajouter deux éléments dans le header de l'application :
  - *icone de profil utilisateur* : pour afficher la page du profil de l'utilisateur.
  - *Log out* : pour déconnecter l'utilisateur.

### 2. Formulaire de connexion (Log in)
- Créer un formulaire de connexion qui s'affiche lorsque l'utilisateur clique sur *Log in*. Le formulaire doit contenir :
  - Un champ *Email* (type : email).
  - Un champ *Mot de passe* (type : password).
  - Un bouton *Log in* pour soumettre.

### 3. Formulaire d'inscription (Sign up)
- Créer un formulaire d'inscription qui s'affiche lorsque l'utilisateur clique sur *Sign up*. Ce formulaire doit contenir :
  - Un champ *Email* (type : email).
  - Un champ *Mot de passe* (type : password).
  - Un champ *Confirmation de mot de passe* (type : password).
  - Un bouton *Sign up* pour soumettre.

### 4. Affichage conditionnel des formulaires
- Lorsque l'utilisateur clique sur *Log in*, le formulaire de connexion doit s'afficher et celui d'inscription doit disparaître.
- Lorsque l'utilisateur clique sur *Sign up*, le formulaire d'inscription doit s'afficher et celui de connexion doit disparaître.

### 5. Simulation de la connexion
- Après une inscription ou connexion réussie (simulation en JavaScript), les boutons *Log in* et *Sign up* dans le header doivent disparaître.
- Ils doivent être remplacés par une *icône de profil* et un bouton *Logout*.

### 6. Page de profil utilisateur
- Lorsque l'utilisateur clique sur l'icône de profil, il est redirigé vers une nouvelle page contenant un formulaire où il peut compléter ses informations personnelles. Ce formulaire doit inclure :
  - *Nom* : champ à compléter.
  - *Prénom* : champ à compléter.
  - *Date de naissance* : champ à compléter.
  - *Genre* : boutons radio (Homme, Femme).
  - *Email* : pré-rempli.
  - *Mot de passe* : pré-rempli.
  - *Adresse* : champ à compléter.
  - *Code postal* : champ à compléter.
  - *Ville* : champ à compléter.
  - *Pays* : champ à compléter.
  - *Texte biographique* : champ textarea pour une bio.

### 7. Validation des champs
- Ajouter des règles de validation pour chaque champ du formulaire :
  - *Email* : doit être une adresse email valide.
  - *Mot de passe* : doit contenir au moins 8 caractères.
  - *Nom* et *Prénom* : ne doivent pas être vides.
  - *Date de naissance* : doit être au format date valide.
  - *Adresse*, *Code postal*, *Ville* : ne doivent pas être vides.
  - *Genre* : un bouton radio doit être sélectionné.
  - *Texte biographique* : doit contenir maximum 120 caractères.

### 8. Gestion de la déconnexion (Log out)
- Lorsque l'utilisateur clique sur le bouton *Logout, il est redirigé vers la page d'accueil et les boutons **Log in* et *Sign up* doivent réapparaître dans le header.

## Bonus
- Ajouter des messages d'erreur personnalisés sous chaque champ en cas d'erreur de validation.
- Styliser les formulaires avec du CSS pour améliorer l'interface utilisateur.
- Veiller à respecter les principe d'[accessibilité](https://developer.mozilla.org/en-US/docs/Web/Accessibility).

---

Avec ces étapes, vous devriez être en mesure de créer une page complète avec un système d'inscription, de connexion et de gestion du profil utilisateur.
