# Prépa SA Ville de Paris 2027

Application web installable (PWA) de préparation au concours interne de secrétaire administratif·ve d'administrations parisiennes, spécialité administration générale, session 2027.

Créé par G. FUMONT · FMT Collaboration.

- `index.html` : l'application.
- `free-data.js` : contenus en accès libre.
- `contenu.enc` : contenus de la version complète, chiffrés avec la clé du gestionnaire et publiés par lui dans Firestore (collection `sa_contenu`), lisibles pendant l'essai de 7 jours ou avec un abonnement actif.
- `admin.enc` : tableau des accès, réservé au gestionnaire.

Le projet Firebase est partagé avec l'application Prépa Attaché AAE 2027 ; les comptes, essais, abonnements et contenus de cette application sont dans des collections distinctes (`sa_comptes`, `sa_abonnes`, `sa_contenu`, `config/sa_paiement`, `users/{uid}/data/sa_progress`).
