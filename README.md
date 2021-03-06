## <a href="http://www.insa-toulouse.fr/" ><img src="http://www.math.univ-toulouse.fr/~besse/Wikistat/Images/Logo_INSAvilletoulouse-RVB.png" style="float:left; max-width: 80px; display: inline" alt="INSA"/> |  [*Mathématiques Appliquées*](http://www.math.insa-toulouse.fr/fr/index.html), [`Science des Données`](http://www.math.insa-toulouse.fr/fr/enseignement.html) 

# Science des Données & Statistique

### [Lire plus...](http://www.math.univ-toulouse.fr/~besse/Wikistat/pdf/st-lm-Intro-Stat_SD.pdf)

Schématiquement, la **Science des Données** est définie autour d'une *agrégation de compétences* en Informatique (langage comme [R](href="https://cran.r-project.org/) et [Python](https://www.python.org/) , gestion des données, calcul parallèle...), Statistique (exploration, estimation test, modélisation, prévision) Apprentissage Machine (prévision), Mathématiques (probabilités, optimisation, analyse fonctionnelle, graphes...). 

Son **apprentissage** est acquis par l'intermédiaire de scénarios d'analyse de données réelles, ou *tutoriel*, présentés sous forme de *calepins* ([*jupyter notebooks*](http://jupyter.org/)) en [R](href="https://cran.r-project.org/) ou [Python](https://www.python.org/). Voir à ce sujet le [livre de référence](https://www.inferentialthinking.com/) du cours [*Fondations of Data Science*](http://data8.org/) de l'UC Berkley.

Cette **pratique** est **indispensable** mais masque les *aspects théoriques* (mathématiques, statistiques): une *formule* est remplacée par un commande ou fonction en Python ou R, une *démonstration* par l'exécution d'exemples dans un calepin.

Pour offrir de la *profondeur*, plus de compréhension, à cette (auto)-formation, les calepins renvoient (liens hypertextes) systématiquement à des **vignettes "théoriques"**  du site [wikistat.fr](http://wikistat.fr/) exposant en détail (cours) les méthodes et algorithmes concernés.

Il ne s'agit pas simplement de pouvoir exécuter une méthode, un algorithme, il est important d'en **comprendre les propriétés**, conditions d'utilisation et limites.

# Saison 3 [*Apprentissage Machine / Statistique*](\http://wikistat.fr)

### [Introduction plus détaillée](http://www.math.univ-toulouse.fr/~besse/Wikistat/pdf/st-m-Intro-ApprentStat.pdf)...

## Objectifs

Cette saison est consacrée à l'apprentissage des principales méthodes et algorihtmes d'apprentissage (supervisé) machine ou statistique listées dans les épisodes successifs.

## Prérequis
Avoir acquis les compétences des épisodes précédents ou revenir à leur saison:

- [Initiation à R](https://github.com/wikistat/Intro-R)
- [Initiation à Python](https://github.com/wikistat/Intro-Python)
- Formation aux [outils statistiques de base](https://github.com/wikistat/StatElem)
- [Exploration Statistique pour la Science des Données](https://github.com/wikistat/Exploration). Cette saison intègre les algorithmes de classification non-supervisée (*clustering*).

## <FONT COLOR="Red"> Déroulement de l'UF *Apprentissage Machine* </font>

- Consulter le [document ](https://github.com/wikistat/Intro-R) (`README`) pour installer le noyau `IRkernel` afin de pouvoir utiliser R dans Jupyter.
- Lors de chaque séance / **épisode**, exécuter les calepins "fil rouge" ([prévision des pics d'ozone](https://github.com/wikistat/Apprentissage/tree/master/Pic-ozone)) en *R et Python3* en se référant, si nécessaire aux vignettes, (liens hypertextes) à chaque étape. 
- Traiter également le projet commun entre les UFs. 
- **Rendre par binome et pour le 22/12/2017 18H** le calepin Python commenté du projet avec un résumé substanciel de la démarche et des résultats obtenus.
- **Examen** le 10/01/2018 9h30 sur un thème analogue aux autres calepins disponibles.
- Remarques
	- le calepin [patrimoine INSEE](https://github.com/wikistat/Apprentissage/tree/master/Patrim-Insee) de calcul du score d'appétence de l'assurance vie est un exemple typique de marketing quantitatif ou Gestion de la Relation client à réaliser par celles-ceux à la recherche d'un stage dans ce domaine.
	- Les [`exemples jouets`](https://github.com/wikistat/Apprentissage/tree/master/ExemplesJouet) servent aussi de *bac à sable* pour expérimenter chaque méthode. 
	- D'autres scénarios (exemples et cas d'usage ci-dessous), basés sur des jeux de données complets / complexes sont et seront disponibles dans ce même dépôt.

## Pour aller plus loin
Aborder la *Science des Données* avec les 

- [Technologies des grosses data](https://github.com/wikistat/Ateliers-Big-Data) (Hadoop Spark, XGBoost, Keras...)

## Épisodes 
Les [calepins]((https://github.com/wikistat/Apprentissage/tree/master/Pic-ozone)) python et R "fil rouge", sont découpés en 5 épisodes listés ci-dessous. 

Pour chaque épisode, **suivre le cours** ou consulter les vignettes et exécuter les parties correspondantes des calepins. 

- Pic d'ozone: [calepin en R](https://github.com/wikistat/Apprentissage/blob/master/Pic-ozone/Apprent-R-Ozone.ipynb)
- Pic d'ozone: [calepin en Python](https://github.com/wikistat/Apprentissage/blob/master/Pic-ozone/Apprent-Python-Ozone.ipynb)

### Épisode 1 
- [Introduction: Apprentissage Machine pour la Science des données](http://wikistat.fr/pdf/st-m-Intro-ApprentStat.pdf)
- [Qualité de prévision, risque](http://wikistat.fr/pdf/st-m-app-risque.pdf)
- [Rappels sur le modèle linéaire général](http://wikistat.fr/pdf/st-m-app-rlogit.pdf) (modèles gaussien et binomial)

### Épisode 2
- [Analyse discriminante, *k* plus proches voisins](http://wikistat.fr/pdf/st-m-app-add.pdf)
- [Arbres binaires de décision](http://wikistat.fr/pdf/st-m-app-cart.pdf)

### Épisode 3
- [Réseaux de neurones](http://wikistat.fr/pdf/st-m-app-rn.pdf), introduction au *deep learning*
- [Agrégation de modèles](http://wikistat.fr/pdf/st-m-app-agreg.pdf): *boosting, random forest*

### Épisode 4
- [Régression PLS](http://wikistat.fr/pdf/st-m-app-sparse-pls.pdf)
- [*Support Vector Machine*](http://wikistat.fr/pdf/st-m-app-svm.pdf)
- [Synthèse](http://wikistat.fr/pdf/st-m-app-conclusion.pdf)

### Épisode 5
- [Imputation de données manquantes](http://wikistat.fr/pdf/st-m-app-idm.pdf)
- [Détection de défaillances](http://wikistat.fr/pdf/st-m-app-anomalies.pdf) (*One class Classification, noveltry detection*) 


## Cas d'usage (sujets d'examen)

- [`ExemplesJouet`](https://github.com/wikistat/Apprentissage/tree/master/ExemplesJouet) illustratifs sur données simulées:
	- Discrimination binaire en dimension 2: [`Nuages gaussiens`](https://github.com/wikistat/Apprentissage/tree/master/ExemplesJouet/Apprent-R-Clouds.ipynb) en R ou [`Blobs`](https://github.com/wikistat/Apprentissage/tree/master/ExemplesJouet/Apprent-Python-Blobs.ipynb) de Scikit-learn. Dessiner les frontières des classes selon les méthodes utilisées, rôle du paramètre de compexité;
	- Régression polynomiale en R, optimisation de la complexité (degré) par *Cp* de Mallows, régularisation *ridge* ou lasso.
- [`Pic d'ozone`](https://github.com/wikistat/Apprentissage/tree/master/Pic-ozone) Prévision de la concentration (régression) ou de dépassementdu seuil (discrimination binaire) légal d'ozone par la plupart des méthodes d'apprentissage. En R et en Python.
- [`AdultCensus`](https://github.com/wikistat/Apprentissage/blob/master/Adult-Census/) Données de sondage de 32561 citoyens américains. Prévision de la variable dépassement d'un seuil de revenu à partir de variables socio économiques.
- [`Diagnostic coronarien`](https://github.com/wikistat/Apprentissage/tree/master/Diag-coro) Prévision du risque de coronopathie (discrimination binaire) par les principales méthodes d'apprentissage en R. Optimisation avec la librairie [`caret`](http://topepo.github.io/caret/index.html), introduction à l'implémentation de [`xgboost`](https://xgboost.readthedocs.io/en/latest/) en R.
- [`GRC-carte_Visa`](https://github.com/wikistat/Apprentissage/tree/master/GRC-carte_Visa). Exemple de Gestion de la Relation Client (GRC). Prévision du score d'appétance de la carte visa premier; comparaison des méthodes.
- [`Patrimoine INSEE`](https://github.com/wikistat/Apprentissage/tree/master/Patrim-Insee) La gestion de la relation client appliquée à des données d'enquête INSEE. Recherche d'un score d'appétence pour l'assurance vie.
- [`Pourriels`](https://github.com/wikistat/Apprentissage/blob/master/Spam/) détection de pourriels dans une base de courriers électroniques.
- [`NIR`](https://github.com/wikistat/Apprentissage/blob/master/NIR/) Approches utilisées en chimiométrie: modélisation et prévision à partir de mesures spectrométriques dans le proche infra-rouge: taux de sucre dans une pâte à gâteaux et taux de graisse dans des échantillons de viande.




