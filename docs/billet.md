# Titre

## Cartouche d'identification

 - Manifestation : CodeursEnSeine 2018
 - Lieu : KindArena - Rouen
 - Conférence : Découvrir Haskell et le mettre en prod
 - Horaire de la conférence : 14h30
 - Durée de la conférence : 50 minutes
 - Conférencier(s) :
   - Cécile Louvet https://twitter.com/celine_louvet
 - Audience : 30 personnes
 - Auteur du billet : Thibault Pawlak
 - Mots-clés : *Haskell* - *Stack* - *Back-End*
 - URL de l'illustration : ![Résumé d'une conférence Haskell](https://www.explainxkcd.com/wiki/images/8/8d/haskell.png)
 - Sources :
    -  https://docs.haskellstack.org/en/stable/README/,
    -  https://www.haskell.org/,
    - https://www.haskell.org/cabal/

## Support
 - Suppoort de la présentation : https://fr.slideshare.net/celine_louvet/haskell-en-prod-123943994
 - Nombre de diapos du support : 95
 - Plan du support :
    * Contexte et Besoin
    * Choix de la techno
    * C'est parti
    * De quoi j'ai besoin ?
    * Let's code
    * Et les tests ?
    * Et si on mettait en prod ?
    * Et les performances ?
    * Des tutos à conseiller
    * Les points durs
    * Les points positifs
    * Verdict ?

## Résumé
Céline Louvet fait partie d'une start-up nommée *Fairvioo*, qui a pour but la récolte d'avis client à but caritatif.
Pour leur architecture serveur, ils ont du faire face au choix de la technologie a utiliser.
Elle a fait le choix de Haskell pour plusieurs raisons : Découvrir un nouveau langage.C'est également un programme fonctionnel et cela s'adaptait parfaitement à l'architecture qu'ils souhaitaient installer.
Cependant, Haskell est un langage de programmation relativement complexe. Elle explique alors les spécificités du langage, notamment les alias de type et le mot-clé *let*.
Une fois le langage expliquée, celle-ci développe la stack de leur start-up, basée entièrement sur Haskell :
IDE : VSCode + Package Haskero
Packaging : Cabal ou Stack
CI : CircleCI
Déploiement : Clever Cloud
Framework de DB : postgresql-simple
Tests : HUnit
S'ensuit un approfondissement du modèle utilisé, ici CRUD mélé à une REST API.
En conclusion, les performances sont bonnes, même si celle-ci admet qu'ils n'ont pas benché leur code.
Elle liste ensuite les points négatifs puis positifs d'Haskell, ressortent notamment la complexité d'un coté et le compilateur très puissant de l'autre. Celle-ci conclut que, malgré les difficultés, il est difficile de revenir à un autre langage.

## Architecture et facteur qualité
...
