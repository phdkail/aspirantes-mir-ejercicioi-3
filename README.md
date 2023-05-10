# aspirantes-mir-ejercicioi-3
S3 – Git Branches

Este ejercicio te permite practicar el uso de dos ramas en Git (main y develop) y cómo fusionar cambios entre ellas. Al trabajar en la rama develop, puedes realizar cambios en el código sin afectar la rama principal main. Luego, cuando los cambios están listos para ser integrados en la rama main, puedes fusionar los cambios usando el comando git merge. Esto ayuda a mantener un flujo de trabajo ordenado y evita que los cambios no deseados se introduzcan en la rama principal.

Misión

1.	Crea un repositorio de Git vacío con el comando git init.
Inicio Git Bash, ejecuto el comando cd /C/Users/Acer/Downloads/MakeItReal/Ejercicios para ubicarme en mi carpeta de trabajo, luego ejecuto el comando indicado
Git init
2.	Crea un archivo llamado index.html y agrega algo de contenido.
Procedo a crear el archivo usando el comando touch
Touch index.html
3.	Agrega el archivo index.html al área de preparación con el comando git add index.html. y haces commit en esa rama con su respectivo mensaje.
Procedo a emplear el comando indicado
Git add index.html
Luego procedo con el commit
Git status
4.	Crea una nueva rama llamada develop con el comando git branch develop.
Con git Branch puedo ver las ramas que tengo, asimismo puedo crear una rama con git checkout -b develop
5.	Cambia a la rama develop con el comando git checkout develop.
Con el comando indicado procedemos a cambiar de rama
Git checkout -b develop
Podemos cambiar de rama con el comando
Git checkout -m develop
Y automáticamente quedará indicado en que rama estamos ubicados
6.	Crea un archivo llamado .env y agrega algo de contenido sensible (PASSWORD=1234).
Usamos el comando touch para crear el archivo indicado
Touch env
7.	Crea un archivo llamado .gitignore en la raíz del repositorio.
Usamos el comando touch
Touch gitignore
8.	Abre el archivo .gitignore y agrega una línea que indique que Git debe ignorar el archivo .env. La línea debería ser así: .env.
En el VSCode colocamos la línea indicada .env.
9.	Agrega el archivo .gitignore al área de preparación con el comando git add .gitignore.
Procedemos a ejecutar lo indicado
Git add gitignore
10.	Edita el archivo index.html para hacer algunos cambios y agrega esos cambios al área de preparación con el comando git add index.html.
En VSCode edito el archivo index.html, luego regreso al Git Bash y procedo a agregar los cambios
Git add index.html
11.	Haz un commit con los cambios en la rama develop usando el comando git commit -m "Cambios en la rama develop".
Procedemos con el comendo en mención
Git commit -m “Cambios en la rama develop”
Veremos los cambios que han sido efectuados
12.	Cambia de vuelta a la rama main con el comando git checkout main.
Procedemos con el comando
Git checkout main
13.	Muestra el contenido del archivo index.html para comprobar que los cambios hechos en la rama develop no están presentes.
Visualizamos en archivo index.html dentro del VSCode
14.	Fusiona la rama develop en la rama main usando el comando git merge develop. Los cambios realizados en la rama develop se integrarán en la rama main.
Usamos el comando
Git merge develop
15.	Muestra el contenido del archivo index.html de nuevo para comprobar que los cambios realizados en la rama develop ahora están presentes en la rama main.
Procedemos a visualizar nuevamente el contenido de index.html en el VSCode
16.	Verifica que el archivo .env no está incluido en el repositorio ejecutando el comando git ls-files --other --ignored --exclude-standard.
Usamos el comando list
Ls
Veremos que no figura el archivo en mención
17.	Publicar a Github en un repositorio llamado aspirantes-mir-ejercicioi-3.
Procedemos a crear el repositorio
18.	Enviar el link del repositorio en Github a esta misión.
Procedemos a enviar el link a través del Classroom

Bonus

Este ejercicio te permite practicar cómo clonar un repositorio existente, cómo crear una nueva rama a partir de la rama principal y cómo fusionar los cambios realizados en la nueva rama de vuelta a la rama principal.

1.	Clona un repositorio existente con el comando git clone <url del repositorio>.
a
2.	Cambia al directorio del repositorio clonado con el comando cd <nombre del repositorio>.
a
3.	Crea una nueva rama llamada nueva-funcionalidad a partir de la rama principal con el comando git checkout -b nueva-funcionalidad. Este comando crea una nueva rama y automáticamente cambia a ella.
a
4.	Crea un nuevo archivo llamado nuevo-archivo.txt en el directorio raíz del repositorio y agrega algo de contenido.
a
5.	Agrega el archivo nuevo-archivo.txt al área de preparación con el comando git add nuevo-archivo.txt.
a
6.	Haz un commit con los cambios en la rama nueva-funcionalidad usando el comando git commit -m "Agregado nuevo archivo para la nueva funcionalidad".
a
7.	Cambia de vuelta a la rama principal con el comando git checkout main.
a
8.	Muestra el contenido del archivo nuevo-archivo.txt para comprobar que los cambios realizados en la rama nueva-funcionalidad no están presentes.
a
9.	Fusiona la rama nueva-funcionalidad en la rama main usando el comando git merge nueva-funcionalidad. Los cambios realizados en la rama nueva-funcionalidad se integrarán en la rama main.
a
10.	Muestra el contenido del archivo nuevo-archivo.txt de nuevo para comprobar que los cambios realizados en la rama nueva-funcionalidad ahora están presentes en la rama main.
A
