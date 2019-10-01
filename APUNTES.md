# Curso de Git y Github de Fatz.
# Ruta de yoututbe: https://www.youtube.com/watch?v=HiXLkL42tMU
# 30 de Septiembre del 2019.

-- Instalamos Git
-- Creo el proyecto
-- git init: le digo a git que voy a empezar a utilizar git en el proyecto.  Debo estar
   posicionado en la carpeta del proyecto.
-- git status: me permite ver los archivos en los cuales estoy trabajando.
-- git add nombre-archivo: para agregar un archivo al cual quiero darle seguimiento a traves de git, es decir,
   a empezar a darle commit, push, etc.
-- git config --global user.email "fredalsa@gmail.com" para crear un usuario que estara trabajando con los cambios.
-- git config --global user.name "Frederic Alvarez" para darle un nombre al usuario.
-- git commit me lleva al editor vi para poder insertar (i) un comentario, con Escape :wq salgo y grabo, o puedo
-- git commit -m "comentario de que hice para este commit"
-- git checkout nombre-archivo me reversa lo que le hecho en el archivo si no he hecho commit.
-- git diff nombre-archivo me presenta las diferencias entre lo que hice y lo que tenia.
-- puedo crear un archivo .gitignore para que no tome en cuenta los archivos y carpetas que estan señalados aqui.
