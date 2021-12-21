# kubernetesProjet
## Déployez Wordpress à l’aide de manifests

_Déployez wordpress à l’aide des étapes suivantes:_
```doc
• Créez un deployment mysql avec un seul réplica.
• Créez un service de type clusterIP pour exposer votre pod mysql.
• Créez un deployment wordpress avec les bonnes variables d’environnement pour se connecter à la base de données mysql.
• Votre deployment devra stocker les données de wordpress et de mysql sur un volume mounté dans le (wordpress : /data) et (mysql : /db-data) de votre nœud.
• Créez un service de type nodeport pour exposer le frontend wordpress.
• Utiliser les manifests pour réaliser cet Projet
```
![Screenshot](assets/meetre-à-jour-wordpress-régulièrement.jpg)

