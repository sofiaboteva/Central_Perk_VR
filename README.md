# Reconstruction de "Central perk" en réalité virtuelle avec A-Frame

Ce projet est effectué dans le cadre du cours Réalité virtuelle et augmentée donné par Isaac Pante à l'Université de Lausanne au semestre de Printemps 2022.

Le but de ce projet était de reconstruire en réalité virtuelle "Central Perk", le fameux café de la série "Friends".

À cette fin, j'ai utilisé des modèles gltf (open source ou créés / modifiés à l'aide de Blender) pour en composer une scène en réalité virtuelle avec A-Frame.

## Inspiration

Pour imaginer la scène en réalité virtuelle, je me suis inspirée aussi bien des plans du café de la série, que d'autres modèles de "Central Perk" en 3D que j'ai trouvés sur Internet.

![centralperk](refs/centralperk.jpeg)
![centralperk](centralperk3d.png)
![centralperk](centralperk3d2.png)

## Modèles gltf

La première étape consistait à trouver des modèles gltf représentant les meubles et les objets de décor du café (pour cela j'ai utilisé sketchfab.com). Le nombre des modèles gltf open source est bien restreint, donc c'était souvent impossible de trouver un modèl identique au prototype réel.

C'est là où d'autres modèles en 3D de "Central Perk" m'étaient utiles. Beaucoup d'eux sont composés des objets qui, pris séparément, sont bien distincts de leurs prototypes. Mais ensemble ils parviennent à recréer le "look&feel général" de la scène originelle.

# Les sources des modèles gltf:

- Le bar https://sketchfab.com/3d-models/wooden-bar-f4f9231e73d64e3683d6ff19993d8fad
- Le canapé https://sketchfab.com/3d-models/scott-3-seater-sofa-burnt-orange-cotton-velvet-b3ac8e20f12e4c8fa3f7ded38aeb901c
- Le canapé bourgogne https://sketchfab.com/3d-models/antique-sofa-5384d703c1094899a45ae0a9a8dee909
- Le canapé gris https://sketchfab.com/3d-models/sofa-grey-fabric-7f8cca8fe9d8449684b1dfbb410af8c6
- Les chaises https://sketchfab.com/3d-models/modern-chair-7ede0d6a745d45e7beac044814899b7e
- La porte https://sketchfab.com/3d-models/diner-door-c7fae4880bfe49f897fa9860a4bbc67b
- Le tapis https://sketchfab.com/3d-models/fine-persian-esfahan-carpet-6f8f98d15a60439aa813785433c3cd4c
- Le fauteuil https://sketchfab.com/3d-models/old-armchair-3f202edab73e4ce886f8cf5c85810a1c
- Le porte-manteau https://sketchfab.com/3d-models/old-coat-rack-f7125e65dd004381aa3e9882ef74e963
- La table ronde https://sketchfab.com/3d-models/round-table-e51789f2d79d4fb0897ba39b3d55dba6
- La fenêtre https://sketchfab.com/3d-models/shop-window-6578e778970e4719b30411c7c56427f3
- Les lumières https://sketchfab.com/3d-models/stage-light-fresnel-3554154c724c4cf1b8db4ff26f65b54c
- La table https://sketchfab.com/3d-models/white-wooden-kitchen-table-f63ff45c124840709310932183c99b1a
- La chaise de bar https://sketchfab.com/3d-models/wooden-stool-low-poly-9b975361717b4da79b18480bcc4e6dc8
- Muffin https://sketchfab.com/3d-models/blueberry-muffin-e48f29f0714a4c70ac75a34cedf6b3bc
- Tasse https://sketchfab.com/3d-models/coffee-cup-992750b0df674378989fa915b0688ce1
- Tasse bleue https://sketchfab.com/3d-models/coffee-cup-with-plate-c3132a723f434ce2b94e2e563420ef7a
- Tasse marron https://sketchfab.com/3d-models/cup-of-cappuccino-04f2c34a3df94e58be97c2830e7e462a
- Plateau de muffins https://sketchfab.com/3d-models/muffins-a027d9df992d4fc38a08ae858f547cda

# Sources des images 2D (décor): 
- New York https://images.app.goo.gl/JKRjyR1Jzyi7h7E69
- Central Perk https://images.app.goo.gl/g54Vhbxgfdrb6xf28
- Friends https://images.app.goo.gl/yucwQXyXJHLW1pTy9
- Cappucino poster https://images.app.goo.gl/Tycxcidfx16aCNqf7
- Friends 2 https://images.app.goo.gl/PYUcoiZS8ZcsYaBY8

# Sources des textures: 
- Carreau https://www.textures.com/download/PBR0199/133238
- Brique https://www.textures.com/download/3DScans0739/140277
- Papier peint https://www.textures.com/download/WallpaperForties0077/19091
- Panneau https://www.textures.com/download/PBR0573/138820

## Blender

Comme c'était ma première expérience de l'utilisation de Blender, je ne pouvais pas créer d'objets complexes, mais j'ai appris à compléter certaines taches de base sur Blender, plus précisément:

- faire des modifications des modèles gltf importés – changer de couleur (par exemple, les tables rondes, le portemanteau), choisir un élément du modèle pour l'utiliser isolement (les chaises colorées)
- travailler avec les textures et créer de simples objets constitués de plusieurs textures (par exemple, les murs avec du papier peint)
- créer des modèles gltf à partir des images 2D (les tableaux)
- créer de simples modèles gltf (l'enseigne au néon représentant une tasse de café)

## A-Frame

La partie finale du projet consistait à organiser les modèles au sein d'une scène A-Frame. Cela comprenait notamment:

- importation des modèles gltf
- mise à l'échelle et positionnement des objets
- travail avec les textures (le mur de briques)
- travail avec la caméra et la lumière

![centralperk](readme.image.PNG)
