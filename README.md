La mémoire est le lieu où se trouvent les programmes et les données quand le processeur les exécute. Le terme "mémoire" fait surtout référence à la mémoire principale, c'est à dire à la RAM, et la gestion de celle-ci doit être effectuée d'une manière optimale et attentionnée, car en dépit de sa grande disponibilité, elle n’est, en général, jamais suffisante. Ceci en raison de la taille continuellement grandissante des programmes. Celui qui s'occupe de la tâche de gestion s'appelle gestionnaire de mémoire.
Le gestionnaire de mémoire est un sous-ensemble du système d'exploitation qui permet de faire un certain nombre de tâches parmi lesquels il y a l'allocation d'espace libres aux processus utilisateurs en utilisant un algorithme d'allocation comme First-Fit et Best-Fit.
Mon but consiste à créer une application d'allocation de mémoire. Pour réaliser cet objectif, on a utilisé nos compétences de programmation en langage C et j’ai conçu " A2M BF-FF "
A2M BF-FF est un programme informatique simple d'utilisation qui permet de gérer l'allocation de mémoire d'un processus quelconque.

Ce programme peut être utilisé par les programmeurs, les étudiants ou les amateurs d'informatique , pour savoir comment seront gérés les processus d'un programme à l'aide des états bien présentés avec des commentaires explicatifs.

Très facile à maîtriser, A2M BF-FF permet de suivre instantanément l'évolution d'un programme en répondant très facilement aux besoins des utilisateurs.

Les consignes du projet :

Ce projet parle de la création d'une application d'allocation de mémoire en utilisant deux types d'algorithmes d'allocation et deux types d'algorithmes d'ordonnancement sachant que Le système dont nous somme entrain d'étudier dispose d'un seul processeur.
Les deux types d'algorithmes d'allocation sont :
1.FF (First-Fit) : Le premier bloc suffisamment grand pour contenir notre processus est celui qu'on va allouer au processus pour qu'il doit exécuté.
2.BF (Best-Fit) :  Le plus petit bloc suffisamment grand pour contenir notre processus est celui qu'on va allouer au processus pour qu'il doit exécuté.

Les deux types d'algorithmes d'ordonnancement : 
•	FIFO (First In First Out) : appelé aussi FCFS (First Come First Served), c'est l'un des algorithmes les plus simples qu'il soit. L'idée est d'ajouter chaque processus dans une file et d'exécuter chaque processus par ordre d'arrivée.
•	SJF (Short Job First) : L'algorithme SJF (plus court d'abord) ressemble au FIFO mais au lieu d'exécuter dans l'ordre d'arrivée, on choisi d'exécuter celui qui a le plus court temps d'exécution.

Donc devant une liste d'attente des processus arrivés, notre programme va devoir choisir le prochain processus à stocker dans la RAM en utilisant l'algorithme FIFO, et avant  de lui allouer un espace libre de mémoire, si c'est possible, on cherche le bloc adéquat grâce à l'un des deux algorithmes d'allocation choisi : BF ou FF. Une fois le processus est alloué, celui qui sera prochainement exécuté est celui qui une durée d'exécution la plus courte : SJF. Il faut noter aussi que chaque processus est caractérisé par des informations chargées par le programme à partir d'un fichier de type TXT. Chaque ligne de ce dernier est composée des données suivantes séparées par un point virgule : 
•	Le code qui identifie le processus de manière unique
•	La date d'arrivée du processus
•	La taille d'espace mémoire demandée
•	Le temps d'exécution du processus

Lorsque le programme est en marche, l'utilisateur charge le fichier TXT contenant le BCP de chaque processus ensuite il choisit le type d'algorithme d'allocation de mémoire, il précise la taille de la RAM,  puis il reçoit la présentation de tous les nouveaux états instantanés de la RAM avec l'adresse de début et de fin de chaque bloc, la taille de chacun, les processus en attente ainsi que les commentaires.

Attention !!
Avant d’utiliser cette application il faut s’assurer d’avoir configurer la console de la manière suivante :
<p align="center">
  <img src="/important.JPG">
</p>

Ensuite vous pouvez utiliser l'application

<p align="center">
  <img src="/0.png">
</p>
<p align="center">
  <img src="/1.png">
</p>
<p align="center">
  <img src="/2.png">
</p>
<p align="center">
  <img src="/3.png">
</p>
<p align="center">
  <img src="/4.png">
</p>
<p align="center">
  <img src="/5.png">
</p>

Voici le lien pour la video de simulation : 

Voici mon email si on voudrait me contacter : abouabdelmajidkhalil@gmail.com
