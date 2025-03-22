# Fichier readme pour utiliser mon notebook Jupyter


### Ce que j'ai fait :

Programme d'analyse automatique de la capacité calorifique spécifique. Lorsque nous entrons les données de mesure (sous forme de fichier .csv), nous pouvons obtenir \( C(T) \) pour n'importe quelle mesure à la fin du Jupyter Notebook, ce processus est automatique.

Il y a deux choix : Calcul de la chaleur spécifique dans le livre rouge (méthode directe) et Méthode de l'égalité des aires.

### Insuffisances :

Pour la partie chauffage, j'ai utilisé une ligne droite pour l'ajustement. Théoriquement, on pourrait utiliser une fonction exponentielle, mais il y a peu de difference dans notre cas.

De plus, mes annotations sont en chinois.

La discussion sur la Méthode de l'égalité des aires n'est pas assez approfondie.

### Problèmes à résoudre :

La méthode de mesure manque de précision. Pour la méthode directe, la courbe BE descend très lentement, donc augmenter la limite supérieure de l'intégrale pose de gros problèmes (données non significatives).


