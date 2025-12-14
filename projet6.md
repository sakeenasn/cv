Après avoir terminé l’affichage du système solaire et le mouvement des planètes, j’ai voulu rendre le projet plus interactif.
Pour ça j’ai ajouté deux nouveaux boutons sous les curseurs (zoom + vitesse), ajouté sous les sliders:
Bouton Son ON / OFF => Ce bouton sert à gérer les sons joués quand on clique sur une planète.
ON → les sons sont activés et peuvent se jouer normalement
OFF → tous les sons sont coupés et impossible d’en jouer tant que le bouton est désactivé
Si un son est en cours, il est stoppé immédiatement et appuyer sur la planète pour réécouter le son.

Bouton Pause / Reprendre le Système -> Ce bouton met tout le système solaire en pause , plus rien ne tourne.
Met en pause toutes les animations des planètes, de la Lune et du Soleil
Un deuxième clic relance tout là où ça s’est arrêté
Rien, ne recommence depuis le début : ça reprend exactement au même endroit
J’ai du modifier l’animation de la lune pour qu’elle soit comprise avec les autres planètes. Ces fonctions utilisent les méthodes .pause et .play d’Anime.js et gèrent correctement l’arrêt des fichiers audio en cours.
L’utilisateur peut observer une planète immobile, ou relancer tout le système d’un clic.
