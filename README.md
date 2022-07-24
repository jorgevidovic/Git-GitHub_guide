# Git-GitHub_guide
ES: Guía para trabajar con Git y/o GitHub para principiantes.

EN: A beginner's guide to working with Git and/or GitHub.

## - Crear repositorio:

**Si el repositorio ya existe, hay clonarlo antes de seguir los pasos:**

  - git clone                                           --> Paso opcional para clonar un repositorio ya existente.

  - git init                                            --> Inicializa el proyecto.
  
  - git status                                          --> Paso opcional para ver un listado de archivos del proyecto.
  
  - git add .                                           --> Para cargar todos los nuevos archivos a la rama master
  
  - git commit -m "Texto variado"                       --> Carga los archivos nuevos del repositorio
  
  - git branch -M main                                  --> Para indicar que vamos a subir los archivos a la rama principal
  
  - git remote add origin "Link"                        --> Indicar la direccion del proyecto en github donde va a ser subido
  
  - git push -u origin main                             --> Para sincronizar la rama local con el remoto 


## - Actualizar repositorio:
  - git init                                            --> Inicializa el proyecto.
  
  - git status                                          --> Paso opcional para ver un listado de archivos del proyecto.
  
  - git add .                                           --> Para cargar todos los nuevos archivos a la rama main
  
  - git commit -m "Texto variado"                       --> Carga los archivos nuevos del repositorio
  
  - git push -u origin main                             --> Para sincronizar la rama local con el remoto
