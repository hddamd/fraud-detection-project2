# fraud-detection-project2
Ce projet consiste à développer un API (fastAPI) d'un modèle ML (Machine Lean=rning) pour la détection des transactions bancaire frauduleuses et le et le deployer sur Docker et Kubernetes.
* L'API permet de checker une transaction avec deux modèles: Kmeans, et CatboostClassifier.
* Deux fichiers .pkl des deux modèles sont dans le répertoire. Ainsi pas besoin de les régénérer avec le fichier ml_pour_generer_model.py
* Dans le répertoire également, il y a deux prise d'écrans de l'exécution des conteneurs dans Kubernetes. On a réussi à les faire communiquer.
