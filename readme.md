CREATION DU CHATBOT 
1)on installe d'abord  python
2)puis on installe rasa avec la commande suivante : pip install rasa 
3) aprés l'installation on fait : rasa init (ceci cree un chatbot avec tous les fichiers necessaires)
4)on install rasa x : ceci est optionel (il permet d'avoir une interaction graphique avec le chatbot rasa)

DEPLOIMENT DU CHATBOT 
pour le delpoiment on utilise heroku et heroku utilise git ce qui fait le deploiment se fait avec git 
voici les etapes 
1)création d'un compte heroku
2) puis on fait  :git init
3) on ajoute le projet sur git: avec git add
4) puis on commit avec :git commit 
5) puis on se connecte au compte heroku avec : heroku login 
6) puis on cree l'application en specifiant le nom avec : heroku create chatbotgainde2k
7)puis accede au container du docker avec : heroku container :login
8) puis on execute avec :heroku container: push web (ceci execute les instructions qui sont dans le fichier Dockerfile)
9)et enfin on fait :release web
 et c'est bon et pour verifier on peut faire : heroku open (pour voire si le serveur a bien demarré) 
 