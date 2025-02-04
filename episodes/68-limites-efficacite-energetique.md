---
episode_number: 68
title: Les limites à l'efficacité énergétique
people: Anne-Cécile Orgerie
description: "Anne-Cécile Orgerie est chargée de Recherche CNRS à l'IRISA de Rennes (Institut de Recherche en Informatique et Systèmes Aléatoires). Membre d'EcoInfo, ses principaux sujets de recherche sont l'efficacité énergétique dans les systèmes distribués, le cloud computing, les réseaux et les smart grids."
date: 2022-07-06
image: "/img/episodes/68-orgerie.jpg"
audio_link: https://soundcloud.com/techologie/68-limites-efficacite-energetique-anne-cecile-orgerie
audio_size_in_megabyte: 23
---

Cet épisode a été enregistré en public au Diapason, sur le campus de Beaulieu à Rennes. Nous remercions Philippe Quemerais, enseignant à l'ENSSAT d'avoir rendu cet épisode possible !

## Sommaire

* Son parcours
* Ce qui l'a amené à travailler sur le sujet des impacts environnementaux du numérique
* Les principaux travaux d'EcoInfo
* Les sujets sur lesquels elle travaille actuellement
* Comment mesure t-on l'impact des systèmes distribués, par exemple l'usage du Cloud ?
* Y a t-il encore des marges pour gagner en efficience ?
* Peut-on découpler l'explosion des usages des impacts environnementaux du numérique ?
* Son avis sur le fait que l'empreinte du cloud ne prend pas en compte le scope 3 en général ? Le scope 3 représentant les émissions indirectes « autres » que les émissions directes et les émissions indirectes liées à l’énergie .
* Quelle vision à long terme de l'impact sur le territoire ?
* Que penser du poids du choix énergétique dans l'équation ? 
* La France, qui n'utilise que moins de 20% d’énergie renouvelable, est-elle un terrain adapté pour la construction de nouveaux datacentres et quel modèle privilégier ?
* Les GAFAM sont-il alimentés 100% en énergies renouvelables ou c'est du greenwashing ?
* Quels sont les effet positifs du numérique sur l’environnement ?

## En savoir plus

[Page d'Anne-Cécile Orgerie sur le site de l'IRISA](http://people.irisa.fr/Anne-Cecile.Orgerie/)

## Transcription

### Extrait

Tout ça, alors qu'on doit réduire, qu'on doit faire la transition énergétique, la transition écologique, etc. J'irais même plus loin. Tout ça alors qu'on imagine que le numérique va nous aider à faire cette transition.

### Introduction

Nous sommes aujourd'hui, c'est une grande première, en public sur le campus de Beaulieu, à Rennes. c'est l'université de Rennes 1, plus particulièrement dans un lieu qui s'appelle le Diapason. Et nous avons l'honneur d'avoir Anne-Cécile Orgerie, chargée de recherche CNRS à l'IRISA de Rennes (Institut de Recherche en Informatique et Systèmes Aléatoires).

### Peux-tu nous parler de ton parcours ?

J'ai fait d'abord un master en informatique, à l’École Normale Supérieure de Lyon. Ensuite, j'ai poursuivi par une thèse sur la réduction de la consommation d'énergie des systèmes distribués. Puis, je suis parti un an en post-doctorat, à Melbourne, sur un sujet totalement différent, de traitement du signal. Et en 2012, j'ai obtenu mon poste à l'IRISA, ici, à Rennes, au laboratoire d'informatique.

### Qu'est-ce qui t'a amené à travailler sur le sujet des impacts environnementaux du numérique ?

J'ai commencé par un stage de master sur un sujet assez proche. Alors, à l'époque, on ne parlait pas encore trop de Cloud. Le terme est apparu un petit peu plus tard. Mais on parlait beaucoup des grilles de calcul. C'était les grosses infrastructures qui permettaient de faire des calculs scientifiques, par exemple, pour la météo, pour les simulations, les modélisations climatiques, entre autres. Mon sujet, c'était de m'intéresser à la consommation énergétique de ces grilles de calcul. C'était un premier sujet, un premier pas vers vers le sujet un peu plus général de l'impact environnemental du numérique. J'ai suivi ma thèse sur ce sujet-là pour essayer de réduire cette consommation, et on a appliqué ça à notre propre infrastructure de recherche expérimentale, qui s'appelle Grid'5000, qui est distribuée partout en France. C'est une infrastructure pour la recherche en informatique dans les systèmes distribués, donc ces grands systèmes, qui calcule des choses avec beaucoup d'ordinateurs en commun et que, par exemple, utilisent Facebook, Google, etc. Ces infrastructures très distribuées, puisqu'il y a plusieurs centres de calcul partout dans le monde et qui mettent en commun des puissances de calcul, du stockage pour fournir des services aux utilisateurs. Notre plateforme Grid'5000 est une plateforme de recherche sur laquelle on peut jouer, entre guillemets, des usages de cloud. Ma thèse portait sur essayer de réduire la consommation et au moins déjà la mesurer, ce qui, à l'époque, était une première.

### Tu fais également partie du groupement de services EcoInfo. Tu en es même actuellement directrice. On a reçu dans ce podcast une autre membre de EcoInfo, Françoise Berthoud, il y a quelques mois. Peux-tu nous en parler et nous présenter quels sont les principaux projets ?

EcoInfo, c'est un groupement de services du CNRS qui regroupe des personnels de tout l'enseignement supérieur et la recherche, à la fois des ingénieurs, des enseignants-chercheurs, des chercheuses, c'est pluridisciplinaire. On est distribué un peu partout en France. On s'attaque aux impacts environnementaux du numérique, mais avec un aspect pluridisciplinaire avec évidemment des informaticiens, des informaticiennes, des géologues, des philosophes, des sociologues, avec des perspectives assez variées, des points de vue aussi variés pour étudier ces impacts environnementaux et sociétaux du numérique. On a trois missions principales. La première, c'est de fournir des services pour l'enseignement supérieur et la recherche. Par exemple, on est acteur dans les marchés publics pour essayer d'allonger la durée de vie des équipements, notamment les durées de garantie, pour essayer de favoriser des écolabels à l'achat des équipements. On fournit aussi des outils pour calculer le bilan carbone d'une unité sur la partie numérique.

On a une partie aussi sur des actions de médiation scientifique, à destination principalement de l'enseignement supérieur, la recherche, puisqu'il y a encore assez peu de formations là-dessus, dont des formations, des articles de vulgarisation qui sont sur notre site web, notamment des guides de bonnes pratiques, tels que celui avec la Dinum, par exemple, des interventions dans des formations universitaires.

On a aussi un troisième aspect sur des projets de construction de connaissances, puisque c'est un sujet qui est quand même assez nouveau. Il y a plein de méthodologies qui n'existent pas encore et qu'on essaye de développer au fur et à mesure et qu'on essaye de rendre disponible. On fait des études bibliographiques, par exemple, sur les impacts environnementaux de la 5G, des campagnes expérimentales de mesure avec notre fournisseur d'accès à internet universitaire, qui est Renater, par exemple. Et puis des recherches prospectives, des expertises, etc. Donc un ensemble de services très variés, tout ça pour réduire les impacts négatifs du numérique.

### Et en dehors d'EcoInfo, quels sont les sujets sur lesquels tu travailles actuellement ?

Alors plusieurs sujets, comme je le disais, principalement sur les systèmes distribués, donc ces grandes infrastructures de l'internet qui vont des centres de calcul jusqu'aux réseaux de communication, la 5G, ou les réseaux d'accès filaires notamment. Donc vraiment une étude sur un impact de bout en bout. C'est la caractérisation, l'originalité de mes recherches.

Alors, pour être un peu plus concrètement, par exemple, j'ai des travaux sur la modélisation et la simulation de la consommation de l'internet des objets. Donc, si on prend un objet qui émet des données, comme dans l'internet des objets, par exemple un capteur, une caméra, quel est l'impact qu'il a sur l'utilisation du cloud, puisqu'il va envoyer des données et donc va avoir une empreinte numérique dans le cloud, sur les réseaux de communication, et puis combien ça consomme tout ça. Finalement, de bout en bout.

Il y a aussi des sujets sur réduire la consommation énergétique de l'internet sans fil à la maison. C'est un projet qui vient de commencer, pour réduire, par exemple, la consommation des box internet, puisque c'est l'utilisateur, finalement, qui paye cette facture.

Aussi des sujets sur l'alimentation des centres de calcul notamment avec des énergies renouvelables. Est-ce qu'il est possible de les alimenter uniquement avec des énergies renouvelables, à quel coût, puisqu'elles sont souvent intermittentes. Et puis l'optimisation de la consommation énergétique plus globale des infrastructures de cloud.

Et aussi sur une partie un peu plus récente du réseau de pilotage des Smart Grid. Pour aller un peu plus vers à quoi sert l'informatique, à quoi il peut servir dans les autres secteurs, pour optimiser l'énergie notamment.

### Comment mesure-t-on l'impact des systèmes distribués, par exemple l'usage du cloud. C'est un vrai sujet soumis à débat. Chacun arrive avec sa méthode. Les GAFAM ont leurs méthodes...

Oui, tout à fait, on trouve des chiffres originaux dans la littérature, et puis souvent très variés, avec des ordres de grandeur qui peuvent faire des grands écarts. Ce n'est pas un sujet simple très clairement. Mesurer des impacts c'est multifactorielles, c'est multisectorielles, c'est assez compliqué. Il y a plusieurs méthodes. Une des méthodes sur laquelle je travaille, c'est de partir de l'objet, voir ce qu'il génère comme données dans le cloud et mesurer la consommation de chacune des parties et essayer d'ajouter ça.

On peut partir sur une méthode complètement différente et prendre la consommation globale de ces infrastructures, puis diviser par le nombre d'objets. Et on n'obtient pas les mêmes résultats.

Il y a plusieurs méthodes, ce qui explique aussi qu'il y ait plusieurs résultats. Mais si on prend l'exemple d'une visioconférence. Elle utilise beaucoup de serveurs. Donc, il y a un serveur qui va faire passer la vidéo, plusieurs souvent. Un qui va faire passer la voix, plusieurs aussi. Si on partage les documents, ça va être encore plusieurs serveurs. Et puis on a utilisé un autre serveur avant, au début, pour l'authentification. Donc, il y a vraiment pour un service donné qui paraît simple, une multitude de ressources qui sont utilisées, qui ne sont pas au même endroit, qui peuvent être dans des data centres différents, et donc mesurer c'est assez compliqué et puis ça dépend des questions qu'on se pose pour adopter la bonne méthode finalement.

### C'est avec Renater, peut-être, vous avez fait une étude sur la consommation du réseau ? Et aussi des études sur le calcul d'une heure de calcul dans le domaine de la recherche, comment on obtient ces chiffre ? 

Effectivement, on a fait plusieurs études avec Renater dans le cadre d'EcoInfo, auxquelles je n'ai pas forcément participé à toutes, mais voilà, juste pour repréciser. Avec Renater, on va regarder combien ça coûte de transporter des octets d'un point à un autre sur le réseau. Et puis combien ça coûte la visioconférence aussi, combien ça coûte de transférer des données.

Et dans le cadre d'une autre étude qui a été faite au Gricad, à Grenoble, un centre de calcul universitaire, qui est en fait pour des calculs scientifiques très variés, ils ont calculé combien, quel est l'impact en termes d'empreinte carbone d'une heure de calcul sur un cœur de cette plateforme. Et donc là on a des résultats très intéressants. Cette étude est disponible sur le site d'EcoInfo et vous pouvez trouver toutes les données. Donc l'idée, c'est de regarder une heure d'utilisation d'un cœur physique, et il y a à peu près quarante serveurs sur la plateforme. Et cela inclut la fabrication des serveurs, de tous les équipements, donc le cycle de vie. Ça n'inclut pas le recyclage, parce qu'on a très peu de données là-dessus, puis c'est encore assez peu, assez peu fait finalement, on recycle assez peu ces équipements encore. Cela inclut aussi, par exemple, le coût des personnels, c'est-à-dire qu'il y a des personnels qui sont affectés à cette plateforme pour la maintenance. Cela inclut notamment leurs trajets domicile / travail. Donc voilà, c'est quelque chose d'assez large.

### Ce qu'ils mangent à la cantine ?

Effectivement, il y a toute une partie sur comment ils se nourrissent, comment ils viennent au travail, s'ils font du télétravail, quels équipements ils ont, puisque ça, ça fait pas partie de la plateforme, mais ils ont des ordinateurs, des téléphones, des écrans, etc. L'étude essaye d'être exhaustive autant que possible pour aller sur des scopes un petit peu plus larges que ce qu'on a habituellement dans la littérature. Et c'est pas simple. C'est-à-dire que ce genre d'études a été assez complexe à mener. On essaye de le reproduire sur d'autres plateformes, mais c'est vraiment pas simple.

Alors, parlons un peu des résultats. Comment ils ont fait ? Ils ont pris le total de toutes les consommations que je viens de lister là, notamment les personnels, puis ils ont divisé par le nombre d'heures d'utilisation par cœur de la plateforme. Donc, ils ont fait ce genre d'approche. Et donc on arrive à 3,97 grammes équivalent CO2 par heure - cœur  uniquement pour la partie serveur, en considérant la fabrication et l'usage. On est à peu près à 40% pour la phase de fabrication, sur ces 3,97 g, en sachant que les serveurs, ils les font durer sept ans, ce qui est déjà plus que la moyenne nationale. La part de fabrication est vraiment très importante dans cette équation, et ne pas la prendre en compte, c'est se priver de 40% des impacts dans ce cas-là.

Si on regarde globalement, 3,97 g, c'est juste pour les serveurs. Globalement, c'est estimé à 4,68 g équivalent CO2 pour une heure - cœur au total, en incluant les coûts de personnel. Ces coûts de personnel représentent 15% quand même de la facture totale : venir au travail, leurs équipements propres... Tous les détails sont dans l'étude sur le site.

### Dans l'informatique, dans le calcul, etc., est-ce que il y a encore des marges de manœuvre pour gagner en efficience ou est-ce qu'on atteint un peu les limites physiques ?

Alors déjà, on a fait beaucoup de progrès quand on imagine les premiers ordinateurs qui prenaient un hangar entier et qui consommaient quand même pas mal. Juste pour la puissance de notre téléphone actuel, on a fait beaucoup de progrès. Si on regarde, par exemple, l'évolution des microprocesseurs depuis les années 1970, les progrès qu'on a fait, d'abord, ça a été d'augmenter la fréquence de l'horloge des processeurs, c'est-à-dire le nombre d'opérations finalement qu'on est capable d'exécuter en une seconde. Cela a été une première amélioration de l'efficacité puisque, en augmentant la fréquence d'horloge, sans trop augmenter la consommation énergétique, on arrivait à faire plus de calculs. Sauf qu'on s'est rendu compte qu'il y avait des problèmes de dissipation thermique en augmentant la fréquence d'horloge, et donc on est arrivé à un palier. On ne pouvait pas aller beaucoup plus loin en étant beaucoup plus efficace. Depuis 2006, on a atteint ce palier.

On a essayé plutôt d'augmenter le nombre de cœurs de processeur. Cela veut dire qu'on a fait des processeurs multi cœurs qui peuvent faire plusieurs calculs en parallèle, plusieurs opérations à chaque cycle d'horloge. Et donc, ça, ça améliore encore l'efficacité puisqu'on mutualise une partie de ses processeurs. Et on a aussi augmenté la finesse de gravure des puces gravées, des puces de plus en plus petites. On est alors de l'ordre de quelques nanomètres. Actuellement, on sait faire des des transistors à 2 ou 3 nanomètres, suivant les fabricants. Ce qui est vraiment très petit quand on y pense. Cela permet d'avoir plus de puces sur la même surface, et donc une augmentation de la densité. Sauf que, là encore, on attend des limites thermodynamiques de dissipation de chaleur. Cette augmentation, elle pose des problèmes physiques qu'on va pas pouvoir résoudre, qui sont, qui sont des limites dures. On atteint depuis une dizaine d'années ce qu'on appelle le "dark silicone" c'est-à-dire le fait que dans nos ordinateurs, on a plus de processeurs, plus de cœurs que ce qu'on peut allumer à un instant donné pour des problèmes de dissipation thermique.

Alors, pourquoi on en met plus quand même ? Parce que, si nos calculs s'exécutent et puis change de processeur, change de cœur au fur et à mesure, on arrive à les refroidir comme ça, mais ça fait quand même une grosse dissipation, en gros, un gros gaspillage à la fabrication, juste pour gagner pas beaucoup finalement. Donc, on atteint des efficiences de plus en plus limitées, de plus en plus plafonnés et qui nous poussent de plus en plus vers les limites de la thermodynamique.

Ce qu'on imagine, c'est que l'efficience, maintenant, va plutôt venir soit d'une rupture technologique majeure, mais on ne l'a pas encore trouvé. Donc, ça paraît un peu "science-fiction". Soit de compromis un petit peu plus compliqué à trouver avec la qualité de service, c'est-à-dire qu'on s'est habitué à un internet qui est disponible tout le temps 24h/24, qui est très performant tout le temps, sauf que si, par exemple, la disponibilité, de l'électricité, elle, n'est pas aussi garantie que ça, peut-être que notre internet, on pourrait supposer qu'il soit moins performant à certains moments, quand il y a moins d'énergie, pour privilégier d'autres secteurs, par exemple la santé.

Ce sont des compromis qu'on va pouvoir trouver aussi sur cette efficience, pour essayer de limiter les pics de consommation qui dimensionne ses infrastructures. Donc je pense que, oui, on peut encore gagner en efficience, mais vraiment pas beaucoup. Notamment en réduisant les sources de gaspillage, la redondance, etc. Mais c'est des gains potentiels, qui ne sont pas infinies de toute façon, puisqu'il a des limites physiques, ne serait-ce que planétaire, et ils sont de plus en plus difficiles à atteindre. C'est comme quand on extrait des ressources et qu'il en reste de moins en moins. C'est de plus en plus difficiles à atteindre et de plus en plus coûteux en énergie. Et puis, surtout, l'explosion des volumes de données et des équipements informatiques ne va pas permettre de gagner sur tous les tableaux.

### Il y a des débats sans fin, notamment sur les réseaux sociaux, sur le numérique, ça va, l'impact est stable, etc. Mais est-ce que vraiment on peut découpler l'explosion des usages des impacts environnementaux du numérique ?

Alors, c'est compliqué. Les usages, effectivement, sont de plus en plus nombreux. Il y a des usages qu'on n'imaginait pas il y a dix ans, qui sont actuellement courant. Il y a des secteurs de l'industrie qui sont de plus en plus numérisés, informatisés, notamment l'énergie, l'agriculture, le transport et puis même le secteur du climat. Finalement, les modèles climatiques qu'on a réussi à produire, qui sont de plus en plus fins, de plus en plus fiables, c'est aussi grâce à des outils numériques, des simulations, des modélisations multi échelles qui sont complexes et gourmands en calculs. Et puis, certains usages c'est pour optimiser des choses, par exemple dans le transport. L'usage du numérique, c'est pour optimiser et réduire la consommation du transport.

C'est assez compliqué de dire quels sont les bons usages et les mauvais usages. Et puis, qui pourrait dire ça ? Par contre, ce qu'on voit effectivement, c'est que les impacts environnementaux, ils sont quand même de plus en plus forts. La consommation énergétique, elle, augmente. La consommation de matières premières augmente aussi, puisqu'on recycle en plus très peu les équipements, encore actuellement.

Et qu'on a besoin d'équipements de plus en plus petits, de plus en plus intégrés. Donc, ça va être de plus en plus difficile aussi d'avoir une espèce d'économie circulaire qui paraît encore très utopique. L'efficacité énergétique dont on vient de parler, n'augmente pas assez vite - et elle ne l'a jamais fait - par rapport à la consommation. Et du coup, eh bien non, on va pas pouvoir découpler très longtemps tout ça.

### Quel est ton avis sur le fait que l'empreinte du numérique, du cloud typiquement, ne prend pas en compte le scope 3, en général ? Définition rapide du scope 3, ce sont les émissions indirectes autres que les émissions directes et les émissions indirectes liées à l'énergie.

Effectivement, si on reprend le scope 1 ce sont les émissions directes, par exemple le refroidissement, l'utilisation de fuel pour les groupes électrogènes qui permettent d'avoir une fiabilité assez forte sur les centres de calcul.

Le scope 2 ça va être les émissions indirectes liées à l'énergie qu'on consomme, donc le mix électrique, par exemple, qui dépend du type d'électricité qu'on achète, par exemple, très nucléaire en France.

Et puis le scope 3 c'est tout le reste. Donc, souvent, c'est la majorité en fait. C'est par exemple la partie cycle de vie des équipements, la fabrication des serveurs, dont extraction des matières premières, l'assemblage de chacun des composants, puis l'intégration de tous ses composants et le traitement de fin de vie, donc, soit recyclage, soit réemploi. C'est aussi l'achat des équipements autres, la gestion des déchets des entreprises. C'est aussi - on en parlait tout à l'heure - les déplacements professionnels des personnels, les déplacements qui peuvent être liés aux maintenance si on a des des multi-sites, par exemple les trajets domicile - travail des employés, etc. Donc, ça peut être très, très large.

Les entreprises commencent de plus en plus à essayer de s'y intéresser. Par exemple, en 2021, Microsoft a estimé que plus des trois quarts de son empreinte était du scope 3. Et c'était une première estimation, sans tenir compte de tout. C'est vraiment une empreinte majeure qu'il va falloir reconsidérer. On ne peut pas prétendre une neutralité carbone ou quoi que ce soit d'autre sans considérer ses émissions de scope 3.

### Il y a une question territoriale, notamment sur l'implantation des centres de données. Quelle vision as-tu à long terme de l'impact sur le territoire de nos activités numériques ?

C'est assez compliqué d'y répondre puisque, effectivement, notre consommation de données est en augmentation : de plus en plus d'objets, de plus en plus de données. On exporte notre pollution quand on construit les centres de calcul qui permettent de traiter ces données à l'étranger, quand on fabrique les serveurs à l'étranger. Cette partie-là, si on la relocalise sur le territoire, ça va faire un impact assez conséquent. Et on peut se demander à quel endroit il faut localiser les centres de calcul et est-ce qu'il faut vraiment les construire, est-ce qu'il faut vraiment autant d'usages. Et puis comment on essaye d'optimiser tout ça en sachant qu'on a quand même assez peu d'énergie renouvelables actuellement sur le territoire.

Si on regarde un petit peu plus les données mobiles qui, elles, par contre, ce sont des infrastructures qui sont en France, puisque les réseaux mobiles, les antennes sont implantées sur le territoire. Si on regarde par exemple les données de l'Arcep, l'autorité de régulation des communications électroniques, des postes et de la distribution de la presse, au quatrième trimestre 2021, il y avait 80 millions de cartes SIM en France, tout compris prépayée et abonnement. Leur consommation mensuelle moyenne, combien de données consomment chaque utilisateur par mois, c'était 10,4 gigaoctets. C'est assez conséquent. Et si on regarde il y a 10 ans, fin 2011, c'était 0,1 gigaoctets par mois et par utilisateur. En 2011, c'était la 3G. On n'était pas du tout dans la même infrastructure, mais on a quand même multiplié la consommation de données par 100 en 10 ans.

Et le nombre d'utilisateurs a explosé lui aussi. Il y a 10 ans, il y avait beaucoup moins d'utilisateurs mobiles qu'actuellement. Donc, à long terme, l'impact sur le territoire va être quand même assez fort, surtout si on garde ces pentes, ces taux de croissance qui sont monstrueux : fois 100 en 10 ans, il n'y a pas d'autres secteurs où il y a ce genre d'augmentation massive.

### Et du coup, il y a un poids aussi sur la consommation énergétique sur le territoire. Tu travailles aussi et on y reviendra sur les Smart Grid, etc. Quelle est l'équation par rapport à l'implantation des centres donnés ? On peut faire un focus sur la consommation d'électricité, la consommation énergétique mais aussi la consommation d'eau, sur lesquels peut-être tu travailles ?

Oui, tout à fait. Alors si on parle de l'électricité, c'est ce qu'on nomme le scope 2. Effectivement, c'est un poids qui est important. On l'a vu, le scope 3 est encore majoritaire, et lui aussi il est sur le territoire. Sur le scope 2, il est pas majoritaire, mais c'est quand même un bon début pour commencer à réduire l'impact et donc voir où on localise nos infrastructures. En sachant, par exemple, aux États-Unis, quand ils implantent un nouveau super centre de calcul, ils sont obligés de le localiser très proche d'une centrale électrique, parce que sinon ils ont pas de quoi l'alimenter et il y a trop de pertes en ligne.

Il y a vraiment des problèmes assez forts sur l'alimentation de ces infrastructures. L'autre problème, c'est qu'il faut que ce soit des données, des infrastructures qui sont accessibles tout le temps, avec une forte garantie. Et donc, par exemple, il faut dimensionner des batteries, tel que sur les antennes. Vous imaginez une antenne mobile en cas de catastrophes climatiques majeures, il faut qu'elle soit encore accessible pour pouvoir notamment permettre l'arrivée des secours ou l'information des secours, etc. Ce sont des infrastructures pour lesquelles il faut des batteries pour qu'elles puissent marcher même en cas de panne majeure du réseau électrique. Donc, l'électricité n'est pas le seul problème, effectivement.

Souvent dans les centres de calcul, on a des groupes électrogènes pour les antennes, des batteries, etc. Les groupes électrogènes ont une durée de vie assez longue, mais les batteries pas tellement. Donc ça fait une infrastructure assez conséquente. Par exemple en Chine, lorsqu'ils ont envisagé le déploiement de la 5G, Huawei a fait une étude pour savoir de combien il allait falloir augmenter les infrastructures 4G qu'ils avaient déjà pour pouvoir supporter la 5G. Une antenne 5G va consommer plus en moyenne qu'une antenne 4G et donc il va falloir augmenter le câble électrique qui arrive jusqu'à l'antenne, les batteries, etc. Le coup était faramineux.

Toutes ces infrastructures, si elles supportent nos usages en croissance. Ça va être très important et le mix électrique va être très important dans les émissions. Tout ça, alors qu'on doit réduire. 

### Tout ça alors qu'on doit faire la transition énergétique, transition écologique, etc.

J'irai même plus loin. Tout ça alors qu'on imagine que le numérique va nous aider à faire cette transition.

### En parlant d'énergie, je ne sais pas d'où vient cet ordre de grandeur, c'est un auditeur qui propose cette question : la France, qui n'utilise que 18 à 19 % d'énergies renouvelables, est-ce que c'est un terrain adapté pour la construction de nouveaux centres de données ? Et quel modèle privilégier pour cette installation ? Que vois-tu sur le terrain, quelles sont les axes d'amélioration par rapport à ça ?

Effectivement, si on voulait être sobre, il ne faut pas installer, ça c'est sûr. Mais quel que soit le mix électrique, finalement, puisque tout mix électrique a un impact, même le nucléaire.

### Combien de centre de données sont installés en France chaque année ?

En France, je ne sais pas. Alors, l'implantation des centres de calcul dépend souvent pas de la source d'énergie, mais plutôt des optimisations fiscales, de ce genre de choses. Du coup, souvent, l'énergie est pas le critère principal, au moins en Europe, puisqu'on a un réseau électrique quand même très fiable.

C'est quand même pas simple d'implanter un centre de calcul. S'il est grand, il va falloir, il va falloir l'implanter dans une zone où il y a la place. Ça dégage de la chaleur s'il y a un refroidissement, qui soit par air ou par eau. Il faut des infrastructures assez grandes. Oui, il y a un problème d'infrastructure qui est plus de l'ordre du territoire et plus de l'ordre politique que, finalement, énergétique. C'est souvent pas la première préoccupation dans l'implantation.

Alors, un des axes d'amélioration qui est actuellement étudié, c'est le edge computing. Donc, on a parlé des antennes 5G. Elles vont probablement délivrer une bande passante bien supérieure aux utilisateurs et elle essaye de garantir une latence faible. Pour plein d'applications, une latence faible, ça veut dire qu'on n'aura pas le temps d'aller jusqu'à un datacenter qui se trouve aux États-Unis, par exemple, qui est quand même assez loin.

Donc, il va falloir avoir des ressources de calcul très proches des antennes de communication, par exemple, pour des applications telles que la virtualité, la réalité virtuelle augmentée et améliorée, etc.

Pour garantir ces faibles latences, on commence à imaginer des infrastructures de type edge computing, avec des serveurs distribués plutôt que d'être dans des gros centres de calcul, ils vont être distribués partout sur le territoire, un peu comme le fait actuellement les distributeurs de vidéos, par exemple streaming, tels que Netflix. Ils distribuent leurs serveurs au plus près de des utilisateurs pour garantir une faible latence et des performances élevées. Donc, ça, c'est un un type de cloud, finalement, qu'on voit de plus en plus se développer mais qui a l'inconvénient, de ne pas avoir des infrastructures mutualisées. Ce qu'on peut faire pour des gros centres de calcul, par exemple, du refroidissement à eau qui demande des infrastructures assez importantes tant d'un point de vue réseau d'eau, etc., c'est très difficile à faire à petite échelle.

Sur l'efficacité, notamment du refroidissement, ça va être compliqué de faire ça à petite échelle dans ces infrastructures là, et puis finalement, c'est juste d'autres nouvelles infrastructures qui se rajoutent aux infrastructures existantes. Donc, on empile encore une fois de nouvelles infrastructures.

### Tu en as parlé un petit peu tout à l'heure, c'est les GAFAM qui sont vraiment alimenté 100% en énergies renouvelables ou c'est du greenwashing ?

Effectivement, plusieurs parlent de zéro émission carbone, de 100% énergies renouvelables et quand on gratte un peu, la réalité est un petit peu différente. Souvent, en fait, ce qui recouvre par 100% renouvelables, c'est uniquement les scopes 1 et 2. Ils compensent uniquement la partie qu'ils émettent, c'est-à-dire qu'ils achètent ou ils produisent autant d'énergies renouvelables que ce qu'ils émettent en termes de ce dont ils ont besoin en scopes 1 et 2.

Il y a un article très bien fait sur notre site EcoInfo qui parle de ça. Cette compensation carbone a quand même des avantages et pas beaucoup d'inconvénients. Les énergies renouvelables sont intermittentes, c'est leur principal problème. Par exemple le solaire, il y en a pas la nuit. Et pourtant, Google n'est pas éteint la nuit. Et Apple non plus, Facebook non plus, etc.

Consommer de l'énergie lorsqu'il y en a pas pour les énergies renouvelables, ça supposerait de la stocker, ce qu'ils ne font pas. Puisque c'est assez compliqué, ça perd de l'énergie de stocker l'énergie. Du coup, en fait, ils se contentent juste de compenser sans avoir les inconvénients, finalement temporels, de production d'électricité, ce qui pose des soucis probablement à long terme sur le volume de production actuel.

Et puis comme tous les autres acteurs, ils compensent, mais ils continuent d'augmenter leur facture d'électricité. Donc ça ne résout pas non plus le problème et ce n'est pas dans la bonne trajectoire pour faire une transition énergétique.

### Certains disent que ça créé de l'inaction, finalement. Vu qu'ils compensent, qu'ils sont neutres, voire négatifs, ils n'ont pas d'effort spécial à faire, niveau efficience, au niveau de la sobriété.

Sobriété, non. Au niveau efficience, ils ont fait beaucoup d'efforts, par exemple  sur le refroidissement des gros centres de calcul, parce que ça leur coûte cher, tout simplement la facture électrique est importante. Et ce qui est embêtant aussi, c'est que, finalement, pour un fournisseur de cloud, l'électricité qu'il consomme, c'est du scope 1 et 2. Mais pour quelqu'un qui achète des services cloud, c'est du scope 3. Et donc, s'il y a écrit zéro émission carbone sur ce scope 3, qui prend pas en compte leur propre scope 3, et ça fait que tous les bilans derrière sont faussés finalement. Ou en tout cas très favorables.

### On va finir peut-être sur une note positive. Quels sont les effets positifs du numérique sur l'environnement ?

J'imagine, quand on pose cette question, il y en a plein de réponses qui sont très personnelles souvent.

### Par rapport à tes travaux, parce que tu travailles aussi sur l'IT for green, comme on aime l'appeler.

Effectivement, donc pour l'IT for green, c'est plutôt tout ce qui va être modélisation climatique, par exemple. Ne serait-ce que mesurer les impacts, c'est quelque chose qui a été rendu possible grâce à des modèles de plus en plus fins. Mesurer les impacts, avoir une confiance assez forte, puisque c'est des modèles qui sont de plus en plus développés, de plus en plus éprouvés, dans lesquels on a de plus en plus confiance. C'est aussi comme ça qu'on construit la recherche. Donc voilà principalement ça.

### Questions du public

#### Ce que je comprends le plus gros de l'une des émissions en tout genre, c'est la fabrication et donc l'urgence c'est d'arrêter d'acheter du nouveau matériel ?

Effectivement sur la phase de fabrication, il y a un très gros impact pour la plupart des équipements. Ne pas acheter, c'est une bonne solution, mais aussi faire durer ce qui existe déjà. Favoriser le réemploi, la réparation. Notamment avec l'indice de réparabilité de la nouvelle loi, qui permet de voir à quel point les équipements sont réparables, et on espère que les entreprises vont faire de plus en plus d'efforts. Par exemple, si une touche d'un clavier est abîmée, qu'on puisse changer juste la touche, pas tout le clavier, pour un exemple, un peu caricatural.

Et aussi empêcher l'obsolescence, qu'elle soit logicielle ou matérielle, c'est-à-dire que, par exemple, pour un smartphone, lorsqu'il devient un peu âgé, le système d'exploitation ne s'installe plus forcément, il y a plus forcément de mise à jour possible, et donc, il y a des initiatives qui naissent pour essayer de favoriser l'apparition de systèmes d'exploitation qui puisse s'installer sur des vieux téléphone. Par exemple Fairphone contribue à ce développement là. Essayer d'éviter l'obsolescence qui fait qu'on réduit la durée des équipements alors qu'ils fonctionnent encore et qui pourraient être encore utilisés longtemps. 

Réduire les achats et puis allonger la durée de vie, principalement, c'est les deux choses qu'on peut faire pour réduire cet impact de la fabrication, en tant qu'utilisateur.

#### Vers quoi est-ce que vous militez, est-ce que c'est en priorité vers les GAFAM, qui doivent changer leurs habitudes, ou c'est vers les particuliers qui, à travers des gestes du quotidien, peuvent vraiment modifier la consommation. Sur quoi est-ce qu'aujourd'hui il faut mettre un impact en premier ?

Alors, du côté particulier, il y a plein de choses qu'on peut faire et repenser nos usages peut-être. Après, ce serait un peu trop simpliste de  supposer que seuls les particuliers ont des efforts à faire. Parce qu'il y a un système économique entier derrière qui fonctionne uniquement par l'appât du particulier. On va dire notamment le tout, ce qu'on appelle le faux gratuit en tous ces services informatiques qui semblent gratuits, dont on est nous-mêmes les produits. Les abonnements illimités aussi, finalement, qui nous poussent à ne pas regarder notre consommation du numérique. Puisque l'on a payé un abonnement et qu'il est illimité, pourquoi éteindre la lumière, pourquoi éteindre la télé ? Il y a tout un système, un ensemble de mesures économiques qui font que l'usager n'a pas forcément d'incitations fortes à réduire ses usages. Donc, on peut repenser nos usages, mais on peut aussi repenser comment on nous les a vendus. Et donc, ça, c'est plutôt la balle est aux entreprises.
