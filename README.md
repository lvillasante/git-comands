# README #

This README would normally document whatever steps are necessary to get your application up and running.

para templates de consulta bolivia

### What is this repository for? ###

* Quick summary
* Version
* [Learn Markdown](https://bitbucket.org/tutorials/markdowndemo)

### How do I get set up? ###

* Summary of set up
* Configuration
* Dependencies
* Database configuration
* How to run tests
* Deployment instructions

### Contribution guidelines ###

* Writing tests
* Code review
* Other guidelines

### Who do I talk to? ###

* Repo owner or admin
* Other community or team contact



### Add y commit ### 

Registrando cambios de directorio de trabajo al Storage (index) => add
Incluir los cambios en el HEAD local => commit
Enviar los cambios al repositorio remoto => push

git add .
git add <nombre de archivo>
git commit -am "comentario"
git push origin master
git push origin <nombre del branch>


### Actualizar repositorio ##
git pull

$cuando tienes cambios locales y necesitas actualizr el repo con archivos remotos
git stash
git pull
git stash pop

### Comados GIT para Ramas ###

$Ver ramas locales
git branch

$Ver ramas remotas
git branch -a

$Obtener Ramas remotas
git pull
git remote show origin
git checkout --track origin/serverfix
git checkout -t origin/serverfix
$Otro ejemplo
git checkout --track se featuring/seleccion origin/featuring/seleccion

$Cambiando de rama
git checkout master


