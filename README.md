# Smarthome_Energy

## Documentation sur la Gestion d’Énergie dans la Smart House
La gestion de l’énergie est un enjeu crucial dans notre monde moderne. Car elle contribue à la durabilité de notre planète , permet de réduire les coûts de revient de nos factures , garantit la fiabilité des systèmes électriques , assure le bon fonctionnement de tout appareils connectés , améliore le confort des occupants tout en  contribuant au confort et à la qualité de vie. Raison pour laquelle  la gestion de l’énergie est un pilier fondamental pour un avenir durable, économique et fiable.

# Remerciements



# Sommaire 

   1. Introduction et objectifs 

   2. Analyse Fonctionelle 

   3. Analyse technique

   4. Conclusion
      
## 1. Introduction et objectifs 

Un système de gestion de l’énergie domestique est une configuration sophistiquée conçue pour surveiller, contrôler et optimiser la consommation d’énergie au sein d’un foyer grâce à une technologie avancée. Ce système intègre des fonctionnalités telles que le suivi de la consommation d’énergie, le contrôle de la distribution et la gestion à distance.  
  
Son objectif principal est d’aider les propriétaires à gérer efficacement leur consommation d’énergie, conduisant finalement à une réduction des dépenses énergétiques et à une meilleure efficacité énergétique. Particulièrement dans le paysage actuel de transition énergétique, marqué par une dépendance croissante aux sources d’énergie renouvelables, les systèmes de gestion de l’énergie des maisons intelligentes jouent un rôle central dans la promotion de l’intelligence énergétique.

**Objectifs**

* Mesure du Courant Consommé

* Surveillance du Système Électrique

* Automatisation et Contrôle

* Sécurité et Protection

## 2. Analyse fonctionnelle
  

| Fonctionnalité                                                | Statut   |
|---------------------------------------------------------------|:--------:|
| Surveillance de la consommation                                |   🔴     |
| Analyse des habitudes de consommation                         |   🟠     |
| Prédiction de la consommation future                           |   🟡     |
| Contrôle de la distribution                                    |   🔴     |
| Envoi d’alerte en cas de consommation anormale                |   🟠     |
| Interface utilisateur                                         |   🔴     |
| Utilisation à distance                                        |   🔴

                                                      
CODE COULEUR : 

- Très important : 🔴

- Moyennement important : 🟠

- Facultatif : 🟡

### Rôle des fonctionnalités

 - Surveillance de la consommation(mesure et affichage en temps réel de la consommation des appareils) 🔴

- Analyse des habitudes de consommation(identifier les tendances de consommation et fournir des rapports sur la consommation) 🟠

- Prédiction de la consommation future(prédire à l’aide des rapports la consommation puis ajuster la distribution en vue de l’optimisation de la consommation) 🟡

- Contrôle de la distribution(activer ou désactiver l’alimentation de la distribution de certains appareils sur commande ) 🔴

- Envoi d’alerte en cas de consommation anormale puis envoi de recommandations pour la régulation 🟠

- Interface utilisateur(création d’une interface permettant à l’utilisateur de paramétrer ses préférences) 🔴

- Utilisation à distance(permet de contrôler la distribution en électricité par internet à travers un site ou une application) 🔴

## 3. Analyse technique

### 3.1. Liste du matériel utilisé

| **COMPOSANTS**                          | **QUANTITE** |
|-----------------------------------------|:------------:|
| Carte Arduino                           |      1       |
| Module horloge (DS1302)                 |      1       |
| Relais (220V - 12V)                     |      4       |
| Pince ampèremétrique ACS712             |      4       |
| Carte SD pour stocker les données (32)  |      1       |




* Mesure du Courant Consommé 


