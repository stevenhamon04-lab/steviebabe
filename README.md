# DEAD ZOMBIE ARCADE

Jeu de survie arcade en vue du dessus, jouable dans un navigateur moderne sur PC et mobile. Aucun compte ni installation ne sont nécessaires.

## Lancer

Ouvrir `index.html` dans un navigateur connecté à Internet. Phaser 3.80.1 et les polices sont chargés depuis des CDN. Pour publier le jeu, déposer le dossier `outputs` sur un hébergement de site statique (par exemple GitHub Pages, Netlify ou un serveur web). HTTPS est recommandé pour iPhone et Android.

## Commandes

- **WASD** ou **ZQSD** : déplacement (les flèches fonctionnent aussi).
- **Souris** : viser ; maintenir le clic gauche pour tirer.
- **1 à 7** : choisir une arme ; clic droit pour passer à la suivante.
- **Espace** : impulsion EMP, avec un délai de recharge.
- **Mobile** : joystick gauche pour bouger, joystick droit pour viser et tirer, bouton EMP.

Le record, les crédits et la progression de la partie sont conservés localement dans le navigateur. Le jeu comprend sept armes, cinq variantes de zombies dessinées en 2D avec animations, un survivant détaillé, des traces au sol, un boss récurrent, des bonus, une arène à obstacles et cinq thèmes sélectionnables. Les effets audio sont générés dans le navigateur : tirs distincts par arme, impacts, grognements synthétiques, explosion, EMP, bonus et fond sonore. Le bouton « SON » permet de couper ou rétablir le son.

Chaque environnement a son propre éclairage et des éléments de décor : consoles de laboratoire, pierres tombales, gravats, caisses militaires ou machines d’usine.

## Transférer le jeu sur GitHub

1. Créer un dépôt sur [github.com/new](https://github.com/new) et choisir **Private** ou **Public**.
2. Décompresser `dead-zombie-arcade.zip` sur l’ordinateur.
3. Dans le dépôt, choisir **Add file → Upload files**, puis déposer `index.html` et `README.md` et valider avec **Commit changes**.

Pour obtenir une page jouable en ligne, activer ensuite **Settings → Pages** et sélectionner la branche principale comme source. GitHub Pages publiera alors `index.html`.

## Contenu

- `index.html` — jeu complet, interface et styles.

