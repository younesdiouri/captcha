creation Blog @antonbourtnik @younesdiouri
Les require pour installer le projet : 
-composer

1)utiliser la commande php composer.phar update
--> alors les dépendances seront installées
2) vérifier les parametres.yml , la base de données doit être créée 
3) generer les entités avec doctrine:generate:entities
4) test de la base avec doctrine:schema:update --dump-sql
5) faire un --force
6) ajout des catégories grace au doctrine fixture
7) EVERYTHING OP


Développé en PHP avec le Framework Symfony 3
