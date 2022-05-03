# Delta55
Le régulateur de plancher chauffant électrique Delta55 est ancien et n'est plus commercialisé.
Le mien a atteint un âge vénérable de 40 ans avant que son relais ne se mette à osciller lors des déclenchements par la base de temps.

La solution proposée par mon électricien était un renouvellement pour environ 1000€ vers un modèle électronique plus récent, et dont les fonctionnalités et réglages sont identiques. Aussi j'ai préféré réparer le matériel existant.

Je n'ai pas trouvé de schéma, pourtant il était courant à l'époque que celui-ci soit fourni dans le manuel de l'appareil. J'ai donc refait celui-ci et je vous le propose dans ce dépôt. Idéalement cela pourra aider certains d'entre vous à réparer leur appareil.

S'agissant d'une analyse d'un appareil existant, le schéma n'est pas organisé par bloc fonctionnel mais selon la position relative approximative de chaque composant sur les deux platines.


Attention il peut y avoir des erreurs dans les relevés des valeurs des résistances, notamment les résistances de précision dont les bandes étaient peu visibles sur mon exemplaire ; je ne les ai pas dessoudées pour vérifier. Il peut aussi y avoir d'autres erreurs ou oublis à d'autres endroits !


Pour les sondes de température, ce sont des thermistances CTN 1000 ohms à 25°C. Je les ai mesurées lors de l'intervention :
- 1250 ohms à ~20°C pour l'extérieure
- 1340 ohms à ~18°C pour la sonde sol (température de la pièce)


Sur mon exemplaire, il a suffi de changer les condensateurs dont 4 étaient HS. Les références indiquées sont sur le site de Conrad avec la durée de vie la plus longue d'après leur fabricant :
2x 220uF 25V radial => Nichicon UPW1V221MPD (déçu, mesurent 200 à 203uF au lieu des 220uF qu'ils devraient faire)
9x 10uF 40V radial => Europe ChemiCon EKY500ELL100ME11D

Voici les références chez le même revendeur pour d'autres composants que je n'ai pas eu besoin de changer :
1x 1000uF 16V axial => Vishay 2222 021 26102
1x relais ZETTLER AZ692-80-2 => ZETTLER AZ763-1C-12DE


Comme mot de la fin, cet appareil est assez simple et ne serait sans doute pas difficile à refaire autour d'un microcontrôleur. On pourrait même imaginer piloter le chauffage par accumulation selon la météo des jours à venir. Dommage qu'un matériel actuel à 650€TTC ne le propose même pas.
