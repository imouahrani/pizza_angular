# Angular Pizza  


![Pizza](Pizza.jpg)

## Installation

```shell
yarn
```

```shell
yarn setup
```

## Serveur de démarrage

```shell
yarn start
```

## Developpement

Vous êtes intéressé à changer de code?  [DEVELOPMENT.md](DEVELOPMENT.md)

[renovate-badge]: https://img.shields.io/badge/renovate-app-blue.svg
[renovate-app]: https://renovateapp.com/

## Tests

```shell
yarn cypress:open
```

Les tests sont situés dans le dossier [cypress/integration](cypress/integration) :

- [order-spec.js](cypress/integration/order-spec.js) est un test de fonction qui confirme que l’utilisateur peut entrer les détails de livraison, choisir les garnitures et passer une commande
- [dry-spec.js](cypress/integration/dry-spec.js) montre comment utiliser les commandes personnalisées définies dans [cyprès/support/index.js](cyprès/support/index.js) pour rendre le code de test sec et lisible
- [visual-spec.js](cypress/integration/visual-spec.js) 





