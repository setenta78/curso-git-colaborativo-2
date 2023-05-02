# Curso Git Desarrollo Avanzado

Este es un curso de **GIT Desarrollo Avanzado**

* GitLens
* LiveServer


## Codigo PHP
```php
$variable = "contenido"
```

## Codigo JS
```js
 let variable = "curso git"
```
## Que pasa con el repositorio

```bash
git init
```
## Primera vez que inicio con Git
* Vincular repo:

Con un usuario y un correo

Al colocar global, todos los repositorios se van a crear con este usuario y correo

```bash
git config --global user.name "setenta78"
```

Al colocar local, su repositorio local se creara con este usuario y correo

```bash
git config --local user.name "setenta78"
```

Al colocar global, todos los repositorios se van a crear con este usuario y correo

```bash
git config --global user.email "dennis.quezada@gmail.com"
```

Al colocar local, su repositorio local se creara con este usuario y correo

```bash
git config --local user.email "dennis.quezada@gmail.com"
```

Para validar se usa el comando

```bash
git config --global --get-regexp user
```


## Que paso del working directory al Staging Area

git add Readme.md

git add .

**Esto sirve para abarcar toda la caperta del working area**

**IMPORTANTE**: Git no versiona carpetas vacias.

Para que versione la carpeta vacia tengo que crear un archivo llamado **.gitkeep** dentro de la carpeta vacia.


## Programas para versionado

GitKraken - https://www.gitkraken.com/  -Gratis/Paga

Github Desktop - https://desktop.github.com   -Gratis

Sourcetree - https://www.sourcetreeapp.com

## Creacion de repos

2 Nombres magicos


* El de la cuenta git que permite crear un readme.md para hacer una carta de presentacion setenta78/setenta78
* Y el que permite crear un hosting para subir mi proyecto setenta78/setenta78.github.io




