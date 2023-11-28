+++
title = 'Premier cours '
date = 2023-11-14T14:50:36+01:00
draft = false
+++

## Mon premier cours 

Ici, je vais vous expliquer mon expérience. Je ne suis pas développeur, je travaille dans le domaine de l'informatique en tant que Product Owner. Je me mets parfois à coder pour comprendre comment fonctionnent Hugo et GitHub.

Dans ce contexte, nous allons utiliser un thème : Awake. Il est très simple en apparence et en code. 

Le thème génère de l'HTML et du CSS. Notre objectif sera d'ajouter des surcouches de code afin de pouvoir le personnaliser à notre goût.

C'était le but de notre exercice. L'article que vous lisez a été généré par le développeur. Il suffit d'utiliser la commande hugo new posts/.

J'ai découvert un outil collaboratif pour un site statique. Très pratique pour avoir un environnement identique et le même rendu pour tout le monde.

Alors comment est-ce que l'on débute ? 

On installe Git et Hugo :

```
install git
```
```
install hugo
```

Ensuite, on commence l'installation du site : 

```
hugo new site quickstart
cd quickstart
git init
git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke
echo "theme = 'ananke'" >> hugo.toml
hugo server
```

ici nous avons installé notre site avec le thème awake. Mais si vous souhaitez le changer :  [Thèmes](https://jamstackthemes.dev/ssg/hugo/).

On lance le server pour qu'il apparaisse sur votre navigateur : 
```
hugo server -D
```
Généralement il se lance sur le port localhost:1313.

Maitenant, nous allons créer un premier post : 

```
hugo new posts/mon-nouvel-article.md
```
Voilà, vous avez une base pour débuter !

Si on récapitule on a :
- Installé Hugo et GitHub
- Installé un site statique grâce à ces outils
- Lancé un site avec le thème Awake
- Créer un premier post

on continue ? 