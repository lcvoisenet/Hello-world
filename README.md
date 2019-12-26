## Définissez votre nom:

git config --global user.name "Your Name"

## Maintenant configurez votre courrier électronique:

git config --global user.email "youremail@example.com"

## Tout d'abord, créez un nouveau dossier:
## Astuce: mkdir signifie make directory

mkdir hello-world

## Ensuite, entrez dans ce dossier:
## Astuce: cd signifie change directory

cd hello-world

## Enfin, dites à Git d'initialiser(démarrer le suivi) du dossier dans lequel vous êtes:

git init

## La dernière commande devrait renvoyer quelque chose commençant par "Initialized empty Git repository". Les autres commandes ne renvoie rien.
## Vous l'avez fait! Si vous voulez être sûr que c'est un dépôt Git, tapez git status et s'il ne vous retourne pas 'fatal: Not a git repository...' c'est que tout est parfait !

## Tout d'abord, vérifiez le statut:

git status

## Git devrait vous dire qu'un fichier a été ajouté.
## Puis ajouter le fichier que vous venez de créer afin qu'il devienne une partie des modifications que vous soumettez avec Git:

git add readme.txt

## Enfin, soumettez (commit) ces modifications à l'historique du dépôt avec un court (m) message décrivant les mises à jour.

git commit -m "Création du fichier readme"

## Dans le terminal, vous pouvez afficher les différences entre le fichier actuel et la dernière version soumise.
## Dites à Git de vous afficher le diff:

git diff

## Maintenant, avec ce que vous venez d'apprendre ci-dessus, soumettez ces derniers changements.