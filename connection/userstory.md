# Page de connection 

**Objectif :**

Permettre aux utilisateurs (apprenants et enseignants) de s'inscrire, de se connecter, de récupérer un mot de passe perdu...

**Questions au client :**

-> Inscriptions ouvertes ou fermées (via URL ou code d'invitation ?) ? 
-> Inscription séparée pour les deux types de profils (apprenants et enseignants) ?  
-> Connection séparée pour les deux types de profils (apprenants et enseignants) ?  
-> Quel mode de récupération du mot de passe ? (mail, téléphone, app mobile... etc)
-> Quels informations à demander durant l'inscription ?
-> Autres profils ? (parents par exemple)
-> Conidition générale d'utilisation, législation 

## En tant qu'utilisateur, je veux accèder au formulaire d'inscription

Etant donné que j'arrive sur la page de connection, je vois un formulaire de connection, deux boutons ("Se connecter" et "S'inscrire") et un lien "Mot de passe oublié ?"

Quand je clique sur le bouton "S'inscrire".

Alors j'arrive sur un second formulaire avec plusieus champs ("Identifiant", "Mot de passe", "Confirmer mot de passe", "e-mail", "captcha", accepter les CGU...).

## En tant que apprenant, je veux m'inscrire pour accéder au site

Etant donné que je suis sur le formulaire d'inscription qui contient plusieus champs ("Identifiant", "Mot de passe", "Confirmer mot de passe", "e-mail", "captcha", accepter les CGU...).

Quand je remplis correctement ces champs puis que j'appuie sur le bouton de confirmation.

Alors je vois sur mon écrans que mon inscription a bien été prise en compte, et je recois un mail me confirmant mon inscription sur le service.

## En tant qu'enseignant, je veux m'inscrire pour accéder au site

Etant donné que je suis sur le formulaire d'inscription qui contient plusieus champs ("Identifiant", "Mot de passe", "Confirmer mot de passe", "e-mail", "captcha", accepter les CGU...).

Quand je remplis correctement ces champs, que je coche la case "Je suis un enseignant" puis que j'appuie sur le bouton de confirmation.

Alors je vois sur mon écrans que ma demande d'inscription a bien été prise en compte, et je recevrais un mail me confirmant mon inscription sur le service dès qu'un administrateur l'aura validé.

## En tant que qu'utilisateur, je veux me connecter pour accéder au site

Etant donné que j'arrive sur la page de connection, je vois un formulaire de connection, deux boutons ("Se connecter" et "S'inscrire") et un lien "Mot de passe oublié ?"

Quand je remplis correctement les deux champs du formulaire ("identifiant" et "mot de passe")

Alors j'arrive sur la page principale de l'application, en étant connecté.

## En tant qu'utilisateur, je veux accèder au formulaire de récupération de mot de passe

Etant donné que j'arrive sur la page de connection, je vois un formulaire de connection, deux boutons ("Se connecter" et "S'inscrire") et un lien "Mot de passe oublié ?"

Quand je clique sur le lien "Mot de passe oublié ?"

Alors j'arrive sur un nouveau formulaire avec un champ pour rentrer son email et un bouton.

## En tant qu'utilisateur, je veux récuperer mon mot de passe pour me connecter

Etant donné que je suis sur le formulaire de récupération de mot de passe.

Quand je remplis correctement le champ email et que je clique sur le bouton de confirmation.

Alors je vois sur mon écrans que mon inscription a bien été prise en compte, et je recois un mail avec un lien pour modifier mon mot de passe.

## En tant qu'utilisateur, je clique sur le lien pour modifier mon mot de passe

Etant donné que j'ai reçu un mail avec un lien pour modifier mon mot de passe, que j'ai cliqué dessus et que je suis maintenant devant un formulaire avec deux champs ("Nouveau mot de passe", "Confirmer le mot de passe") et un bouton.

Quand je remplis correctement les champs et que je clique sur le bouton de confirmation.

Alors je vois sur mon écrans que mon changement de mot de passe a bien été pris en compte, et je suis de retour sur la page de connection.
