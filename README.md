# Plugin aux fonctionnalites basiques

## Cadre et Objectifs

Ce plugin a été développé dans le cadre du cours "Programmation sous QGIS" dispensé au sein du Master TSI de Géodata Paris, en novembre 2026. Les objectifs étaient multiples :
 * Prendre en main les outils QGIS à disposition pour développer un plugin (PLugin Builder 3, Plugin Reloader).
 * Explorer les possibilités offertes par PyQGIS pour améliorer les fonctionnalités de QGIS, et manipuler des projets hors de l'interface.
 * Approfondir les connaissances de la suite QtCreator, en liant l'interface créée via QtDesigner et les fonctionnalités du plugin développée en python.

 ## Fonctionnalités du plugin

 Le plugin est basique et permet d'effectuer les opérations suivantes :

 * Sélection des couches de ponctuels sur le projet QGIS en cours
 * Affichage au clic des coordonnées du point sélectionné
 * Affichage de l'adresse de la BAN la plus proche du point cliqué
 * Affichage d'une zone tampon d'un rayon défini par l'utilisateur autour du point cliqué
 * Décompte du nombre d'objet dans la couche sélectionnée au sein de cette zone tampon
 
