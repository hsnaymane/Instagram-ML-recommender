🌟 Instagram ML Recommender
Ce projet implémente un système de recommandation de contenu inspiré du fonctionnement d’Instagram. Il utilise une base de données MySQL réelle (utilisateurs, posts, interactions) et des techniques de machine learning pour proposer des posts personnalisés à chaque utilisateur.
​

Le cœur du système repose sur :

Une matrice user–post construite à partir des likes réels

La similarité cosinus pour mesurer la proximité entre profils utilisateurs

Un modèle Random Forest pour prédire la probabilité qu’un utilisateur aime un post

L’application propose une interface graphique développée avec Tkinter, affichant :

Un champ pour saisir le nom d’utilisateur

Les utilisateurs les plus similaires

Une galerie scrollable de posts recommandés (image, titre, description, score ML)

Ce projet illustre concrètement comment combiner base de données, data science et machine learning pour créer un moteur de recommandation complet de bout en bout.
​