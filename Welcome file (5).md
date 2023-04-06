## Examen écrit: Test et intégration continue
### Nom/Prénom
### Questions de cours

#### Expliquer l’intérêt de tester notre code et notre application [1 point]
```





```
#### Citer deux types de test différents que l'on peut retrouver dans un projet et détailler leur utilité. [2 points]
```





```
#### Définir et expliquer le principe du TDD [1 point]
```





```
#### Quel est l'utilité du package Babel en NodeJS? [1 point]
```





```
#### Définir le principe de couverture de code [1 point] 
```





```
#### Définir ce qu'est un Githook [1 point] 
```





```
#### Donner la forme ou un exemple du conventionnal commit de git [1 point]
```





```
#### A quoi sert un linter [1 point]
```





```
#### Citer au moins deux éléments qu'un linter peut vérifier/relever [1 point]
```





```
### Kata de développement

#### Problème pierre papier ciseaux [10 points]

Le jeu du pierre papier ciseaux fonctionne comme suit: chaque joueur choisit un signe et le révèle. Le signe le plus fort l'emporte et le gagnant marque un point. Si les deux joueurs utilisent la même forme c'est un match nul. Le jeu se déroulera en une manche gagnante. Vous possédez deux fichier: un fichier **game.js** et un fichier **game.test.js**.

Créer les test suivants dans le fichier game.test.js:
- on s'attend à recevoir 'Match nul'.
- on s'attend à recevoir 'Victoire J1' lorsqu'il choisit les ciseaux
- on s'attend à recevoir 'Victoire J1' lorsqu'il choisit la pierre
- on s'attend à recevoir 'Victoire J1' lorsqu'il choisit la feuille
- on s'attend à recevoir 'Victoire J2' peu importe son signe

*Pour les test la fonction de matcher à utililiser sera toBe().*

 Compléter si nécessaire le fichier game.js en fonction de vos test.
```javascript
/* game.test.js */
import {game} from './game.js'

describe('Game',()=>{




























})
```

```javascript
/* game.js */

// Prend les signes de chaque joueurs en paramètre et renvoie le résultat
export function game(p1,p2){


































}
```
