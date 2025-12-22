Respuesta tarea Github módulo 2 - lección 7

git -- versión
Descripción: muestra la versión instalada de Git.
Ej: 
PS C:\Users\wwejo\Desktop\Actividad L-3 , 1,2,3,4> git --version
git version 2.52.0.windows.1


git init
Descripción: Inicializa un repositorio Git en la carpeta actual, creando el directorio .git
Ej: 
PS C:\Users\wwejo\Desktop\Actividad L-3 , 1,2,3,4> git init Initialized empty Git repository in C:/Users/wwejo/Desktop/Actividad L-3 , 1,2,3,4/.git/
git add
Descripción: Agrega archivos o cambios al área de preparación (staging).
Ej: 
PS C:\Users\wwejo\Desktop\Actividad L-3 , 1,2,3,4> git add .
PS C:\Users\wwejo\Desktop\Actividad L-3 , 1,2,3,4> 

git commit 
Descripción: Registra los cambios en el repositorio con un mensaje descriptivo. 
Ej: 
PS C:\Users\wwejo\Desktop\Actividad L-3 , 1,2,3,4> git commit -m "Proyecto Instalación Git"
[master (root-commit) 482440a] Proyecto Instalación Git
 6 files changed, 120 insertions(+)
 create mode 100644 Assets/audio/Pug main black movie.mp3
 create mode 100644 Assets/img/limpieza pliegue pug.avif
 create mode 100644 Assets/img/limpieza-pliegue-pug (1) (1).jpg
 create mode 100644 Assets/videos/video chistoso pug 1.mp4
 create mode 100644 CSS/styles.css
 create mode 100644 index.html

git status
Descripción: Muestra el estado de los archivos del repositorio. 
Ej: 
PS C:\Users\wwejo\Desktop\Actividad L-3 , 1,2,3,4> git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

