Détection de Visages avec Apprentissage Profond

Présentation

Ce projet met en œuvre un système de détection de visages basé sur un réseau de neurones convolutif (CNN). Il utilise TensorFlow pour l'entraînement, OpenCV pour le traitement d'image et Albumentations pour l'augmentation des données.

Prérequis

Avant d'exécuter le projet, installez les dépendances requises :

pip install labelme tensorflow opencv-python matplotlib albumentations

Pipeline du Projet

1. Acquisition et Annotation des Données

Capture d'un ensemble d'images contenant des visages.

Annotation des visages à l'aide de l'outil LabelMe pour générer des boîtes englobantes.

2. Prétraitement des Données

Conversion des annotations en un format compatible avec l'entraînement.

Application de techniques d'augmentation des données (rotation, mise à l'échelle, symétrie, ajustement de luminosité) avec Albumentations.

3. Architecture du Modèle

Implémentation d'un modèle de détection basé sur un réseau de neurones convolutif (CNN) avec TensorFlow.

Possibilité d'utiliser un modèle pré-entraîné pour améliorer la performance (transfer learning).

Optimisation avec des fonctions d'activation et une fonction de coût adaptées.

4. Entraînement et Évaluation

Entraînement du modèle sur les données annotées.

Suivi des performances avec les métriques de perte et d'exactitude.

Validation sur un ensemble de test pour évaluer la capacité de généralisation.

5. Détection de Visages en Temps Réel

Utilisation du modèle entraîné pour la détection de visages sur des flux vidéo en direct.

Exploitation d'OpenCV pour la capture et le traitement des images en temps réel.

Utilisation

Suivez les étapes du notebook pour entraîner et tester le modèle. Adaptez les paramètres selon vos besoins pour améliorer les performances.
