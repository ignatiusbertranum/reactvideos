Intro y requisitos previos
--------------------------
-Proyecto hecho en el curso de React de la plataforma online de formación platzi.com

-React es una librería de JS, se instala mediante npm. Ver npmjs.com
-Para instalar npm, hay que instalar nodejs (que contiene npm). Ver nodejs.org
-Para empezar una aplicación React, se puede usar un boilerplate (estructura mínima).
Ejemplo: https://github.com/facebook/create-react-app

-Se instala con:
sudo npm install -g create-react-app

-Para crear luego la aplicación mínima:
create-react-app platzi-video
(ejecutar la instrucción dentro de la carpeta raíz de nuestro proyecto; en este proyecto es /platzi, por ejemplo)

-Para luego inciarla:
cd platzi-video
npm-start


Configuración Webpack
---------------------
-Dos ficheros de configuración:
1) webpack.config.js: para producción
2) webpack.dev.config.js: para test


Package.json
------------
-Para crear el fichero package.json:
npm init
(ejecutar la instrucción en la carpeta donde están los ficheros de configuración de Webpack)

-Para instalar/actualizar dependencias nuevas/actualizadas:
npm install
(ejecutar la instrucción en la carpeta donde está el fichero package.json)

-Para ejecutar scripts indicados en package.json:
npm run [nombre del script]

Por ejemplo:
npm run build:dev
npm run build:prod


Instalar react
--------------
-Para instalar React y ReactDOM:
npm install react react-dom --save
(ejecutar la instrucción en la carpeta raíz; /platzi en este proyecto)