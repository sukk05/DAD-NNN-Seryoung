# Fiche Pédagogique

## Informations étudiant·e

- **Nom :** KIM

- **Prénom :** Seryoung



## Profil et connaissances

### Présentation personnelle

- **Objectif à court terme :** Dans ce cours, je souhaite relier un objet réel à un espace virtuel interactif, autour des petits secrets et plaintes du quotidien.
- **Objectif à long terme :** Pour mon diplôme (DNA), je veux continuer à explorer mon thème principal — « les espaces virtuels, et ce qu'on y cache ou abandonne » — à travers des installations interactives simples.

### Compétences

**CODE CRÉATIF**

**GIT ET VERSIONING**

**INTERACTIVITÉ ET RENDU TEMPS RÉEL**

**INSTALLATION ET MISE EN ESPACE**

**PRÉSENTATION ET ARGUMENTATION**



## Projets

### Projet 1

#### Sujet du projet

- **Titre du projet :** Tasse à souci
- **Description du projet (environ 150 mots) :**
    *Tasse à souci* est une installation interactive composée d'une tasse vide posée sur une table, équipée d'un petit micro caché, et d'un écran placé devant elle. Le projet part des petits stress du quotidien et de la pause-café comme moment pour les relâcher. Lorsque le visiteur murmure des secrets ou de petites plaintes dans la tasse physique, le micro capte sa voix en temps réel. Sur l'écran — qui montre la surface du café vue de dessus — les mots reconnus tombent et s'accumulent sous forme de fragments pointus, déformés et complètement illisibles. Ainsi, personne ne peut lire ce qui a été dit. Une fois la surface remplie, un tourbillon se forme comme si on remuait avec une cuillère : les fragments fondent doucement dans le café jusqu'à retrouver une surface calme.

#### Thématiques de recherche

- **Thématiques que vous souhaitez explorer :**
La visualisation de l'invisible (la voix) sous de nouvelles formes, et l'interaction entre un objet du quotidien et un écran.

- **Pourquoi cette thématique vous intéresse-t-elle ? (environ 100 mots) :**
Jusqu'ici, j'ai surtout travaillé sur des sujets assez grands, comme des problèmes de société. Pour ce cours, j'ai voulu réduire l'échelle et m'intéresser aux petits stress et aux légères plaintes qu'on a pendant une pause-café. J'avais envie de relier un objet ordinaire à un écran interactif pour créer un petit moment de détente au quotidien. Ce qui m'a aussi intéressée, c'est de rassembler ces soucis mais de les transformer en images illisibles : on peut ainsi exprimer ce qu'on ressent plus librement, sans gêne.

#### Outils et techniques

- **Outils que vous comptez utiliser (logiciels, langages de programmation, etc.) :**
- **Techniques spécifiques que vous souhaitez maîtriser ou expérimenter :** La capture sonore en temps réel et la reconnaissance vocale (TTS) reliée à l'affichage de texte dans Unity ; l'ajout d'effets physiques simples pour faire tomber et bouger les lettres ; et l'expérimentation de shaders en temps réel pour créer et ajuster l'effet de tourbillon du café.

#### Références artistiques

Golan Levin / Zachary Lieberman, Messa di Voce (2003) : Pour la manière dont la voix captée par un micro se transforme en temps réel en formes abstraites et en fragments visuels qui tombent et s'accumulent à l'écran.

Hiroshi Ishii / MIT Media Lab, musicBottles (1999) : Pour l'utilisation d'un contenant ordinaire (une bouteille, comme ici une tasse) comme interface physique intuitive à la place d'un clavier ou d'une souris.

Henri Michaux / Untitled (Alphabet) (1944) : Pour l'invention de signes graphiques illisibles qui ressemblent à une écriture secrète, permettant de garder une trace visuelle des paroles tout en cachant leur sens.

- **Argumentaire expliquant la pertinence de votre projet (environ 150 mots) :**
- **Références artistiques qui inspirent votre travail (livres, artistes, œuvres, etc.) :**



## Actions

### Présentation orale d'un sujet artistique ou design (documentation de recherche)

// Sujet choisi, membres du groupe, date de passage et lien vers votre présentation :

### Accrochage de rendu

// Décrivez ce que vous allez présenter et comment vous comptez le mettre en espace :

### Contribution au logiciel

// Décrivez votre participation à la conception de l'outil commun et votre réflexion sur le sens du logiciel :



## Planification

### Planning de travail

- Établissez un planning des étapes clés de votre projet :
  - **Étape 1 :** Définition du concept, mise en scène visuelle, storyboard et vidéo de simulation, exploration technique (reconnaissance vocale, choix du micro).
  - **Étape 2 :** 
  - **Étape 3 :** 



## Commentaires et questions

// Avez-vous des questions ou des préoccupations à propos du cours ou de vos projets ? :

## Journal de bord

Ajoutez une entrée à chaque jour de cours, la plus récente en haut.

### JJ/MM/AAAA

###### 27/11/2026
*   **Ce que j'ai fait :** Réalisation d'une nouvelle vidéo test avec un rendu plus proche d'un vrai café, suivie d'un échange individuel avec le prof pour comparer les essais. Le prof a trouvé que la version graphique était plus intéressante et faisait mieux passer le sens du projet, en mentionnant le style du *skeuomorphisme* (tout en gardant cette évocation du café pour l'affiner ensuite).
Nous avons aussi défini la direction technique : utiliser **Unity** et envisager un effet de **shader** généré en temps réel plutôt qu'une vidéo préenregistrée en arrière-plan, afin de pouvoir ajuster les couleurs et les formes. Enfin, mise au clair et ajout des références et pistes discutées.
*   **Problèmes rencontrés :** Une vidéo préenregistrée est peu flexible, mais créer un shader en temps réel demande des notions de mathématiques un peu complexes à coder soi-même. Il faut aussi éviter de vouloir réaliser tout de suite l'effet final trop complexe (avec les lettres qui se mélangent) et avancer par étapes.
*   **Prochaine étape :** Commencer le développement sur Unity par la base la plus simple : d'abord relier l'entrée vocale à l'affichage d'un texte à l'écran, puis ajouter de la physique aux lettres pour les faire bouger, et développer le projet progressivement.
*   **Captures / liens :**![vidéo test1](img/test1.png)
                          ![vidéo test2](img/test2.png)
                          ![vidéo test3](img/test3.png)

###### 25/11/2026
*   **Ce que j'ai fait :** Mise à jour de la `fiche_pedagogique.md` avec la rédaction de l'étape 1 du planning de travail et l'ajout de références artistiques.
Réalisation de deux versions de vidéo test pour l'écran en vue de la maquette vidéo. 
Réflexion pour simplifier la logique de code : au lieu de déformer les lettres en temps réel, préparer à l'avance 26 images PNG abstraites et illisibles (correspondant aux lettres de A à Z) pour que chaque lettre reconnue fasse tomber le symbole correspondant à l'écran.
*   **Problèmes rencontrés :** Après avoir réalisé les deux vidéos tests, j'hésite sur le rendu visuel : est-ce que l'image à l'écran doit avoir un aspect plus graphique ou ressembler davantage à une vraie boisson (café/liquide) ? Il reste aussi à vérifier par le tournage quel dispositif fonctionne le mieux (écran posé sur la table ou projection).
*   **Prochaine étape :** Tourner la maquette vidéo avec la vraie tasse et les vidéos tests pour comparer les différents rendus visuels.

*   **Captures / liens :**![Croquis du projet](img/251126.jpg)

##### 24/11/2026
- **Ce que j'ai fait :** Rédaction des parties « Présentation personnelle » et « Thématiques de recherche » dans la `fiche_pedagogique.md`, et recherche de références. Échange individuel avec le prof autour de l'installation et mise au clair du mot-clé du projet (passer de « surpris » à « souci »). Début du storyboard pour la maquette vidéo(fake it)
- **Problèmes rencontrés :** Pour fixer la composition de l'écran, il reste plusieurs choix à tester (noir et blanc ou couleurs du café, fragments de texte seuls ou avec des formes abstraites, écran ou vidéoprojection), ainsi que l'outil de reconnaissance vocale (speech-to-text). La maquette vidéo  va servir à tester ces options.
- **Prochaine étape :** Finir le storyboard, rédiger le planning de travail, explorer les outils techniques nécessaires (reconnaissance vocale, choix du micro, etc.) et préparer les visuels d'écran pour tourner la vidéo.
- **Captures / liens :** ![Croquis du projet](img/241126.jpg)

##### 23/11/2026
- **Ce que j'ai fait :** Création du dépôt GitHub public (`DAD-NNN-Seryoung`) et début de la `fiche_pedagogique.md` (rédaction de la description du projet). Courte présentation de l'idée, puis mise au clair du concept et recherche de références.
- **Problèmes rencontrés :** Première utilisation de GitHub Desktop et du Markdown (`.md`), donc j'ai mis un peu de temps à comprendre comment ranger les fichiers et faire des commits. Difficile aussi de développer le projet tout en restant dans ce que je peux coder moi-même. Je me demande encore si je dois vraiment définir un type de stress précis.
- **Prochaine étape :** Remplir les autres parties de la `fiche_pedagogique.md`. Partager à nouveau l'idée précisée avec le prof (reconnaissance vocale + effet de tourbillon dans le café) et lui demander des références.
- **Captures / liens :** [Dépôt GitHub](https://github.com/sukk05/DAD-NNN-Seryoung) ![Croquis du projet](img/231126.jpg)