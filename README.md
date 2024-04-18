# Améliorez l'interface d'un site mobile avec des animations CSS

Ce projet a pour but de travailler sur l'intégration de la maquette du site de la start-up Ohmyfood!.

# Compétences visées

- Utilisation Sass
- Animations CSS
- Versionnage avec Git et GitHub

Les animations donneront vie à l'interface et rendront la navigation plus interactive et engageante.

L'utilisation d'un pré-processeur CSS tel que Sass sera essentielle pour étendre les fonctionnalités de base du CSS, et aider à écrire des styles plus organisés et maintenables.

Le versionnage du projet avec Git et GitHub permet de se familiariser avec des outils essentiels pour la gestion et la collaboration sur des projets de développement web.

# Caractéristiques techniques et fonctionnelles

## Identité graphique

Polices :

- Logo et titres : Shrikhand
- Texte : Roboto

Couleurs :

- Primaire : #9356DC
- Secondaire : #FF79DA
- Tertiaire : #99E2D0

## Planning

Date de livraison de la première version du site : sous 1 mois.

## Technologies

- Le développement doit se faire sans JavaScript.
- Les fichiers sources .scss ainsi que le code compilé CSS doivent être disponibles dans un ou plusieurs fichiers dédiés.
- Le site devra être réalisé en adoptant le Mobile First, c’est-à-dire qu’il faudra d’abord réaliser l'intégration de la maquette mobile, puis tablette, et enfin l'intégration du responsive vers le desktop.
- Aucun framework ne devra être utilisé (comme Bootstrap par exemple).
- Aucun code CSS ne doit être appliqué via un attribut style dans une balise HTML.
- Tout le code doit être versionné sur GitHub avec des commits réguliers pour suivre l’avancement et publier le site en ligne plus facilement.
- Le site devra être accessible sur GitHub une fois terminé.

## Compatibilité

- Les pages devront passer la validation W3C en HTML et CSS sans erreur.
- Le site doit être parfaitement compatible avec les dernières versions desktop de Chrome et Firefox.

## Livrables attendus

# Page d’accueil

- Affichage de la localisation des restaurants. À terme, il sera possible de choisir sa localisation pour trouver des restaurants proches d’un certain lieu.
- Une courte présentation de l’entreprise.
- Une section contenant les 4 menus sous forme de cartes. Au clic sur la carte, l’utilisateur est redirigé vers la page du menu.

# Pages de menu

- 4 pages contenant chacune le menu d’un restaurant.

# Footer

- Le footer est identique sur toutes les pages.
- Au clic sur “Contact”, un renvoi vers une adresse mail est effectué.

# Header

- Le header est présent sur toutes les pages.
- Sur la page d'accueil, il contient le logo du site.
- Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil.

# Effets graphiques et animations

Les effets accessibles au clic ou au survol sont visibles sur la maquette. Ils devront utiliser les animations ou transitions CSS, pas de JavaScript ni de librairie. Pour toutes les animations, afin de soigner le rendu du site, il est important que lorsque nous avons un effet au hover ou lors d’un clic, nous ayons l’effet inverse lorsque l’on quitte le survol.

# Boutons

- Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir. L’ombre portée devra également être plus visible.
- À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un bouton "J’aime" en forme de cœur est présent sur la maquette. Au clic, il devra se remplir progressivement. Pour cette première version, l’effet peut apparaître au survol sur desktop au lieu du clic.

# Page d’accueil

Quand l’application aura plus de menus, un “loader” sera nécessaire. Sur cette maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à 3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini, toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte graphique du site.

# Pages de menu

À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger décalage dans le temps. Ils pourront apparaître soit un par un, soit par groupe “Entrée”, “Plat” et “Dessert”.
Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec des points de suspension.

## Réalisation

Le projet a été réalisé en 3 semaines.

## Évaluation des compétences par Openclassrooms

1. Intégrer une maquette en mobile-first (Validé)

L'aspect visuel correspond à la maquette sur écran mobile et aucun framework (type Bootstrap) n'est utilisé pour ce projet. La maquette s’adapte sur mobile, tablette et desktop. Le site s’affiche sans perte d’information et sans barre de défilement horizontale sur les différentes tailles (smartphone, tablette, écran de portable, écran fixe (au moins jusqu’à une résolution “hd” (1920*1080)).

2. Mettre en œuvre des animations CSS (Validé)

Toutes les animations demandées sont présentes, le code CSS passe la validation W3C CSS et aucun code CSS n'est appliqué via un attribut style dans une balise HTML. Le code CSS est écrit dans plusieurs fichiers SCSS, bonne structuration.

3. Versionner son projet avec Git et Github (Validé)

Le code de l’application est hébergé sur GitHub. Le versionning de l’application est effectué régulièrement (45 Commit).

# Axes d'amélioration :

- Plus d'utilisation de fonctionnalités potentiel.

- Utilisation d'un normalizer plus optimisé pour éviter la répétition de code.

# Remarques :

- Temps de parole un peu trop long, présentation très propre avec une bonne élocution, réponses aux questions sont bonnes.

- SCSS bien appréhendé et compris dans l'ensemble (manque d'optimisation du code qui viendra avec l'expérience).

Félicitation continuez comme ça sur les prochains projets !
