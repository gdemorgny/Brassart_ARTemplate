# Brassart_ARTemplate

Le template fonctionne de la manière suivante :
- Le sublevel PreviewAR ne sert qu'à avoir de la lumière pour vous permettre de voir le contenu de votre level, il n'a pas d'autre utilité.
- Vous rien à mettre dans votre level de base ! Du moins pour l'instant.
- Vous avez un BP_ARSequence qui regroupera tout votre travail. Il se situe dans HandheldAR\Blueprints\Placeable.
- Si vous ouvrez le BP_ARSequence, vous verez un component appelé ARSequence. C'est une timeline interne au BP qui se lance dès que le BP apparait.
- Donc : L'appli se lance, Vous scannez, Vous choisissez où vous voulez voir apparaitre votre BP_ARSequence, Il apparait et la séquence ce lance automatiquement.
- J'ai fait une séquence avec un niagara systeme pour voir si tout marche correctement. Vous pouvez tester.
