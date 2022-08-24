# ohmyfood (OpenclassRooms)

Projet 3 de la formation "Développeur Web".

"ohmyfood" est une entreprise de commande de repas en ligne. Le concept permet aux utilisateurs de composer leur propre menu, de le commander et ainsi réduire leur temps d'attente dans les restaurants.

## Objectif:

- Intégrer une maquette en "mobile first".
- Dynamiser une page web avec des animations CSS.
- Utilisation du préprocesseur Sass.
- utilisation de git et github pour la gestion de versions.
- Utilisation de github-pages pour l'hébergement.

## Livrables attendus:

### Contenu des pages

#### Page d'accueil (1 page):

- Affichage de la localisation des restaurants. À terme il sera possible de choisir la localisation pour trouver des restaurants proches d'un certain lieu.
- Une courte présentation de l'entreprise.
- Une section contenant les 4 menus sous forme de cartes. Au clic sur la carte, l'utilisateur est redirigé vers la page menu du restaurant.

#### Pages de menu (4 pages):

- 4 pages contenant chacune le menu d'un restaurant.

#### Header:

- Le header doit etre présent sur toutes les pages.
- Sur la page d'accueil, il contient le logo du site.
- Sur les pages menu, il contient en plus un **bouton de retour** vers la page d'accueil.

#### Footer:

- Le footer est identique sur toutes les pages.
- Au clic sur **"Contact"**, un renvoi vers une adresse mail est éffectué.

### Effets graphiques et animations

Les effets accessibles au clic ou au survol sont visibles sur la maquette. Ils devront utiliser les animations ou transitions CSS, pas de JavaScript ni de librairie.

#### Boutons:

- Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir et l’ombre portée devra également être plus visible.
- À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, unbouton "J’aime" en forme de cœur est présent sur la maquette. Au clic, il devra se remplir progressivement. Pour cette première version, l’effet peut être apparaître au survol sur desktop au lieu du clic.

#### Page d'accueil:

- Quand l’application aura plus de menus, un **"loading spinner"** sera nécessaire. Sur cette maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à 3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et
  utiliser les animations CSS **(pas de librairie)**. Le design de ce loader n’est pas défini, toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte graphique du site.

#### Pages de menu

- À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe **"Entrée", "Plat" et "Dessert"**. Un exemple de l’effet attendu est fourni.
- Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol
  sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec des **points de suspension**. Un exemple de l’effet attendu est fourni.

## Mémo

1. Polices:

- Logo et titres: **Shrikhand**
- Textes: **Roboto**

2. Couleurs:

- Primaire: **#9356DC**
- Secondaire: **#FF79DA**
- Tertiaire: **#99E2D0**

3. Convention:

- Nommage des classes CSS avec **la méthode BEM**.

5. Validations:

- **Validations W3C HTML et CSS obligatoires** avec warning autorisés.
- Compatibilité avec les dernières versions de **Chrome, firefox, Safari**.

## Démo

Pour visualiser la démo en ligne, veuillez suivre ce lien: [ohmyfood](https://michelmb-dev.github.io/ohmyfood/)


