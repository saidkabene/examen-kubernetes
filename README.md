# examen-kubernetes

1)- Vérification de la connexion au cluster en éxecutant la commande: 
	- kubectl cluster-info 

2)- création des fichiers yaml permettant de lancer des Pods
	- deployment-node-redis-Said.yaml 
	- deployment-redis-said.yaml 
	- sevice-said.yaml


3)- exécution des  ces commandes va créer une série de Pod à partir de la configuration : 
	- kubectl create -f deployment-node-redis-Said.yaml 
	- kubectl create -f deployment-redis-said.yaml 
	- kubectl create -f sevice-said.yaml

4)- Vérification de la création des pods et du service avec les commandes : 

	- kubectl get pods
	- kubectl get service 

5)- vérification de la connexion à redis 

	- kubectl logs 'nom-du-pods'

Le nom du pod peut etre récupéré avec la commande : kubectl get pods