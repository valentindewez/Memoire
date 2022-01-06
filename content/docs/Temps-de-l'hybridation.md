+++

Title = "Temps de l'hybridation"

weight = 4

+++

# Temps de l'hybridation 



*« Du papier à l'écran, la dualité s'estompe tandis que les formes de publication migrent d'un support à l'autre et réciproquement. La composition fixe de la page imprimée rencontre l'interactivité et le flux liquide et adaptable des écrans. C'est le design responsive qui s'étend aujourd'hui jusqu'au papier. Il devient possible à partir d'une même source de distribuer un contenu sur différents supports en lui appliquant une mise en forme adaptée à sa destination.*

*Cette existence hybride tire la conception graphique vers de nouveaux possibles : livres programmés, sites web typographies, publications multisupports, flux paginé, pages adaptables, textes paramétrables, formes génératives... Pour cela, il faut mettre les mains dans le code et les langages du web --- technologies libres, open source et collaboratives. »*[^1]



L'édition hybride peut être traitée à plusieurs échelles. Elle peut être élaborée dans les outils d'écriture/de publication, dans la « chaîne » ou « système » de publication, dans sa forme graphique et éditoriale ou même dans son économie. Dans la partie qui va suivre je vais essayer de dresser un portrait assez divers et hétéroclites sur la question de l'édition hybride à travers une série d'exemples dans différents champs importants et prolifiques sur ces questions. Le champ de la recherche qui présente des contraintes rédactionnelles et de diffusions spécifiques notamment liés à la structure sémantique du texte et aux formats de diffusion. Un champ plus lié à la création littéraire et graphique notamment à travers les maisons d'éditions, les revues, et fanzines, qui ont une liberté plus grande du média de diffusion et de sa forme. Et un dernier champ qui sera celui des réseaux sociaux permettant une prolifération littéraire plus spontanée, amateure parfois et souvent plus critique et expérimentale sur le sujet.



## Déployer la recherche : un besoin des chercheurs de pouvoir écrire un texte sémantique de façon simple, indépendante et de le publier



Le constat est simple : il n\'y a pas de solution aux besoins d\'écriture académique et scientifique d\'aujourd\'hui[^2]. Toutes les options existantes sont orientées vers l\'impression, il n\'est donc pas facile de générer un texte significatif lié aux exigences typiques de la structure numérique. LaTeX, mais il est toujours orienté impression et ne permet pas le balisage sémantique. Bien sûr, on pourrait écrire directement en XML, mais au prix d\'une écriture un peu lourde, ce qui fait que l\'on perd la fluidité nécessaire lors de la génération de texte. « Word a complètement monopolisé l\'écriture et les conséquences sont catastrophiques[^3] ».

<ins>**Le projet Stylo**</ins>

Créé par Marcello Vitali-Rosati, Nicolas Sauret, Servanne Monjour et Arthur Juchereau, Stylo est un éditeur de texte WYSIWYM[^4] en sciences humaines conçu pour changer toute la chaîne d\'édition numérique des revues universitaires en sciences humaines. Le projet a été réalisé en collaboration avec Érudit. Bien qu\'elle soit la base de la diffusion numérique, la structure sémantique du document est actuellement reportée jusqu\'à la fin du processus d\'édition. Cependant, il doit être considéré en termes de production, c\'est-à-dire l\'auteur lui-même. La philosophie de Stylo est de s\'appuyer sur les « compétences sémantiques plutôt que graphiques » des chercheurs et des éditeurs pour remettre la gestion du balisage entre leurs mains.

Pour son équipe, l\'éditeur de texte doit être sémantique. Les savoir-faire d'auteur sont des savoir-faire sémantiques, et non pas des connaissances graphiques. Dans le domaine de l\'imprimerie, les auteurs ont plus ou moins appris à traduire ces savoir-faire en connaissances graphiques : par exemple, un titre sera plus grand ou en gras, une référence sera en italique etc. La mise en place de ce genre de connaissances graphiques et logicielles est très chronophage, et le plus important est qu\'elle varie d\'un éditeur de texte à l\'autre. D\'une part, l\'auteur perd beaucoup de temps à les maîtriser et à les déployer dans l\'écriture et en fin de processus, le balisage sémantique en devient mauvais. Avec la prolifération des documents en ligne, il devient nécessaire de pouvoir baliser le texte de manière plus fine et rapide : avec des métadonnées « alignées[^5] » et « fiables[^6] », et la capacité de styliser graphiquement le corps du texte par balisage pour définir d\'autres parties de sa fonction (articles, hypothèses, définitions, concepts clés, exemples, etc.).

L\'éditeur de texte se veut user-friendly. La nécessité de simplicité dérive du besoin d\'avoir une écriture instinctive et rapide. Souvent, on pense en écrivant , il n\'est alors pas possible d\'interrompre l\'écriture pour se consacrer à l'utilisation du logiciel et de devoir insérer des balises complexes, ni, de se perdre dans l'interface pour trouver une fonction précise. En outre, plusieurs chercheurs ne sont pas prêts à dépenser trop de temps pour apprendre de nouveaux logiciels ou outils.

L\'éditeur doit être compatible avec d\'autres formes d\'écriture et de balisage. Il serait contreproductif ici de créer un monopole. L'équipe veut permettre aux auteurs de passer par plusieurs formes d'écriture et ainsi ne pas aliéner l'auteur dans un environnement donné tout en lui donnant les moyens de garder la richesse sémantique du texte qu'il a déjà établi. L\'éditeur doit donc s'appuyer sur des standards technologiques et d'écritures, afin d\'éviter le risque d'obsolescence de l'éditeur et de la production engagée par l'auteur, ainsi que d\'éviter les dangers liés à des formats clos ou propriétaires.

L\'éditeur de texte dispose de plusieurs formats de sortie différents, qui peuvent être ajustés en fonction des besoins spécifiques de chaque auteur et de chaque revue. Le texte doit pouvoir se diffuser dans différents environnements : imprimés, numériques, plus ou moins scientifiques, et sous différents formats. À une époque où les machines peuvent faire ce travail sans problème, il est inacceptable que les auteurs perdent du temps à reformater leur texte pour l\'adapter aux besoins de l\'éditeur.

L\'éditeur de texte doit être low-tech, sinon il ne pourra pas se maintenir dans le temps car les technologies seront trop difficiles à implémenter.

<ins>**Le projet Pandoc**</ins>

Pandoc est un logiciel libre de conversion, disponible sur les trois systèmes d'exploitation Linux, Microsoft Windows et macOS. Écrit en Haskell, il gère une trentaine de formats différents, comme formats d'entrée, comme formats de sortie, ou les deux -- certains formats ne peuvent être convertis qu'en entrée ou en sortie. Il s\'insère dans une question éditoriale des contenus en étant un outil angulaire sur cette question d'hybridation en permettant une passerelle entre différents langages et donc différents supports de publications.

Voici quelques exemples de conversion :

-   Markdown → HTML

-   Markdown → AsciiDoc

-   Microsoft Word docx → Markdown

-   HTML → LaTeX

[John MacFarlane] semble avoir créé ce programme d'abord pour ses besoins personnels, avant qu'il ne devienne le compagnon incontournable des curieux et curieuses de la publication numérique. Il faut noter que John MacFairlane continue de maintenir ce programme, dont le code source est disponible et modifiable [sur GitHub].

Pandoc est peu connu en comparaison de ses nombreuses applications, c'est en quelque sorte un outil de l'ombre -- comme il en existe beaucoup. Pour réaliser une tâche il est rare de disposer d'un seul programme en informatique, c'est pourtant le cas avec Pandoc, et probablement pour trois raisons. La première est que malgré la relative simplicité des langages de balisage, convertir certains formats est parfois un défi de complexité. Qui plus est, Pandoc dispose de nombreuses options très puissantes, par exemple pour la gestion des notes ou des citations -- avec l'aide incontournable du programme [pandoc-citeproc], également développé par John MacFarlane. La seconde est que Pandoc fait bien ce pour quoi il est conçu, c'est un exemple de logiciel efficace qu'il semble difficile de détrôner. Pour des conversions spécifiques -- notamment Markdown vers HTML -- les concurrents sont nombreux, conçus pour s'adapter à des langages de programmation particuliers (Python, Ruby, Go). La troisième raison est que les langages de balisage, il faut bien l'admettre, n'attirent pas non plus les foules. Et dans des cas comme XML, Pandoc devient dérisoire en comparaison de XSLT.

Pandoc est un convertisseur agnostique, il n'impose pas une pratique par rapport à un balisage. Certaines conversions sont toutefois tout simplement impossibles : un format complexe est trop difficile à réduire au risque de perdre la majorité des informations, ou de ne pas savoir quoi en faire.

Pandoc est un révélateur. Tout d'abord parce que son utilisation nous fait comprendre avec beaucoup d'acuité qu'un texte est forcément structuré. Aussi son usage nous fait mieux comprendre les enjeux d'ouverture et d'interopérabilité liés aux formats.

En théorie Pandoc pourrait être utilisé pour produire facilement des pages web, disons qu'il est plutôt conçu pour fabriquer des fichiers HTML. Une organisation spécifique ou un programme peuvent ensuite permettre d'envisager l'utilisation de Pandoc pour concevoir un site web, mais il serait faux de penser que Pandoc peut le faire seul[^7].

<ins>**Le projet Indefensible**</ins>

Project Indefensible est une interface de lecture académique. Il propose une nouvelle façon de lire, d\'interagir et de partager des textes en ligne, à travers un texte académique. Il examine et démystifie les mythes sur le commerce mondial des armes. Réalisé par LUST, le site propose différents outils de lecture permettant une lecture immersive, sourcée et interactive. Je vais lister l'ensemble des outils proposés par le projet.

Sommaire : Un sommaire permet une navigation instantanée vers un chapitre précis de l'essai (système d'ancre)

Index visuel/Mini carte : L\'index visuel est une miniaturisation du texte, offrant une vue d\'ensemble du texte à des fins de navigation. Il s\'agit d\'une méthode immatérielle pour s\'orienter dans de longs textes, analogue aux pages d\'un livre imprimé. En tant qu\'index du contenu, il donne le contexte du contenu avec lequel les lecteurs interagissent, ainsi qu\'un moyen de réinterpréter la lecture grâce à la navigation.

Recherche contextuelle : La recherche contextuelle offre au lecteur la possibilité de générer une compilation alternative d\'un texte à partir de ses propres termes de recherche. L\'occurrence de ces termes est reflétée dans un graphique qui rend visible leur fréquence dans le flux du texte original. Cette réinterprétation crée une nouvelle structure narrative et une nouvelle approche de la lecture littéraire. Des interprétations infinies sont possibles, en puisant dans les propres intérêts du lecteur dans le texte. Cela ouvre une discussion sur l\'interprétation générée par le public et la linéarité dans les médias en tant qu\'outil critique (pluralité d'opinion et de sources) de création de médias.

Mode Focus : Le mode Focus fournit une méthode d\'interaction avec les médias littéraires dans des contraintes de temps. En parcourant seulement un morceau en faisant défiler rapidement le texte, les passages clés deviennent apparents (highlight) pour le lecteur contrairement au reste du texte. Cela permet aux lecteurs de s\'engager avec les passages principaux sans qu\'ils soient décontextualisés, comme avec la citation. Ces sections sont intégrées dans le texte de manière non hiérarchique pour ne s\'activer que dans les situations où un lecteur fait défiler rapidement. Le mode focus est une expérience de formes de lecture qui reflètent le comportement du public.

Notes et partage : Mettez en surbrillance une partie spécifique du texte et enregistrez-la en tant que note ou partagez-la sur Facebook ou Twitter.

Notes de bas de page : L'outil permet de faire des références croisées entre les notes de bas de page du texte et celles des lecteurs, en utilisant le logiciel implémenté Hypothesis. En cliquant sur une note de bas de page naturellement implémentée dans le texte, celle-ci s'alignera avec les autres références ajoutées par autrui. Il est possible de réagir à ces notes, et de les lier à d'autres types de contenus (iconographie, vidéos...).

Créer des notes : La création d\'annotations de lecteur est génératrice d\'un récit parallèle au texte original. Le public est invité à s\'intéresser au contenu en prenant des notes et en réagissant aux côtés de l\'original. Au fur et à mesure que leur propre ensemble d\'annotations est compilé, les annotations prennent leur propre forme en tant que média littéraire comme le texte original. Les annotations existent latéralement, ils se rejoignent pour produire une lecture nouvelle et anthropologiquement riche.

Partager sa session : Chaque session unique d\'annotations produit un lien partageable, où le lecteur peut inviter d\'autres personnes à collaborer en session d\'annotation. Cette façon de lire, de prendre des notes et de réfléchir permet de faciliter l\'engagement critique et de discussion. Ces sessions invitent de multiples récits à exister en dialogue avec le texte, générant de multiples lectures de la littérature.



## Accès aux données, technologies, outils numériques et de développement web : un vecteur de création et de publication supplémentaire



Le Web amène des bouleversements dans les processus et dans les modalités de création, de circulation et de consommation de productions culturelles par de nombreux points vu dans la partie précédente notamment par son ubiquité et son immédiateté. Certains acteurs de l\'édition ont pris ces questions à bras-le-corps afin de proposer une nouvelle économie du livre. Grâce à de nouveaux systèmes de publications dans un premier temps, tendant vers une horizontalité dans la manière de concevoir et dans le rôle des différents acteurs de ce dit système. Et aussi avec de nouvelles formes hybrides vers de nouveaux possibles (livres programmés, sites web typographiques, publications multisupports, flux paginé, pages adaptables, textes paramétrables, formes génératives). Amenant pour souvent une personnalisation des imprimés en ligne grâce à des scripts tels que paged.js[^8], bindery.js[^9] ou html2print[^10] par exemple.

<ins>**La maison d'édition Abrüpt**</ins>

Abrüpt est une maison d'édition associative tournée autour de contenu philosophique et politique. Leur ligne éditoriale défend une certaine révolution populaire et une forme de liberté. Ils promeuvent la liberté de l'information et condamnent ce que la « piraterie littéraire » corrompt au sein de nos langueurs sociales. A l'aide d'auteurs complices et en adéquation avec leurs idéaux, ils tentent un retournement des genres. « Nous œuvrons au désœuvrement, et néanmoins il nous arrive de puiser dans un savoir artisanal, de lui offrir une métamorphose numérique, pour [*composer nos ouvrages*], qui composent à leur tour le creuset de nos réflexions. »[^11] Ils placent leur créativité au-dessus de l\'avènement pécuniaire du livre, en vendant certaines de leurs éditions à prix libres.

Elle conduit une économie du livre singulière quoique de plus en plus courante en proposant trois formats différents pour un même ouvrage.

Une version broché plus conventionnelle (avec sur certains ouvrage la possibilité d'un prix libre), une version numérique du livre (ePUB) et un *antilivre*, une forme de livre gratuite dans un format *pdf, html (reprenant la forme interactive/inédite du livre numérique), img, diy (à assembler et relier soi même)* ou *git.*

Voici comment Abrüpt défini son *antilivre* :

*« L'antilivre est une dynamite, est son partage, est l'espace où l'électrique déploie sa langue d'aurore. L'antilivre est une divination, est sa brisure, est la piraterie qui insinue son rêve, sa révolution, parmi la clandestinité des réseaux. L'antilivre est une métamorphose, est son désordre, est l'affirmation d'une littérature des courts-circuits, de sa circulation joyeuse, contre l'époque, contre le livre et sa grammaire, contre sa chaîne et ses ronronnements, pour un futur des altérations, pour une information libre et réticulaire, pour une multitude éclairée par celle-ci. L'antilivre cisaille les lenteurs industrielles du siècle, il façonne des idées d'après-demain à force de recomposer la pluralité de ses passés. Ici, rien ne se tisse, rien ne stagne, le texte trouve une texture encore inconnue en ce qui le survolte, et le verbe, à rebours du flux de nos mondes, fabrique les structures nouvelles de son expression. Direction silicium : l'antilivre trafique de l'irréel pour que s'offre en partage l'abrupt. L'antilivre n'a pas de forme, son impermanence dispose de toutes les formes, il se transforme sans cesse, et son information brute ne connaît aucune fixité, aucune frontière, elle fragmente son essence, distribue le commun, déploie sa liberté au-devant de nos singularités cybernétiques. Son identité fuit l'identique, sa norme la normalité, son extravagance n'image de mouvement qu'au travers de la nécessité de son partage. »[^12]*

La maison d'édition s'appuie sur une imagerie très sombre et mystérieuse proche de l'idée de secte et d'anarchisme. Elle y développe des idées singulières, expérimentales et autonomes, en créant un écosystème cohérent d'un point de vue graphique et idéologique. Un idéal de partage, de libre accès, et de la dépossession des standards du livre. « La conséquence de cette utilisation au scalpel du droit d'auteur, avec cette belle contingence qui a les grands airs de la tyrannie, se trouve être étrangement la socialité. Le fait d'amener le créateur d'une œuvre dérivée à nous contacter pour montrer patte blanche et obtenir blanc-seing de l'auteur originel --- si cette notion d'origine a un quelconque sens dans l'histoire humaine --- construit du lien. Se tissent des connexions horizontales entre les différentes volontés créatrices qui dérivent les unes des autres, et une effervescence collective devient alors possible. »[^13]

**<ins>La revue Back office</ins>**

*« Back Office* répond à un état de fait : malgré le nombre croissant d'ouvrages dédiés au design graphique dans le contexte francophone, peu de recherches abordent de front les enjeux du numérique. Tandis qu'en langue anglaise, l'histoire de l'informatique, la philosophie du numérique, l'archéologie des médias ou les *software studies* (études logicielles) font l'objet de nombreuses publications, qu'en est-il de leur réception en langue française ?

*Back Office* est née de ce manque d'écrits et de recul critique, à propos d'une culture technique tellement installée parmi nous que le substantif « numérique » (design numérique, humanités numériques, etc.) semble superflu. Jumelle de *Back Cover* ([Éditions B42]), bilingue, à parution annuelle et thématique, *Back Office* s'incarne dans un double format : revue papier et application. Des articles de fond font face à des formes courtes, traitant de sujets spécifiques ou d'initiatives pédagogiques inventives, et à un texte historique, exhumé et relu par son auteur plus de vingt ans après, permettant d'évaluer les mutations de la discipline. Un glossaire technique, éclairant une terminologie souvent obscure pour les non-initiés, accompagne chaque numéro. Face à une actualité toujours plus dense, et déjà bien couverte sur le Web, la revue affirme son orientation critique, privilégiant les prises de recul, les problématiques, ou les hypothèses à même d'éclairer la situation contemporaine et d'y tracer de nouvelles trajectoires. »[^14]

La Revue Back office de par la pertinence des articles présents dans chaque numéro ainsi que son double format imprimé et numérique (consultable gratuitement en ligne) constitue un acteur important du renouveau de l'édition numérique et des pratiques numériques en France. En étant elle-même fer de lance d'un renouveau graphique et éditorial d'en la publication de Revue. La revue incarne cette hybridation entre supports imprimés et numériques dans un double format : à la fois une revue papier à la forme graphique et à la matérialité maîtrisée, et une application pour tablettes, smartphones et web). Le contenu et la forme de la mise en page seront ajustés en fonction des caractéristiques de chaque média, de manière à mettre en pratique certains principes d, tels que l'hybridation des médias, les exigences de la mise en page ou la question de la typographie et navigation sur écran.



## Médias sociaux, nouvel environnement trouble d'écriture, de publication et de lecture



Quelle position amène les réseaux sociaux numériques aujourd\'hui ? Il semble que Facebook et Twitter apparaissent comme un réel outil d'écriture des journalistes, des artistes et écrivains en offrant un environnement littéraire contraignant mais créatif[^15], des matériaux hétérogènes (vidéos, images, sons, textes), des opportunités de transfert et de partage, qui visent à capter le temps et l\'attention des utilisateurs disponibles. Mais Le microblogging, écriture de soi brève, fluide et asynchrone, n'a pas pris longtemps pour faire de *Facebook* ou de *Twitter* des lieux d'écriture littéraire. Détournant leur dispositif, il mène à des formes à contraintes expérimentales. Mieux encore, l'écriture par fragments, avec son univers de flux affectifs en attente d'échos, accompagne la conversion numérique de l'expérience humaine : loin d'être l'empire de la banalité et de l'éphémère, le microblogging pousse la littérature à quitter les espaces pensés pour l'expression littéraire et à s'imposer à l'intérieur des dialogues sociaux.

<ins>**La médiatisation des savoirs à travers la vidéo</ins>**

Fouloscopie[^16] est une chaîne youtube tenue par Mehdi Moussaid, chercheur en science cognitive à l\'institut Max Planck de Berlin. Et traitant notamment de la question des foules et de leurs comportements. Celui défini la fouloscopie comme « la science du comportement des foules : paniques, mouvement de foule, propagation de rumeurs, réseaux sociaux, intelligence collective\... ». La vulgarisation est devenu un pan important du paysage vidéoludique sur Youtube. En effet, de plus en plus de chercheurs sortent de leurs canaux habituels de diffusion[^17] et viennent confronter leurs savoirs et recherches à un terrain beaucoup plus incertain que celui qu'offre le monde de la recherche[^18].

Etienne Klein, physicien, philosophe des sciences et producteur de radio de l\'émission *Sciences en question ( anciennement La conversation scientifique)* de France Culture ainsi qu'acteur sur Youtube avec des vidéos de vulgarisation sur la chaîne de France Culture et la diffusion de ces cours théorique. Il développe un raisonnement sur la question de l'accès à la connaissance à travers un média tel Internet : « La science et la pédagogie étaient depuis longtemps liées à la linéarité du livre, où il faut insister pour réussir à dépasser les difficultés. Alors que sur Internet, les savoirs sont présentés sous forme de mosaïque et quand on bute sur une difficulté, on est incité à regarder ailleurs. Donc soit le succès de YouTube montre que le livre se fait dépasser par d'autres formes d'accès à la connaissance, ou bien, et c'est mon hypothèse favorite même si je ne peux pas la démontrer, ce succès montre qu'on a installé dans le paysage un chaînon manquant de la pédagogie. Il y a des gens qui ont du mal avec l'abstraction et l'écriture, et ils vont trouver là une marche supplémentaire dans l'escalier du savoir, qui va leur permettre de monter d'un cran leur niveau de compréhension et de se sentir ensuite mieux armés pour affronter des livres. »[^19]

Malgré cela « *Il existe une zone grise, un deux poids deux mesures sur la législation culturelle qui est assez inconfortable. La réalité des contenus culturels et de leur usage a évolué. Au Parlement européen, il y a eu de grands débats autour du rapport de l\'eurodéputé Julia Reda* \[ndlr : Le Parti pirate\] *à ce sujet. On y parle de créer un \"fair use\", un usage loyal à l\'européenne* \[ndlr : un usage qui essaie de prendre en compte à la fois les intérêts des bénéficiaires des droits d\'auteur et l\'intérêt public\]. *Ça n'est pas gagné, vu la méconnaissance qu'ont beaucoup de gens à propos du web. Il y a des mentalités à faire évoluer, mais ça c'est le phénomène d'inertie : le wagon des institutions et de la législation met toujours un certain temps à se raccorder à la réalité des faits.* »[^20]

**<ins>Franck Leibovici</ins>**

Franck Leibovici (1975), poète, artiste, travaillant avec des transcriptions systématiques et des emprunts dans le milieu numérique.

Dans *des opérations d\'écriture qui ne disent pas leur nom,* « Franck Leibovici s\'intéresse ici aux écritures ordinaires, liées à des routines qui échappent à notre attention ou à notre champ de vision et, pour cela, demeurent innommées.

Partant d\'exemples tirés de la poésie des vingt dernières années, des *literacy studies*, des *media studies*, de l\'anthropologie ou du droit international pénal, *des opérations d\'écriture qui ne disent pas leur nom* traite de l\'écriture comme action : écrire (noter, transcrire, récrire, indexer, republier), c'est activer une chaîne étendue d\'inscriptions, deprescriptions et decollectifs -- en somme, un écosystème social composé non plus de textes, mais de documents, à travers lesquels nous mobilisons des médiations et des pouvoirs.

Plutôt que d\'observer des objets d\'écriture tenus *a priori* pour littéraires, Franck Leibovici examine leurs relations avec la documentalité la plus ordinaire. Quel type de fonctionnement et d\'usage ces objets partagent-ils avec des pièces dont l\'établissement, la production et la circulation déterminent l\'ordre présent de nos sociétés ?

La dimension politique et éthique de la littérature réside dans sa capacité à concentrer, redistribuer, reconsidérer les marques de pouvoir qui circulent dans les documents que nous visons, paraphons, signons chacun quotidiennement.

*des opérations d\'écriture qui ne disent pas leur nom* esquisse, par là, une reconception radicalement non essentialiste de l' art et de la poésie. »[^21]

*De l\'amour*, livre du même auteur qui cette fois-ci utilise les opérations décrites dans *des opérations d\'écriture qui ne disent pas leur nom. De l'amour «* se compose de quatre scènes, quatre échelles autonomes : un salon de discussions en ligne, des échanges sur l\'application \_tinder, \_une scène de sexe, une correspondance amoureuse à plusieurs mains, sur plusieurs pays. Le passage d\'une scène et d\'une échelle à l\'autre permet au lecteur de zoomer puis dézoomer, d\'aller au plus fin, au plus intime. le lecteur n\'aura toutefois jamais accès à ce que les anglo-saxons appellent la *big picture* - car cette dernière n\'existe pas : il n\'y a pas de position panoramique, il n\'y a que des dispositifs socio-techniques ( un \_chat \_sur internet, une application sur smartphone, une \_sex-tape \_amateure, des spams échangés par email). les suivre simplement en lisant ce qu\'ils racontent dessine le portrait d\'une génération qui réinvente les codes de l\'écriture et de la rencontre amoureuse. »[^22]

La poésie est une des formes les plus adéquates et libres aujourd'hui pour tester toutes ces opérations d'écriture, se joignent à Franck Leibovici, des poètes/artistes tel que Anne-James Chaton et des poètes/designers comme Rémi Forte.

L'hybridation est donc devenue un point central de la publication dans de nombreux champs. En effet, cette hybridation amène à de nouveaux questionnements et bouleversements dans les médias et leur utilisation. Elle questionne en premier lieu le système de diffusion sur internet, en cassant une linéarité et hiérarchie des étapes de la chaîne. Elle s\'insère dans un héritage de la culture du hackeur depuis les années 50 où elle tente une altération créative visant à améliorer le fonctionnement du système actuel. Cette hybridation se caractérise par des actions à plusieurs échelles et souvent interconnectées. D'abord un travail d\'ingénierie logicielle permettant de rendre des logiciels libres, transversaux, lowtech, et en adéquation avec les enjeux du milieu dans lequel il se propage. Une autre en vient de l'utilisation même de ces outils et la réflexion qu'elle porte sur le support, la publication et sa forme. La dernière est sur l'économie et le partage qu'elle crée ainsi en bouleversant des codes établis notamment en redéfinant le prix d'un livre, ses droits d'auteurs, sa circulation.

J'ai ici compilé ses questionnements et bouleversements en distinguant chaque strate d'actions, mais tout comme l'hybridation tente de faire système dans la publication, il n'est pas moins certain que ces questionnements et bouleversements soient entremêlés de façon non-linéaire dans toute la phase de réflexion et d\'élaboration du projet.

[^1]: Julie Blanc, Grand Atelier 2020, ESAD Orléans, Scripter Gutenberg: des publication de papier et d\'écran, https://workshops.julie-blanc.fr/2020-esad-orleans/ \[consulté le 17/11/21 à 17:09\]

[^2]: Vitali-Rosati, Marcello. 2015. « An editor for academic papers (xml, html, md, TeX, pdf and if you really need it rtf) ». BlogPost. *Culture numérique*. [[http://blog.sens-public.org/marcellovitalirosati/an-editor-for-academic-papers-xml-html-md-tex-pdf-and-if-you-really-need-it-rtf/

[^3]: Ibid.

[^4]: What You See Is What You Mean

[^5]: Ibid.

[^6]: Ibid.

[^7]: Bortzmeyer, S.(2018, 10/19). Consulté à l'adresse https://www.bortzmeyer.org/generateurs-web-statiques.html

[^8]: cf pp.

[^9]: cf pp.

[^10]: cf pp.

[^11]: Abrüpt, organisation https://abrupt.cc/organisation/

[^12]: Abrüpt, Antilivre [[https://www.antilivre.org/#manifeste

[^13]: Abrüpt, Partage https://abrupt.cc/partage/

[^14]: Présentation de revue Back Office, [[http://www.revue-backoffice.com/\[ consulté le 17/11/2021 à 15h22 \]

[^15]: les 140 caractères de Twitter par exemple

[^16]: https://www.youtube.com/c/Fouloscopie/

[^17]: revues scientifiques, plateformes académiques

[^18]: Notamment ouvert à des personnes non-issues à leur champ d'expertise ou à la discipline de façon plus large, et donc parfois plus ouvert à la critique.

[^19]: Propos tenus dans une interview chez Libération, [[https://www.liberation.fr/futurs/2016/09/07/etienne-klein-on-a-installe-un-chainon-manquant-de-la-pedagogie_1488988/

[^20]: François Theurel aussi connu sous le pseudonyme Le Fossoyeur de films, entretien dans *Sur YouTube, des vulgarisateurs face caméra,* France Culture, 2016 \[consulté le 19/11/2021 à 14h27\]

[^21]: Franck Leibovici, Résumé *in* des opérations d\'écriture qui ne disent pas leur nom, questions théoriques, 2020

[^22]: Franck Leibovici, Résumé *in* De l'amour..., Jean Boîte éditions, 2019
