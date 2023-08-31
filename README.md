# DEMO 2

Creamos un repositorio de github directamente desde nuestro código, usando git en RStudio. Para ello creamos una carpeta (prueba2-repo) que convertimos en repositorio de git con "git init".

## Notas 

Después de crear el repositorio no puedes hacer un add, commit, push y listo, lo tienes en github, porque no va a encontrar ese repositorio en github (ya q no existe aun). Hace falta crear esa conexión :

- Creando un nuevo repositorio en github q se llame prueba2-repo. Luego haremos git remote add prueba2-repo https://github.com/paulaminguez/prueba2-repo.git and then push using the remote name "git push prueba2-repo"...


Para ver las ramas del repo --> git branch
Para crear nuevo branch --> git checkout -b feature-readme-instructions
Para cambiar a otra branch --> git checkout master

Para fusionar cambios de dos ramas desde la rama donde se quiere actualizar (e-g- master <- feature))--> 
op.1.) git merge feature-readme-instructions

Para fusionar cambios de dos ramas desde la rama donde se hacen los cambios (e-g- feature-readme-instructions -> master))-->
(esto sería el botón de compare and pull request de github)
op.1.) git push master