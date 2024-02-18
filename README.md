# Linux Project
# Démarrage de l'application

Suivez ces instructions pour lancer l'application.

## Étapes pour lancer l'application

1. **Clonage du dépôt**

   Ouvrez votre terminal et exécutez les commandes suivantes pour obtenir le code source du projet :

git clone https://github.com/qchalex/Linux-project.git
cd Linux-project


2. **Construction de l'image Docker**

À partir du répertoire du projet, construisez l'image Docker en utilisant :

docker build -t customer:latest .

Assurez-vous d'être dans le répertoire contenant le Dockerfile pour exécuter cette commande.

3. **Exécution de l'application**

Avant de démarrer l'application, vérifiez que le port 8050 est ouvert.

Pour lancer l'application, utilisez la commande suivante :

docker run -it -p 8050:8058 customer:latest


Après avoir exécuté cette commande, vous pourrez accéder à l'application via votre navigateur en vous connectant à localhost sur le port 8050.
