# Git

Un pequeño vistazo

## Comandos básicos
- __git checkout__ : cambiar de commit o rama

- __git branch__ : indica la rama en la que se trabaja

- __git branch <nombre_rama>__ : crea nueva rama 


- __git branch -d <nombre_rama>__ : borrar rama
    * Eliminar de remoto git push origin <nombre_rama>

- __git checkout -b <nombre_rama>__ : crea rama y cambia a esa rama

- __git diff <hash1> <hash2>__: cambios de un commit a otro.

- __git log --graph__ : aŕbol del proyecto

- __git commit --amend__  o __git commit --amend -m <mensaje>__ : Corregir commit en repo local

- __git tag <tag> <hash>__ : Agregar tag al commit

- __git tag -d <tag>__ : Quitar tag al commit

- __git pull origin <nombre_rama>__ : traer cambios de repo remoto a repo local

- __git blame <archivo>__ : quien ha hecho los cambios y en que momento
