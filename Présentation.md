### Bonjour ! 👋

Je m'appelle Victor Merly, étudiant passionné en BTS CIEL (Cybersécurité Informatique et Electrique). Mon parcours académique et mes projets sont axés sur la conception, l'industrialisation, la maintenance des systèmes électroniques, la cybersécurité et la conception de réseaux informatique.

#### Ce que je fais :
- **Conception Électronique** : Développement de circuits imprimés, schémas électroniques et prototypes.
- **Industrialisation** : Optimisation des processus de fabrication et intégration des systèmes électroniques dans des produits finis.
- **Maintenance** : Diagnostic et réparation des systèmes électroniques, mise en place de plans de maintenance préventive.

#### Mes Minis-projets :

- **Mini-projet 1** : Projet afficheur
Ce projet consiste à créer une interface graphique pour un afficheur destiné à notre lycée. L'interface est divisée en plusieurs sections :

Convocations et Informations : La première moitié de l'interface est dédiée aux convocations émises par la vie scolaire et aux informations diverses fournies par le secrétariat.

Menu du Self : Une autre section affiche le menu du self pour chaque semaine.
Informations Nationales : Un bandeau en bas de l'interface affiche les informations nationales récupérées sur BFM TV.

Météo Locale : Une partie de la page est consacrée aux relevés météorologiques de la semaine pour notre ville.

L'interface devait respecter un cahier des charges strict, notamment en utilisant les couleurs du logo du lycée. J'ai proposé cinq interfaces différentes, dont deux ont été sélectionnées par la classe. Ces deux versions ont ensuite été présentées au professeur référent du projet, qui en a choisi une pour la mise en œuvre finale.

- **Mini-projet 2** : Projet afficheur météo
Ce mini-projet consistait à récupérer des données météorologiques à l'aide de capteurs installés dans notre garage à vélos/motos. Nous avons développé des codes pour permettre aux capteurs de collecter les valeurs suivantes :

Humidité : Mesurée par un capteur d'humidité.

Précipitations : Mesurées par un pluviomètre.

Direction du Vent : Mesurée par une girouette.

Vitesse du Vent : Mesurée par un capteur de vitesse du vent.

Toutes ces informations étaient collectées par un microcontrôleur ESP32 connecté à notre réseau Wi-Fi privé. La borne Wi-Fi était reliée à notre base de données (PHP My Admin), où les données reçues étaient enregistrées dans les tables correspondantes. Les données météorologiques étaient ensuite affichées en temps réel sur un téléviseur.

- **Mini-projet 3** : Projet Video surveillance
Ce mini-projet visait à créer un réseau privé personnel. Sur ce réseau, nous avons connecté une caméra et une base de données (PHPMyAdmin). La caméra, ayant déjà servi pour un autre projet, a été réinitialisée et j'ai ressoudé les câbles qui avaient été retirés.

L'équipe en charge de la caméra a développé un programme permettant de capturer des images dès qu'un mouvement était détecté. Ces images étaient ensuite envoyées à la base de données et enregistrées dans les tables appropriées.

Pour permettre la communication entre la caméra et la base de données, nous avons créé un réseau Wi-Fi privé en utilisant un Raspberry Pi 3B+ avec l'ISO Pi-Rogue. Pi-Rogue est un système d'exploitation qui transforme le Raspberry Pi en routeur Wi-Fi. Une fois configuré, il devient un routeur sur le réseau souhaité.

J'ai défini un mot de passe privé, accessible uniquement par mon équipe et moi-même, afin de sécuriser l'accès au réseau. 

- **Mini-projet 4** : Projet Enceinte thermique 
Ce mini-projet a pour but de nous faire travailler avec un capteur de température et un chauffage dans une enceinte isolée. Pour commencer, nous avons dû prendre en main notre enceinte. Nous l'avons modélisée en 3D pour avoir un aperçu rapide des dimensions. Notre enceinte était en forme de cube.

Pour la partie chauffage, j'ai dû réaliser toute la partie électrique pour alimenter ce chauffage, le capteur et l'ESP32. J'ai récupéré une alimentation, j'ai coupé et soudé des câbles pour relier les composants (Arduino, capteur de température, chauffage) à cette alimentation, tout en vérifiant les conditions électriques pour ne pas tout court-circuiter.

Lorsque toute la partie électrique a bien été réalisée, nous nous sommes mis à la partie communication et enregistrement des données. Nous avons mis en place une base de données qui enregistre les données de température envoyées par le capteur de température. Ces données sont envoyées sur une page web que nous avons également créée. Sur cette page web, nous avons mis le relevé avec un graphique de la température en fonction du temps. Nous avons implémenté un bouton d'arrêt pour stopper le relevé de température.

Cette page web était aussi connectée à un réseau Wi-Fi, comme pour l'ESP32. Nous faisions des partages de connexion en 4G car la salle où nous travaillions ne comportait pas de réseau Wi-Fi privé. La page était enregistrée en local sur un ordinateur portable, aucun hébergement n'a été nécessaire.


#### Mes Projets :
- **Projet 1** : [Nom du Projet] - [Brève description du projet et des technologies utilisées]

#### Compétences :
- **Logiciels** : Kali-Linux, 
- **Langages de Programmation** : C, Python, etc.
- **Outils de Développement** : Oscilloscope, générateur de signaux, carte arduino, ESP32.

#### Objectifs :
- Approfondir mes connaissances en électronique et cybersécurité
- Collaborer sur des projets open-source et contribuer à la communauté.
- Développer des solutions innovantes et durables dans le domaine de l'électronique.

N'hésitez pas à explorer mes projets et à me contacter pour toute collaboration ou discussion !

---
