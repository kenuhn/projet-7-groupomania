

# P6: GROOUPOMANIA

# Création d'un reseau social d'entreprise dans lequel on peut
- créer un compte le supprimer
- se connecter et se déconnecter
- importer une photo de profil ou la changer
- Poter des posts avec des médias images ou vidéos.
- suprimer son post 
- liker les posts d'autres utilisateurs 
- Créer un compte administrateur capable de modérer le réseau social 

![home_groupomania](https://user-images.githubusercontent.com/87643200/216177857-c53ed532-3d0a-4301-bae1-65e9fca41915.jpg)

# Pour la stack j'ai décidé d'utiliser:

pour le backend : 
- nodeJs et le framework express 
- l'orm prisma pour la base de donné relationnelle
pour le frontend : 
- html 5
- Sass/ scss
- React Js
- redux 


# Pour lancer le projet :

installer la bonne la version de node 17.2.0
avec le gestionnaire de version NVM
"nvm use 17.2.0"

Se rendre dans dossier backend et installer node et toute les dépendances :

"cd back-end/" && "npm i"


Ensuite, lancer le server: "nodemon server.js"

Ensuite lancer prisma avec "npx prisma studio" pour accéder à la base de donnés.

Enfin, pour lancer le Front, ouvrir un nouveau terminal et 
se rendre dans le dossier frontend:  "cd frontend/"

puis lancer react: "npm start"



