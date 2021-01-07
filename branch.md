# Branches

Les branches permettent de travailler sur une fonctionnalité sans perturber l'historique de la version stable d'un projet (la *branche* `master`).

Pour créer une branche:
```sh
git branch ma-branche
```

Pour changer de branche:
```sh
git checkout ma-branche
```

Supprimer une branche:
```sh
git branch -d ma-branche
```
> Si la branche n'a pas été fusionnée, utiliser l'option `-D` à la place.
