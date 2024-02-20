# Comandos de git

## Comando para ver la version de git

- git -v
- git --version

## Comandos para configuracion incial de git

- git config --global user.name "Your name"
- git config --global user.email "Your email"

## Comando para editar o ver la configuracion de git

- git config --global --edit
- git config --global --list

## Para salir del edit ctrl + o y ctrl + x y si es VIM esc + :wq

## Como iniciar git en un directorio 

- git init 

## Pasos para crear una version de nuestro codigo 


1. Agregar todos los archivos al commit

- git add . "Todos"
- git add *.js "Para agregar algunos archivos con una extension en especifico"
- git add index.js "Un archivo en especifico"