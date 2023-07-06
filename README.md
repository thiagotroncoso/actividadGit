# actividadGit

***1 Investigación básica de Git:***<br>
***a. ¿Qué es Git y para qué se utiliza?<br>
Git es un sistema de control de versiones.esto nos va a servir para trabajar en equipo de una manera mucho más simple y óptima cuando estamos desarrollando software.Con Git vamos a poder controlar todos los cambios que se hacen en nuestra aplicación y en nuestro código y vamos a tener control absoluto de todo lo que pasa en el código, pudiendo volver atrás en el tiempo, pudiendo abrir diferentes ramas de desarrollo, etc.Vamos a poder trabajar en equipo de una manera muy sencilla y optimizada, de forma que si tenemos dos o tres personas trabajando en ciertas funcionalidades del proyecto y nosotros podemos estar trabajando en nuestra parte del código. Cuando acabamos de desarrollar nuestro código, utilizamos Git para mezclar los cambios con los otros compañeros. De forma que el código se mezcla de manera perfecta sin generar ningún tipo de fallo y de forma rápida.***
<br><br>***b. ¿Cuáles son las principales características de Git?***<br>
 ***las principales características son:proporciona un listado de los archivos llamados Commits, con la fecha en que se modifica el archivo,Tener un control de versiones de los cambios realizados en los archivos de un proyecto,Poder restablecer los cambios, volver atrás en el tiempo,Crear Ramas o Branches,Realizar un mezclado de cambios entre los integrantes que llevan a cabo el Desarrollo del Proyecto etc.***

***c. ¿Qué es un sistema de control de versiones?<br>***
***Los sistemas de control de versiones son software que ayudan a realizar un seguimiento de los cambios realizados en el código a lo largo del tiempo. A medida que un desarrollador edita el código, el sistema de control de versiones toma una instantánea de los archivos. Después, guarda esa instantánea de forma permanente para que se pueda recuperar más adelante si es necesario.***


***d. ¿Cuál es la diferencia entre Git y otros sistemas de control de versiones?<br>***
***A diferencia de las  la mayoría de los sistemas de control de versiones es que git almacena cada versión como una 'instantánea' en lugar de una lista de los cambios realizados en cada archivo.***
<br>***<br>2 Instalación y configuración de Git:<br>***<br>
***a. Investiga cómo instalar Git en diferentes sistemas operativos (Windows, macOS, Linux).
en windows:***<br>
***Descarga el instalador de GIT para Windows.<br>
Una vez que hayas descargado el instalador, haz doble clic sobre el ejecutable para que comience el proceso de instalación y sigue las instrucciones que te aparecerán en pantalla. Al igual que cualquier otro programa, tendrás que dar “Next” (siguiente) en varias ocasiones hasta que aparezca la opción “Finish” (terminar) para completar la instalación.<br>***
***macOS<br>***
***Descarga el instalador oficial para Mac.<br>***
***Sigue las instrucciones que te aparecerán en el programa de instalación.<br>***
***Al finalizar el proceso de instalación del instalador, vuelve a revisar usando el comando git – -version para confirmar si la instalación se ha hecho correctamente.***
***linux<br>***
  ***Abre la terminal y ejecuta los siguientes comandos:<br>***
 ***Sudo apt-get update<br>***
  ***Sudo apt-get install git***
<br><br>***2) Verifica que la instalación se haya hecho correctamente usando el comando:<br> git –versión.
            otra forma es con yum y dnf<br>***
***Abre la terminal y ejecuta los siguientes comandos:***
 ***Sudeo dnf install git***

 ***Sudo yum install git***


***Verifica que la instalación se haya hecho correctamente ejecutando el código: git –versión.***





***b. Explica los pasos para configurar tu nombre de usuario y dirección de correo electrónico en Git.
<br>linux:***
***<br>ejecute los siguientes comandos en la terminal para poder configurar tu correo y nombre de usuario que están asociados a tu cuenta GIT:<br>
git config --global user.name "Tu nombre"***

***git config --global user.email "tu gmail".***


***3 Comandos básicos de Git:***
***<br>a. Investiga los comandos git init, git add, git commit y git status. Explica qué hacen y cómo se utilizan.***
***<br>git init: se utiliza para Inicializar un nuevo repositorio de Git. Si quieres poner un proyecto bajo un control de revisiones, este es el primer comando que debes aprender.***
***<br>git add: se utiliza para mover los cambios del directorio de trabajo al área del entorno de ensayo. Así puedes preparar una instantánea antes de confirmar en el historial oficial.***
***<br>git commit:se utiliza para confirmar la preparación del historial del proyecto. En combinación con git add, define el flujo de trabajo básico de todos los usuarios de Git.***
***<br>git status: se utiliza para mostrar el estado del directorio en el que estás trabajando y la instantánea preparada. Lo mejor es que lo ejecutes junto con git add y git commit para ver exactamente qué se va a incluir en la próxima instantánea.***

***b. Describe los comandos git log y git diff para ver el historial de cambios y las diferencias entre versiones, respectivamente.
git log:Permite explorar las revisiones anteriores de un proyecto. Proporciona varias opciones de formato para mostrar las instantáneas confirmadas.
git diff:es un comando multiusos de Git que, cuando se ejecuta, lleva a cabo una función para establecer las diferencias en los orígenes de datos de Git. Dichos orígenes de datos pueden ser confirmaciones, ramas y archivos, entre otras posibilidades.***

***4 Trabajando con repositorios remotos:***
<br>***a. Investiga cómo clonar un repositorio remoto con git clone.***
***<br>-Abrir una terminal y navegar hasta el directorio deseado.***
***<br>-Obtén la URL del repositorio remoto.***
***Ejecutar git clone <URL> en la terminal, cambiando <URL> con la URL del repositorio.***
***<br>-Tocar el Enter y Git comenzará a clonar el repositorio en tu directorio actual.***
***<br>-Si es necesario, proporciona las credenciales de autenticación.***
***<br>-Una vez completada la clonación, tendremos una copia local del repositorio remoto.***
***<br>b. Explica cómo trabajar con ramas utilizando los comandos git branch, git checkout y git merge.***
***<br>git branch: Crear, listar o eliminar ramas.
<br>git branch nombre-rama: Crea una nueva rama.
<br>git branch: Lista las ramas existentes.
<br>git branch -d nombre-rama: Elimina una rama.
<br>-git checkout: Cambiar entre ramas o crear una nueva rama y cambiar a ella.
<br>git checkout nombre-rama: Cambia a una rama existente.
<br>git checkout -b nombre-rama: Crea y cambia a una nueva rama.
<br>git checkout -- nombre-archivo: Descarta cambios en   un archivo.
<br>-git merge: Fusionar cambios de una rama en otra.
<br>git merge nombre-rama: Fusiona una rama en la rama actual.***

***c. Investiga cómo subir tus cambios locales a un repositorio remoto con git push
 primero debes clonar un repositorio a tu máquina local. y el c0odigo es
Una vez clonado el repositorio, estarás trabajando dentro de la rama por defecto (Por defecto es `main`)
git clone https://github.com/<git-usuario>/<nombre-repo> && cd <nombre-repo>
Haz cambios y agrega tus archivos (repite el comando `git add` por cada archivo, o utiliza `git add .` para agregarlos todos)
git add <nombre-archivo>
Ahora haz el commit de tu código
git commit -m "Agregué cambios a mi repo!"
Sube los cambios en la rama 'main' a github
git push origin main***



***5 Colaboración en Git:
<br>a. Investiga cómo trabajar en equipo en un repositorio remoto utilizando ramas y fusiones.
Para poder colaborar en cualquier proyecto Git, necesitas saber cómo gestionar repositorios remotos. Los repositorios remotos son versiones de tu proyecto que están hospedados en Internet o en cualquier otra red,  Puedes tener varios de ellos, y en cada uno tendrás generalmente permisos de lectura en solitario o de lectura y escritura. Colaborar con otras personas implica gestionar estos repositorios remotos enviando y trayendo datos de ellos cada vez que necesite compartir su trabajo, 
Para ver los remotos que tienes configurados, debes ejecutar el comando git remote. Mostrará los nombres de cada uno de los remotos que tiene especificados. Si has clonado tu repositorio, deberías ver al menos origin (origen, en inglés) - este es el nombre que por defecto Git le da al servidor del que has clonado, En el día a día del trabajo con Git una de las cosas útiles que podemos hacer es trabajar con ramas. Las ramas son caminos que puede tomar el desarrollo de un software, algo que ocurre naturalmente para resolver problemas o crear nuevas funcionalidades. En la práctica permiten que nuestro proyecto pueda tener diversos estadose y que los desarrolladores sean capaces de pasar***

***b. Explica qué son las solicitudes de extracción (pull requests) y cómo se utilizan para revisar y aprobar cambios.
Vamos a presentar un ejemplo simple de ramificar y fusionar, con un flujo de trabajo que se podría presentar en la realidad. Imagina que sigues los siguientes pasos:
Trabaja en un sitio web.
Creas una rama para un nuevo tema sobre el que quieres trabajar.
Realiza algo de trabajo en esa rama.
En este momento, recibe una llamada avisando de un problema crítico que tiene solución. Y sigues los siguientes pasos:
Vuelve a la rama de producción original.
Creas una nueva rama para el problema crítico y lo resuelves trabajando en ella.
Tras las pertinentes pruebas, fusionar (merge) esa rama y la envía (push) a la rama de producción.
Vuelve a la rama del tema en que andabas antes de la llamada y continúas tu trabajo.***

