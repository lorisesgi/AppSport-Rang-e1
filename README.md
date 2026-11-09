# AppSport-Rang-e1
Projet de groupe (GIT)
# Rapport Projet GIT – Rangée 1
## 1. Création du dépôt

- Création du dépôt **AppSport-Rang-e1** sur GitHub.
- Ajout des membres du groupe par invitation mail ou pseudo GitHub.
- Création du fichier `README.md` pour présenter le projet.

## 2. Clonage du dépôt et création de la branche develop

Nous avons cloné le dépôt sur notre machine et créé la branche `develop`.

```bash
cd ~
git clone git@github.com:lorisesgi/AppSport-Rang-e1.git
cd AppSport-Rang-e1
git switch -c develop
git push -u origin develop
```

Ces commandes permettent de récupérer le projet en local, de créer une branche et de l'envoyer sur GitHub.

## 3. Création d'une branche pour la réservation

Avant de commencer, nous avons récupéré les dernières modifications.

```bash
git switch develop
git pull
git switch -c feat/reservation-cours develop
```

Nous avons créé une branche pour travailler sur la réservation sans modifier directement `develop`.

## 4. Création du fichier Markdown

```bash
echo "# Réservation d'un cours" > reservation.md
```

Cette commande permet de créer le fichier `reservation.md` avec un titre.

## 5. Ajout et enregistrement du fichier

```bash
git add reservation.md
git commit -m "feat: ajout de la page de réservation"
```

Nous avons ajouté le fichier puis enregistré les modifications avec un commit.

## 6. Envoi sur GitHub

```bash
git push -u origin feat/reservation-cours
```

Cette commande permet d'envoyer notre branche sur GitHub.

## 7. Vérification du dépôt

Nous avons vérifié sur GitHub que les fichiers étaient bien présents :

- `README.md`
- `accueil.md`
- `planning.md`
- `reservation.md`

## Conclusion

Ce projet nous a permis d'apprendre à utiliser Git et GitHub en groupe. Nous avons appris à cloner un dépôt, créer des branches, ajouter des fichiers, faire des commits et envoyer nos modifications sur GitHub.
