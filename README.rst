.. -*- coding: utf-8 -*-

Introducción
============

Este es un ejemplo de la configuración básica de `buildout`_ usada en el articulo 
`Hola mundo en zc.buildout`_, el cual explica como generar un programa típico 
`Hola Mundo`_ en Bash script llamado **"hola"** dentro del directorio ``bin/`` 
local a tu entorno de desarrollo y otorgar permisos necesarios para la ejecución de este programa.

Instalación
-----------

La instalación la realiza con los siguientes comandos: ::

  $ pip install zc.buildout
  $ git clone https://github.com/plone-ve/buildout.helloworld.git
  $ cd ./buildout.helloworld
  $ buildout init
  $ ./bin/buildout
  $ ./bin/hola
  $ hola mundo
  
.. _Hola Mundo: http://es.wikipedia.org/wiki/Hola_Mundo
.. _buildout: http://plone-spanish-docs.readthedocs.org/en/latest/buildout/replicacion_proyectos_python.html
.. _Hola mundo en zc.buildout: http://plone-spanish-docs.readthedocs.org/en/latest/buildout/hola_mundo_zcbuildout.html
