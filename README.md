Shell Scripts
=============

--------------------------------------------------------------------------------
my_bashrc (EPITECH) :
--------------------------------------------------------------------------------
Une commande qui concerne l'auto-complétion et qui permet d'ignorer les
fichiers *.o
Un alias afs pour pouvoir se connecter directement sur l'AFS via son login
Epitech.

--------------------------------------------------------------------------------
my_cppheader :
--------------------------------------------------------------------------------
Script qui permet de générer un fichier .h ou .hh d'une classe ainsi que le
fichier .cpp.
Il suffit de spécifier le nom de la classe à générer, si l'on souhaite oui ou
non générer la forme de Coplien et si la classe hérite d'une autre classe.

Usage: ./my_cppheader classname hh [coplienform] [inheritanceclass]

Pour plus d'informations concernant le usage :
$> head -13 my_cppheader

--------------------------------------------------------------------------------
my_clone (EPITECH) :
--------------------------------------------------------------------------------
Script qui via votre my_select (placer dans le répertoire ${HOME}/bin)
permet d'effectuer une sélection d'un de vos projets se trouvant dans
${HOME}/rendu et de réaliser un clone (via git clone).
L'intérêt est de pouvoir vérifier que votre rendu a bien fonctionné.

--------------------------------------------------------------------------------
my_git :
--------------------------------------------------------------------------------
Script qui prend en paramètre le message à utiliser pour le commit.
Il exécute les commandes : [make fclean], add, commit, pull & push.
Si le pull échoue, il vous suffit de corriger les conflits puis de relancer
le script ;)
La commande make fclean est exécuté uniquement si un Makefile est trouvé.

--------------------------------------------------------------------------------
my_nc :
--------------------------------------------------------------------------------
Script qui via nc permet d'envoyer via un réseau (LAN, WAN, ...) un fichier
par redirection. Le port utilisé est 4242, exemple d'utilisation :

SENDER (ip du RECEIVER)
./my_nc mon_fichier.tgz 1 10.13.253.142

RECEIVER (exécute la commande en premier)
./my_nc mon_fichier.tgz 0

--------------------------------------------------------------------------------
my_wc (EPITECH) :
--------------------------------------------------------------------------------
Script qui via wc compte le nombre de lignes de code dans un projet en tenant
compte des headers et sources. Le header Emacs de 11 lignes n'est pas compté.

--------------------------------------------------------------------------------
my_rendu (EPITECH) :
--------------------------------------------------------------------------------
Script qui permet de créer un repository avec les droits actl par défaut. Puis
réalise l'équivalent du script `my_git` si le dossier .git est présent.

--------------------------------------------------------------------------------
my_wpa (EPITECH) :
--------------------------------------------------------------------------------
Script qui réinitialise la connexion WiFi s'il est devenu impossible de se
connecter au réseau.

--------------------------------------------------------------------------------
my_xrandr (EPITECH) :
--------------------------------------------------------------------------------
Script qui permet de connecter la sortie VGA à un vidéo projecteur pour scinder
en deux l'écran du PC avec le vidéo projecteur.

--------------------------------------------------------------------------------
xworkspace (EPITECH) :
--------------------------------------------------------------------------------
Script qui fait le café :
Ouvre 6 terminaux XTerm, créer un projet si besoin (copie d'un Makefile, main.c
& template.h ; création des dossiers includes/ libraries/ sources/).
4 terminaux sont ouvert dans le dossier sources/, le premier à la racine où se
trouve le Makefile et le dernier dans le dossier includes/.
