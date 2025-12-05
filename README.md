# Projet_L1Info_Site_Web_Lupin
Licence 1 Informatique - Projet de développement d'un site en HTML 1.0 & CSS (MAI 2025)

---

## Description du projet
Ce projet permet de vous présenter la série Lupin apparu sur Netflix en 2021. On voulait mettre en valeur une série française porter par des acteurs français reconnu dans le monde du cinéma comme Omar Sy. Il y a aussi des scènes qui ont été tournés dans la région, notamment à  Etretat.

## Maquette
Les maquettes sont des visuels crée à l'aide de Canva pour visualiser à quoi pourrait ressembler notre site et se mettre d'accord sur la direction artistique du projet.

## Réalisation du projet
On a très tôt générer la base du site avec panndoc ce qui nous a conduit à faire quelques modifications au fur et à mesure de l'évolution du projet. On a notamment ajouté les classes, corrigé les bugs de conversions de pandoc.

## Auteurs
- Corentin Houllier
  - GitHub : [@Kodentix](https://github.com/kodentix/)
- Edouard Lecocq
  - GitHub : [@EdouardInfo](https://github.com/EdouardInfo/)

## Structure du projet

```
ProjetDocWeb/
├── MarkDown/
│   ├── index.md
│   ├── personnages.md
│   ├── themes.md
│   ├── saisons.md
│   ├── sources.md
│   ├── annexe.md
│   ├── metadata.yml
│   ├── template.html
│   ├── sortiepandoc/
│   └── pandoc-script.txt
├── HTML/
│   ├── index.html
│   ├── personnages.html
│   ├── themes.html
│   ├── saisons.html
│   ├── sources.html
│   └── annexe.html
├── CSS/
│   └── lecocqhoullier.css
└── Images/
    ├── AssaneTab.png
    ├── ClaireTab.png
    ├── fresque-lupin.png
    ├── GuediraTab.png
    ├── lupins1.png
    ├── lupins2.png
    ├── lupins3.png
    ├── PelligriniTab.png
    └── question.png
```

## Structure des pages

Chaque page du site est composée de 4 blocs principaux :
- **Bloc de menu (#menu)** : Barre de navigation entre toutes les pages du site.
- **Bloc de titre (#titre)** : Affiche le nom du site et le titre de la page.
- **Bloc de contenu (#contenu)** : Présente les informations de la page courante.
- **Bloc d'auteurs (#auteurs)** : Qui permet d'ajouter notre crédit.

## Pages du site

1. **index.html** : Page d'accueil, de mise en valeur de la série.
2. **personnages.html** : Présentation des personnages principaux de la série.
3. **themes.html** : Analyse des thèmes abordés dans la série.
4. **saisons.html** : Affiche de chaques "saisons" qui sont en réalité des parties de la série.
5. **sources.html** : Références et sources utilisées pour réaliser le site.
6. **annexe.html** : Informations complémentaires sur l'univers autour d'Arsène Lupin.

## Format utilisé

- **HTML** : Format XHTML 1.0 Strict.
- **CSS** : Un seul CSS utilisé pour toutes les pages du site.
- **Markdown** : Création du contenu et structuration du site.
- **Pandoc** : Conversion du Markdown en HTML à l'aide de lignes de commande.

## Méthodologie de travail

Le projet a été réalisé en trois étapes principales :

1. **Prototypage** : Structure des pages HTML créée à partir de fichiers Markdown convertis avec Pandoc
2. **Stylisation** : Création et application de la feuille de style CSS
3. **Finalisation** : Modification légère de contenu et peaufinement des pages html.

## Utilisation de Pandoc

Les fichiers Markdown sont convertis en HTML à l'aide de Pandoc. Le script de conversion est disponible dans le fichier `MarkDown/pandoc-script.txt`. La conversion utilise :
- Un template principal (`template.html`)
- Le fichier de métadonnées (`metadata.yml`)
- Les fichiers Markdown sources (`.md`)
