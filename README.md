# NameBindingSecured

Projet maven sur le NameBinding de Java WS-RS

## API ##
Le seul usager dans la BD, c'est Paul avec 123456 comme mot de passe.

`GET /login/Paul/123456` Permet l'authentification de Paul.

`GET /logout/Paul` Permet la déconnexion de Paul.

`GET /account/Paul` Permet de voir son compte s'il est authentifié. 

## PostMan ##

Essayer les tests postman avec le mode 'preview' pour voir la reponse du body retourné.
