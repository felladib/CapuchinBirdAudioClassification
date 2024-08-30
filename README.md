# Capuchin Bird Audio Classification

## Description

Ce projet consiste à classifier les vocalisations des oiseaux, spécifiquement celles de l'espèce Capuchinbird, à partir de données audio. L'objectif est de distinguer les vocalisations de cette espèce parmi d'autres sons présents dans les enregistrements. Pour cela, nous avons utilisé un modèle de réseau de neurones convolutif (CNN) appliqué sur des spectrogrammes générés à partir des enregistrements audio.

## Processus du Projet

1. **Prétraitement des données audio :** Les enregistrements audio sont convertis en spectrogrammes, qui sont des représentations visuelles de la fréquence du son au fil du temps.
  
2. **Génération des spectrogrammes :** Les spectrogrammes sont générés à partir des fichiers audio, capturant les caractéristiques spectrales importantes pour la classification.
  
3. **Modèle CNN :** Un modèle de réseau de neurones convolutif (CNN) est conçu et entraîné sur ces spectrogrammes pour apprendre à distinguer les vocalisations du Capuchinbird des autres sons.
  
4. **Classification binaire :** Le modèle effectue une classification binaire, déterminant si un enregistrement contient ou non les vocalisations de l'espèce ciblée.

## Technologies Utilisées

- **Python :** Langage de programmation principal pour le traitement des données et le développement du modèle.
- **Librosa :** Bibliothèque utilisée pour le traitement audio, y compris la conversion des fichiers audio en spectrogrammes.
- **TensorFlow/Keras :** Framework utilisé pour construire et entraîner le modèle CNN.
- **Google Colab :** Plateforme utilisée pour exécuter le code et entraîner le modèle, facilitant l'utilisation de GPU pour l'accélération du calcul.
- **Kaggle :** La plateforme utilisée pour obtenir le dataset et expérimenter avec le modèle.

## Installation et Exécution

Pour exécuter ce projet sur Google Colab, suivez les étapes ci-dessous :

1. **Accédez au notebook Colab :** `https://colab.research.google.com/drive/1KxXtcBSm4-p9GM9M434RrmSgm-u9l5-M#scrollTo=_HtFl5ab3boD`
2. **Téléchargez ou montez le dataset :** Assurez-vous que le dataset est disponible dans votre environnement Colab.
3. **Exécutez le notebook :** Exécutez chaque cellule pour prétraiter les données, générer les spectrogrammes, entraîner le modèle, et évaluer les résultats.

## Résultats

Le modèle a été capable de classifier les vocalisations de l'espèce Capuchinbird avec une précision satisfaisante, démontrant l'efficacité des CNN pour la classification d'images spectrales dérivées de données audio.

## Contributions

Les contributions sont les bienvenues ! Si vous souhaitez améliorer ce projet ou l'étendre à d'autres espèces d'oiseaux, n'hésitez pas à soumettre une pull request ou à ouvrir une issue.
