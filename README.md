Actividad 5 - Unidad 0
Uso de Git (II)
===============
![](imagenes/excelencia.jpeg)

---

Tercera y última actividad en la que trabajamos con Git.
En esta ocasión vamos a trabajar de manera colaborativa.

El producto a realizar será la creación un repositorio (con nombre PPSUnidad0Actividad5TuNombre) en la [plataforma de GitHub](https://github.com/)  que contenga un conjunto de archivos donde tendremos archivos de documentación de todo el proceso realizado (en formato .md) junto con el resto de archivos necesarios, imágenes, etc...

Una vez documentado todo el proceso en tu README.md, en la entrega por la plataforma, pega el enlace a tu repositorio de github.com

### Creación del repositorio

En esta ocasión vamos a crear nuestro proyecto a partir de otro proyecto ya existente.

> Crea tu proyecto en tu dispositivo local clonando (este repositorio)[https://github.com/jmmedinac03vjp/PPS-Unidad0Actividad5-JoseMi]. __Recuerda que para tu proyecto se deberá crear una carpeta en tu equipo con nombre PPS-ActividadUnidad0-TuNombre o sea que la sintaxis de git clone deberá ser un poco más compleja que el nombre del repositorio__
Recuerda  cómo creamos el repositorio desde la línea de comandos:

~~~
echo "# PPS-Unidad0Actividad5-JoseMi" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:jmmedinac03vjp/PPS-Unidad0Actividad5-JoseMi.git
git push -u origin main
~~~

### Visualizando la página web

1. Visualiza con php el contenido de la página web.

2. Introduce dentro de la carpeta img una imagen de tu avatar.

3. Dentro de la carpeta profile crea un archivo html con el mismo nombre del archivo de la imagen que copiaste.

4. Lanza el comando php para que se muestre el contenido de la página web y ver cómo se ha modificado.


Modifica archivos y trabaja con desahacer cambios, volver a estado anterior, diferencias entre ficheros, borrar ficheros etc. git checkout, git reset, git diff, git rm...
Investiga la diferente información podemos ver con git log
Sube tu proyecto a tu página de git.

# Erre que erre con Git Logs

>Repasemos git logs

1. Muestra los logs
2. Muestra los logs de los últimos 3 commits
1. Muestra los logs utilizando el modificador ``--pretty`
1. Muestra los logs de los últimos 2 commits donde se vean las diferencias de cada una de las entradas.
1. Muestra los logs de las modificaciones realizadas en el último día


Sube los cambios al repositorio.

### Colaborando

1. Comparte tu proyecto con al menos dos compañeros.
1. En cada uno de los proyectos  de tus compañeros añade una nueva rama con tu nombre.
1. Añade en esa rama tus archivos de usuario (foto y profile).
1. Sube los cambios de tu rama.

> Ahora vamos a hacer modificaciones en la rama main de tus compañeros. Es importante que el tiempo entre el push y el pull sea pequeño, ya que si en ese tiempo hay modificaciones por parte de otro colaborador, es posible que haya inconsistencias, en cuyo caso tendremos que utilizar git merge.

1. Cambiate a la rama main de los proyectos de tus compañeros
1. Sincroniza en local la rama main. (puedes comprobar qué compañeros han subido datos lanzando la aplicación web con php).
1. Añade en ella tus archivos de usuario (foto y profile).
1. Sube los cambios a la rama main.

### Entrega

> Una vez documentado todo el proceso en tu README.md, en la entrega por la plataforma, pega el enlace a tu repositorio de github.com
