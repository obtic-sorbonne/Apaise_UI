### apaise
## Apaise UI — Outil d'annotation et d'analyse émotionnelle d'entretiens psychiatriques

Cette application web est conçue pour l'annotation manuelle et l'analyse comparative d'entretiens psychiatriques transcrits. 

Elle permet d'importer des transcriptions au format texte, de les segmenter automatiquement en tours de parole (patient / psychiatre), puis d'annoter chaque tour patient avec des émotions primaires et secondaires (roue de Plutchik), une polarité, une intensité, un type d'annotation (littérale ou inférée) et un commentaire libre. 

Un module d'exploration permet de filtrer et rechercher dans le corpus, de visualiser les concordances (KWIC) et d'exporter les résultats en CSV. 

Un module de clustering (TF-IDF + k-means + projection PCA) regroupe les entretiens par profil émotionnel. 

La page de gestion des annotations permet de charger plusieurs fichiers JSON annotés, de calculer des métriques d'accord inter-annotateurs (Cohen's Kappa, Krippendorff's Alpha, Jaccard), de visualiser les désaccords sous forme de heatmap, et de produire un fichier réconcilié tour par tour. 

L'ensemble fonctionne entièrement dans le navigateur, comme une application web monopage en HTML/CSS/JavaScript vanilla, sans framework ni serveur, avec Chart.js comme seule dépendance externe.

Version en ligne: https://obtic-sorbonne.github.io/Apaise_UI/
