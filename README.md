# ProjetAnsible

* PLaybook:
- Installation nécessaires pour Docker , consul
- Importation des projet des Fullstack 
- stckage des configuration de chaque application dans la base Consul
- build et run des deux applications dans des conteneurs


* DockerFile
- Installation et configuration de Consul et confd 
- Confd récupère les valeurs pour la configuration de l'application NodeJS depuis la base Clé/valeur Consul , ceci en utilisant des template pour la création des configuration de node et nginx.
- Un script est éxécuté par confd au démarrage du conteneur pour lancer l'application 
