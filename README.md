# Horloge non conventionnelle en direct

Un tableau de bord de voiture animé dont les aiguilles lisent l'heure réelle. Programmé en nodal dans TouchDesigner.

## Contexte

Projet réalisé dans le cadre du cours de Médias interactifs (6e session, Techniques d'intégration multimédia, Cégep Édouard-Montpetit).

Le mandat : concevoir une horloge hors norme, tout en restant capable de lire l'heure. Carte blanche sur le sujet, j'ai choisi les voitures.

## Mon rôle

Projet solo : idéation, design, préparation des visuels et programmation.

## Technologies

- TouchDesigner : programmation nodale, animation des aiguilles et de l'affichage
- Photoshop : détourage et préparation des éléments visuels

## Démarche

1. Idéation : choix du sujet et de la direction (tableau de bord animé)
2. Préparation du visuel : médias d'arrière-plan, aiguilles retirées sous Photoshop
3. Placement des items : aiguilles placées manuellement, points de pivot ajustés
4. Programmation nodale : animation des aiguilles et de la vitesse en km/h
5. Défi personnel : le retour de l'aiguille des secondes

## Défi principal

Problème : faire repartir l'aiguille des secondes au bon moment, sans saut brusque.
Solution : j'ai isolé 15 % du cycle de 60 secondes comme fenêtre de transition, pendant laquelle la rotation est inversée. L'aiguille repart de façon fluide.

## Limites connues

- L'heure affichée dépend de l'heure système de l'ordinateur
- Projet visuel : aucune version web

## Crédits

- Conception, design et programmation : Yoan Robitaille
- Images : 
- https://www.vecteezy.com/vector-art/28549353-car-dashboard-speedmeter-technology-design-modern-futuristic-on-boack-background-vector
- https://www.freepik.com/premium-vector/car-dashboard-arrows-set-measure-indicator-icon-speedometer-arrow-set-vector-graphic_26985225.htm
- https://www.vecteezy.com/vector-art/9797080-fuel-gauge-full-on-white-background-flat-style-fuel-indicator-sign-fuel-symbol

## Auteur

**Yoan Robitaille** · Dev média interactif / Dev web