---
layout: post
title: Intalación y configuración de un blog en github
---

## Instalación

Decir que me estoy inspirando en el blog de [fernand0](fernand0.github.io)

1. Empezamos clonando (fork) el repositorio oficial [jekyll now](https://github.com/barryclark/jekyll-now)

2. Cambiamos el nombre de nuestro repositorio (desde la opción settings) al que queremos que sea nuestro sub-dominio (colgando de github.io). En mi caso a javacasm.github.io  

3. Editamos el fichero _config.yml y el about.md

4. A partir de ahora sólo hay que crear ficheros en la carpeta post con el formato **yyyy-m-dd-titulo.md** y recordar incluir la cabera en el formato

		---
		layout: post
		title: Blogging Like a Hacker
		---

Podemos usar etiquetas y otras opciones de visualización y clasificación con [otras marcas](http://jekyllrb.com/docs/frontmatter/)

5. En la carpeta **layout** tenemos 3 ficheros: default (con el formato de toda la página, donde podemos cambiar la cabecera, el pie o el aspecto en general), post (que será el aspecto cuando estemos visualizando un post concreto) y page (con la estrucrra de una página). En la cabera de cada post indicaremos el layout que queremos usar.

6. Ahora a retocar el aspecto, y añadir funcionalidades como ver post anteriores, enlaces a etiquetas, etc...
