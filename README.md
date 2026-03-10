# 19 Pool - Piscine C 🏊‍♂️

Bienvenue dans mon dépôt recensant mon travail lors de la **Piscine** de l'école 19 (Réseau 42). 
Ce projet regroupe l'ensemble des exercices, rushs et projets réalisés lors de cette période d'apprentissage intensif du langage C et des bases de l'environnement Unix (Shell).

## 🗂️ Structure du Dépôt

Le dépôt est organisé par jours/thématiques selon la structure classique de la Piscine :

### 🐚 Shell (S00 - S01)
Exercices d'apprentissage des commandes Unix, de la manipulation de l'arborescence des fichiers, des permissions et des scripts shell de base.

### 💻 Langage C (C00 à C13)
Découverte et apprentissage progressif du langage C :
* **C00 à C04** : Affichage, boucles, conditions, pointeurs et manipulation de chaînes de caractères.
* **C05 à C07** : Mathématiques appliquées, récursivité et allocation dynamique de mémoire (`malloc`, `free`).
* **C08 à C13** : Création de headers, utilisation de macros, structures, listes chaînées et arbres.

### 🏃‍♂️ Rushs (R00, R01, R02)
Projets de groupe réalisés en temps limité (le week-end). Ils demandent une organisation en équipe et la résolution de défis algorithmiques.

### 🟥 BSQ (Biggest Square)
Le projet de fin de Piscine. Le programme prendra en paramètre une carte (composée de cases vides et d'obstacles), et devra trouver et afficher le plus grand carré possible.
* Localisation : Dossier `BSQ/`
* Compilation : Via le `Makefile` présent dans le dossier.

## 🛠️ Compilation et Exécution

Pour compiler la plupart des exercices en C, vous pouvez utiliser gcc avec les flags stricts de l'école :

```bash
gcc -Wall -Wextra -Werror nom_du_fichier.c
```

Pour le projet **BSQ**, un `Makefile` est fourni. Naviguez dans le dossier et lancez `make` :

```bash
cd BSQ
make
./bsq [chemin_vers_map]
```

## 📜 La Norme (Norminette)

Tous les scripts et programmes C présents dans ce dépôt ont été écrits pour être conformes à la **Norme** stricte de l'école 42/19. Cela inclut (entre autres) :
* Maximum 25 lignes par fonction.
* Pas de déclarations de variables en dehors du début de la fonction.
* Indentation stricte avec des tabulations.
* Interdiction d'utiliser des boucles `for`, `do...while` ou des `switch`.

---
*Développé pendant la Piscine 19.*
