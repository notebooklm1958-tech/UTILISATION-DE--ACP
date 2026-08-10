# UTILISATION-DE--ACP
vEntrée : Jeu de données (Matrice X), Nombre de composantes à conserver (K)
Sortie : Jeu de données transformé (Dimension réduite)

Étape 1 : Standardiser les données
    - Calculer la moyenne de chaque variable[cite: 10].
    - Soustraire la moyenne de chaque valeur[cite: 10].
    - (Optionnel) Diviser par l'écart-type pour mettre les données à l'échelle.

Étape 2 : Calculer la matrice de covariance
    - Utiliser les données standardisées pour obtenir la matrice de covariance[cite: 9, 11].

Étape 3 : Calculer les valeurs propres et les vecteurs propres
    - Extraire les valeurs propres (eigenvalues) et les vecteurs propres (eigenvectors) 
      à partir de la matrice de covariance.

Étape 4 : Trier et sélectionner les composantes
    - Trier les valeurs propres par ordre décroissant[cite: 10].
    - Réorganiser les vecteurs propres correspondants selon cet ordre[cite: 10].
    - Sélectionner les K premiers vecteurs propres[cite: 10].

Étape 5 : Transformer le jeu de données
    - Projeter le jeu de données d'origine sur les K vecteurs propres sélectionnés[cite: 10].oici le pseudo-code pour l'Analyse en Composantes Principales (PCA):
