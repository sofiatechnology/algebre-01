# MATH 01

## Un Guide Simple en Mathématiques

Ce projet contient un guide de mathématiques simple et accessible, conçu pour aider les étudiants à comprendre les concepts mathématiques fondamentaux.

## Fonctionnalités

- Explications claires des concepts mathématiques
- Exemples pratiques et exercices
- Formules essentielles bien présentées
- Structure progressive adaptée à l'apprentissage

## Prérequis

Pour compiler ce projet, vous aurez besoin de:

- Une distribution LaTeX (comme TeX Live ou MiKTeX)
- Un lecteur PDF (comme Evince, Adobe Reader, ou Preview)

## Installation

### Cloner le projet

```bash
git clone https://github.com/sofiatechnology/math-01.git
```

### Accéder au répertoire du projet

```bash
cd math-01
```

## Compilation

### Générer le PDF à partir des fichiers source LaTeX

```bash
pdflatex main.tex
```

Pour une table des matières et des références correctes, vous devrez peut-être exécuter la commande plusieurs fois:

```bash
pdflatex main.tex
pdflatex main.tex
```

### Visualiser le document généré

#### Sous Linux

```bash
evince main.pdf
```

#### Sous macOS

```bash
open main.pdf
```

#### Sous Windows

```bash
start main.pdf
```

## Structure du projet

```
math-01/
├── main.tex         # Fichier principal LaTeX
├── chapters/        # Dossier contenant les chapitres
├── images/          # Dossier contenant les images
├── bibliographie.bib # Références bibliographiques
└── README.md        # Ce fichier
```

## Contribution

Les contributions sont les bienvenues! N'hésitez pas à ouvrir une issue ou à soumettre une pull request.
