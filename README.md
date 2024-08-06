<p align="center">
<img src="https://mistral.ai/images/logo_hubc88c4ece131b91c7cb753f40e9e1cc5_2589_256x0_resize_q97_h2_lanczos_3.webp" width="100"/>
<img src="https://cdn.iconscout.com/icon/free/png-256/free-python-3521655-2945099.png?f=webp&w=256" width="35"/>
</p>

# Projet de génération de Dataset à partir de mon CV au format JSON

Ce projet vise à générer un grand nombre de variations de données à partir de mon CV au format JSON afin de créer un dataset d'apprentissage pour le FinerTune d'un modèle d'IA.

## Objectif

L'objectif de ce projet est de créer un dataset d'apprentissage suffisamment riche et varié pour permettre à un modèle d'IA de mieux comprendre et d'extraire des informations pertinentes à partir de CV au format JSON.

```bash
 CV
  │   
  └── Extraction en JSON
             │   
             │
    Importation de la data
             │
             └── création des questions types
                   avec reponses associées
                              │   
                              │
  génération des variations ──┘
             │   
             │
     Exportation en JSON
```

## Conclusion

Dans ce notebook, nous avons utilisé le modèle Mistral.ai pour générer 50 variations d'une question donnée et leurs réponses correspondantes. Nous avons enregistré les résultats dans un fichier JSON pour une utilisation ultérieure.

Le résultat est satisfaisant, et permet de générer un grand nombre de variations d'une question et de ses réponses. Cela peut être utile pour l'entraînement de modèles de dialogue ou pour la génération de données de test. Les prochaines étapes consiste à permettre de générer des variations de plusieurs questions en même temps, et de pouvoir les générer en parallèle pour gagner du temps. il faudra aussi pouvoir générer des variations de questions et de réponses en plusieurs langues et centraliser les résultats dans un même fichier JSON.

Ce notebook peut être utilisé comme point de départ pour explorer davantage les capacités du modèle Mistral.ai et pour générer des données de dialogue de haute qualité pour diverses applications. il faut aussi implementer un systeme pour entrainer l'IA sur base de ces données générées.

<u>nb</u>: Il est compliquer de forcer le nombre de 50 variations. Il est possible que le nombre de variations générées soit inférieur à 50. Il faudra donc faire attention à ce point.
