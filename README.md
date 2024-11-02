# **Práctica 1: Introducción a Git**

El programa `HolaMundo.py` es un programa que muestra un **"Hola Git"**. El objetivo de la práctica es el aprendizaje de la herramienta de **Git** y **GitHub**.

Para poder ejecutar el programa, dependerá del entorno que se utilice. En este caso, se considerará que se está intentando correr desde la terminal. De esa manera, se puede ejecutar con el comando:

```bash
python HolaMundo.py
```
Comandos utilizados para subir los archivos a GitHub:
- git init
- git add
- git commit
- git status
- git remote
- git push

El archivo .gitignore se creó para poder ignorar archivos que no son necesarios en el proyecto o carpeta de GitHub (en este caso, un archivo llamado debug.log). Este archivo se activa automáticamente al guardarlo en nuestros archivos de Git (al hacerle commit al .gitignore). Podemos verificar que se están ignorando los archivos deseados con un git status, en el cual, al ejecutar, no se observará el archivo ignorado dentro de la lista de archivos pendientes de agregar.
