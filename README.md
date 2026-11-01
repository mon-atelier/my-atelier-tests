# My Atelier — tests et retours

My Atelier rapproche clients, garages, conseillers, techniciens et mécaniciens autour du suivi d'un véhicule et de son dossier.

Cet espace public accueille les retours des testeurs volontaires. Il ne contient pas le code de l'application. Le code est conservé dans un dépôt privé séparé.

## Participer aux tests

**[Essayer My Atelier sans inscription →](https://my-atelier-demo.vercel.app/demo)**

Choisissez **Client**, **Garage / propriétaire**, **Conseiller client** ou **Technicien / mécanicien**. Aucun compte à créer, aucune adresse e-mail et aucun mot de passe à saisir. Le bouton **Changer de rôle** permet de découvrir les différents points de vue sur le même dossier.

La démonstration utilise une base séparée avec des véhicules, dossiers, rendez-vous et messages fictifs. Les comptes sont partagés : les modifications sont visibles par les autres visiteurs. Ne saisissez aucune donnée personnelle. Les fichiers, e-mails, SMS, WhatsApp et modifications de compte sont désactivés ; certains essais sont donc limités. Les notifications internes à My Atelier restent consultables.

Le service réel https://re-one-lime.vercel.app est distinct de cet espace de démonstration.

1. Consultez le [guide de test](GUIDE-TEST.md).
2. Réalisez le parcours correspondant à votre rôle.
3. [Signalez un problème](https://github.com/mon-atelier/my-atelier-tests/issues/new?template=bug.yml) ou [proposez une amélioration](https://github.com/mon-atelier/my-atelier-tests/issues/new?template=suggestion.yml).

Les échanges GitHub sont publics. Ne publiez ni mot de passe, ni code de connexion, ni plaque, ni nom de client, ni document de dossier. Masquez ces éléments sur les captures.

## Parcours à examiner

- Client : accès à son espace, véhicule, demande de rendez-vous, réclamations, messages et historique.
- Garage et conseiller : demandes, création et suivi de dossier, planning, affectations et échanges.
- Technicien et mécanicien : dossiers affectés, compte rendu, preuves et messagerie interne.
- Tous : lisibilité sur téléphone et ordinateur, clarté des boutons et respect du rôle connecté.

Une fonctionnalité externe non activée pour votre groupe, notamment WhatsApp, ne doit pas être présentée comme disponible.

Les tests et les retours n'accordent aucun accès au dépôt privé ni aucun droit d'exploitation du logiciel.
