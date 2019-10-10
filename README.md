# Charla de GIT

## Vamos a aprender a usar Git

### __git init__
Inicializa el repositorio de Git

### __git status__
Te informa de lo que tienes en el repo local

### __git add \<archivo>__
Para ponerlos en _stage_

### __git rm --cached \<archivo>__
Para quitarlos del _stage_

### __git commit -m "titulo descriptivo del commit" -m "descripción avanzada"__
Para hacer un _commit_

### __git log__
Información sobre los commit

### __git whatchanged__
Te muestra los cambios que ha habido

### __git remote add origin https://github.com/raulsoria98/Charla-Git.git__
Añade el repositorio remoto al que damos el nombre _origin_

### __git remote -v__
Te muestra donde está la rama fetch y la master

### __git push origin master__
Para enviar la rama _master_ al repositorio _origin_

### __git pull origin master__
Trae al repositorio local la rama master de origin

### __git clone \<repositorio remoto>__
Descarga un repositorio

### __git checkout -b \<nombre>__
Crea una nueva rama _nombre_ al repositorio

### __git branch__
Muestra las ramas y en a que estás

### __git switch/checkout \<rama>__
Cambia a la rama _rama_

### __git merge \<rama>__
Une la rama _rama_ a la rama actual

### __git branch -d \<dev>__
Delete de la rama \<dev>

### __git push --delete origin \<dev>__
Elimina la rama \<dev> en el remoto

### __git revert \<numero de comit>
Crea un nuevo commit con la misma version del numero de commit que has metido