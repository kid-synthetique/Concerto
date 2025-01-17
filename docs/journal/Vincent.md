# Journal de Vincent Lalancette

## Table des matières
- [Semaine 0 (25 au 29 janvier)](#Semaine-0-(25-au-29-janvier))
- [Semaine 1 (30 janvier au 5 février)](#Semaine-1-(30-janvier-au-5-février))
- [Semaine 2 (6 au 12 février)](#Semaine-2-(6-au-12-février))
- [Semaine 3 (13 au 19 février)](#Semaine-3-(13-au-19-février))
- [Semaine 4 (20 au 26 février)](#Semaine-4-(20-au-26-février))
- [Semaine 5 (6 au 12 mars)](#Semaine-5-(6-au-12-mars))
- [Semaine 6 (13 au 19 mars)](#Semaine-6-(13-au-19-mars))

---
## Semaine 0 (25 au 29 janvier)

### Résumé des réalisations effectuées
- J'ai inscrit le nom de l'étudiant #4 au mien

### Exemples d'image
![OSC communique avec Max](medias/journal_vincent_S0a.png)

### Est-ce que j'ai accompli l'ensemble des tâches et objectifs que je m'étais fixés pour cette semaine?	
- [ ] Complètement
- [ ] Assez
- [x] Peu
- [ ] Pas du tout

#### Décrivez pourquoi.
Pour le peu à faire, j'ai dû m'absenter et donc j'ai manqué une partie du travail à compléter en équipe, j'ai donc peu accompli sur peu.

#### S'il y a lieu, qu'allez-vous faire pour remédier à la situation?
Nous avons reporté notre rencontre en équipe.

### Mon projet s'est-il réalisé selon l’échéancier prévu?

- [ ] Complètement
- [x] Assez
- [ ] Un peu
- [ ] Pas tout à fait

#### S'il y a des écarts/délais, décrivez-les.
Nous avons reporté notre rencontre d'équipe au lendemain.

#### S'il y a lieu, qu'allez-vous faire pour remédier à la situation?
Nous allons nous présenter en équipe un jour plus tard.

### Défis pour la prochaine semaine
Il faudra savoir quelles nouvelles fonctionnalités il y aurait à intégrer idéalement, si elles sont réalisables, et comment nous allons les intégrer.

---
## Semaine 1 (30 janvier au 5 février)
### Résumé des réalisations effectuées
Je suis désormais capable d'enregistrer, charger, et jouer une séquence de notes selon leur valeur midi, la vélocité, la duration et le "pan", suivant le rythme selon le bpm, la signature temporelle et la longeur du loop.

### Image d'une réalisation dont tu es la ou le plus fier
![Max joue des notes selon une séquence](medias/journal_vincent_S1a.png)

### Est-ce que j'ai accompli l'ensemble des tâches et objectifs que je m'étais fixés pour cette semaine?

- [ ] Complètement
- [x] Assez
- [ ] Peu
- [ ] Pas du tout

#### Décrivez pourquoi.
J'ai complété le fonctionnement interne, mais un utilisateur ne pourrait toujours pas enregistrer ses propres séquences sans aller modifier plus profondément le patcher. 

#### S'il y a lieu, qu'allez-vous faire pour remédier à la situation?
Les données sur la séquence sont enregistrées sous une "liste de liste", comme un tableau.
Il faudra que j'échange les axes du tableau pour plus de petites liste au lieu de moins de grandes listes, ce qui rendrait la modification interne plus difficile et longue, mais la modification par l'utilisateur plus facile et rapide.

### Mon projet s'est-il réalisé selon l’échéancier prévu?

- [ ] Complètement
- [x] Assez
- [ ] Un peu
- [ ] Pas tout à fait

#### S'il y a des écarts, décrivez-les.


#### S'il y a lieu, qu'allez-vous faire pour remédier à la situation?
Il me manque peu à faire, mais je dois probablement revenir en arrière pour modifier certaines choses, ce qui me demandra plus de temps mais au moins j'aurai 

### Défis pour la prochaine semaine
Régler le problème concernant l'enregistrement des notes,
Combiner les patchers de sound vizualiser avec Jérémie

---
## Semaine 2 (6 au 12 février)
### Résumé des réalisations effectuées
Effectué le ménage du patcher sound visualizer de Jérémy
Ajouté 4 nouveaux instruments
Ajouté 4 nouvelles icones pour chaque instrument
Adapté le nouveau Sequencer au projet

### Image d'une réalisation dont tu es la ou le plus fier
![Max joue une séquence à 132 bpm sans problème](medias/journal_vincent_S2a.png)


### Est-ce que j'ai accompli l'ensemble des tâches et objectifs que je m'étais fixés pour cette semaine?

- [ ] Complètement
- [x] Assez
- [ ] Peu
- [ ] Pas du tout

#### Décrivez pourquoi.
L'objectif principal de cette semaine était de terminer le Sequencer, mais la tâche a été ralentie par plusieurs empêchements nécéssaires.
J'ai tout de même eu le temps de rapidement créer des fonctionalités prévues au produit final sans qu'elles empiètent sur la progression actuelle.

#### S'il y a lieu, qu'allez-vous faire pour remédier à la situation?
Je termine le fameux sequencer dans les jours qui suivent.

### Mon projet s'est-il réalisé selon l’échéancier prévu?

- [ ] Complètement
- [ ] Assez
- [x] Un peu
- [ ] Pas tout à fait

#### S'il y a des écarts, décrivez-les.
Le sequencer aurait pu être terminé la veille, mais ça aurait coûté un retard à la remise de la liste de matériel à remettre à Cédrick.

#### S'il y a lieu, qu'allez-vous faire pour remédier à la situation?
Je termine le fameux sequencer dans les jours qui suivent.

### Défis pour la prochaine semaine
Le sequencer doit être terminé, l'interface dans OSC doit être utilisable par le commun des mortels.
---
## Semaine 3 (13 au 19 février)
### Résumé des réalisations effectuées
Ménage de patchers, Sequencer version 1.0, implémentation d'icônes dans l'interface Open Stage Control

### Image d'une réalisation dont tu es la ou le plus fier
![La version 1.0 du Sequencer est terminée!](medias/journal_vincent_S3a.png)<br>
![icones dans Open Stage Control](medias/journal_vincent_S3b.gif)
![icones dans Open Stage Control](medias/journal_vincent_S3c.gif)

### Est-ce que j'ai accompli l'ensemble des tâches et objectifs que je m'étais fixés pour cette semaine?

- [ ] Complètement
- [x] Assez
- [ ] Peu
- [ ] Pas du tout

#### Décrivez pourquoi.
Le Sequencer v1.0 est complété, toutes les fonctions sont utilisables, mais uniquement par le développeur.

#### S'il y a lieu, qu'allez-vous faire pour remédier à la situation?
Il faut que je construise une interface sur OpStCo ou au minimum une interface dev sur Max

### Mon projet s'est-il réalisé selon l’échéancier prévu?

- [ ] Complètement
- [x] Assez
- [ ] Un peu
- [ ] Pas tout à fait

#### S'il y a des écarts, décrivez-les.
Le Sequencer n'est pas utilisable par l'UI OpStCo

#### S'il y a lieu, qu'allez-vous faire pour remédier à la situation?
C'est un problème qui devra attendre, il doit être construit et intégré avec le reste de l'interface.

### Défis pour la prochaine semaine
Il faut combiner le sequencer avec le patcher principal et lui donne une interface lisible et utilisable.  
---
## Semaine 4 (20 au 26 février)
### Résumé des réalisations effectuées
Ménage massif de patchers, intégration du Sequencer au patcher principal, interface dev temporaire du Sequencer, apprentissage de scripts sur Open Stage Control

### Image d'une réalisation dont tu es la ou le plus fier
Patcher Beat avant<br>
![Patcher Beat avant](medias/journal_vincent_S4a.png)<br>
Patcher Beat après<br>
![Patcher Beat après](medias/journal_vincent_S4b.png)<br>
Sous-Patcher Capsules avant<br>
![Sous-Patcher Capsules avant](medias/journal_vincent_S4c.png)<br>
Sous-Patcher Capsules après<br>
![Sous-Patcher Capsules après](medias/journal_vincent_S4d.png)<br>
Interface dev temporaire<br>
![Interface dev temporaire](medias/journal_vincent_S4e.png)<br>

### Est-ce que j'ai accompli l'ensemble des tâches et objectifs que je m'étais fixés pour cette semaine?

- [x] Complètement
- [ ] Assez
- [ ] Peu
- [ ] Pas du tout

#### Décrivez pourquoi.
J'ai entièrement fais le ménage et optimisation des patchers qui étaient déjà intégrés, construit et intégré une interface de base pour le Sequencer.

#### S'il y a lieu, qu'allez-vous faire pour remédier à la situation?

### Mon projet s'est-il réalisé selon l’échéancier prévu?

- [ ] Complètement
- [x] Assez
- [ ] Un peu
- [ ] Pas tout à fait

#### S'il y a des écarts, décrivez-les.
La séquence n'est toujours pas visible par l'utilisateur comme je l'imaginais, on peut voir la hauteur, la vélocité et la durée de chaque note, mais uniquement séparément. On doit pouvoir voir les notes avec l'opacité réfétant la vélocité et la longueur réflétant la durée.

#### S'il y a lieu, qu'allez-vous faire pour remédier à la situation?
J'ai commencé à étudier les solutions possible et les ressources nécessaires (temps et effort) associées.

### Défis pour la prochaine semaine
Trouver la solution idéale pour afficher à l'utilisateur sa séquence sur Open Stage Control
---
## Semaine de rattrapage (27 février au 5 mars)
### Résumé des réalisations effectuées
Recherche, recherche et recherche (comment intégrer du html/js dans open stage control et comment le mettre à jour)
Intégrations de strip DEL sur la scène (sans avoir testé)

J'ai aussi fait un des 3 robots sur notre scène en svg pour la bannière du site.

### Image d'une réalisation dont tu es la ou le plus fier
![Input file pour ouvrir les séquences plus simplement](medias/journal_vincent_SRa.png)

### Est-ce que j'ai accompli l'ensemble des tâches et objectifs que je m'étais fixés pour cette semaine?

- [ ] Complètement
- [ ] Assez
- [x] Peu
- [ ] Pas du tout

#### Décrivez pourquoi.
La recherche effectuée a peu porté ses fruits, je n'ai pas fait de progrès significatifs côté UI utilisateur.

#### S'il y a lieu, qu'allez-vous faire pour remédier à la situation?


### Mon projet s'est-il réalisé selon l’échéancier prévu?

- [ ] Complètement
- [ ] Assez
- [x] Un peu
- [ ] Pas tout à fait

#### S'il y a des écarts, décrivez-les.
Émile me demande maintenant de compléter l'UI utilisateur pour la semaine prochaine.

#### S'il y a lieu, qu'allez-vous faire pour remédier à la situation?
Je dois lâcher le visualisateur de sequencer pour l'instant et me concentrer sur les inputs que je connais et que je sais qui vont fonctionner

### Défis pour la prochaine semaine
Terminer l'UI fonctionnel sur l'interface OpStCo principale, trouver un moyen si possible d'afficher le sequencer.
---
## Semaine 5 (6 au 12 mars)
### Résumé des réalisations effectuées


### Image d'une réalisation dont tu es la ou le plus fier



### Est-ce que j'ai accompli l'ensemble des tâches et objectifs que je m'étais fixés pour cette semaine?

- [ ] Complètement
- [ ] Assez
- [ ] Peu
- [ ] Pas du tout

#### Décrivez pourquoi.
 

#### S'il y a lieu, qu'allez-vous faire pour remédier à la situation?


### Mon projet s'est-il réalisé selon l’échéancier prévu?

- [ ] Complètement
- [ ] Assez
- [ ] Un peu
- [ ] Pas tout à fait

#### S'il y a des écarts, décrivez-les.


#### S'il y a lieu, qu'allez-vous faire pour remédier à la situation?


### Défis pour la prochaine semaine

---
## Semaine 6 (13 au 19 mars)
### Résumé des réalisations effectuées


### Image d'une réalisation dont tu es la ou le plus fier



### Est-ce que j'ai accompli l'ensemble des tâches et objectifs que je m'étais fixés pour cette semaine?

- [ ] Complètement
- [ ] Assez
- [ ] Peu
- [ ] Pas du tout

#### Décrivez pourquoi.
 

#### S'il y a lieu, qu'allez-vous faire pour remédier à la situation?


### Mon projet s'est-il réalisé selon l’échéancier prévu?

- [ ] Complètement
- [ ] Assez
- [ ] Un peu
- [ ] Pas tout à fait

#### S'il y a des écarts, décrivez-les.


#### S'il y a lieu, qu'allez-vous faire pour remédier à la situation?


### Défis pour la prochaine semaine
