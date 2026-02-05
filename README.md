# Analyse Data Anime : Qualité vs Régularité

## Le Problème
On pense souvent que la qualité d'un anime se mesure uniquement à sa note finale.
J'ai voulu vérifier cela en analysant une base de données d'animes pour comparer la note Globale par rapport au nombre d'épisodes.

## Ce que j'ai appris
En croisant les données avec Python, j'ai réalisé que :
1. Les meilleures notes sont massivement concentrées sur les séries courtes (12-24 épisodes). C'est "facile" de faire un sans-faute sur une courte distance.
2. Dès qu'on dépasse les 300 épisodes, les points deviennent rares. Maintenir la qualité sur la durée est le vrai défi.

## Le Résultat
J'ai créé un ratio pour valoriser la régularité autant que la note.
D'après mon algorithme, le grand gagnant qui allie le mieux qualité et longueur est : **Vinland Saga**.

---
*Premier projet réalisé en Python dans le cadre de ma reprise d'études.*
