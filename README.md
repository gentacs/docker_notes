# docker_notes
##Docker Machine
Comentario|Comando
------------------|---------------------
Buscar imagen | **$ docker search apache**
Descargar imagen  | **$ docker pull apache**
Iniciar un contenedor con consola interactiva| **$ docker run -i -t apache /bin/bash**
Lista de contenedores corriendo | **$ docker ps**
Lista de todos los contenedores | **$ docker ps -a**
##docker-compose
Comentario | Comando
--------|--------
Archivo de configuración | **docker-compose.yml**
Lista de contenedores corriendo | **$ docker-compose ps**
Construir y arrancar contenedores | **$ docker-compose up**
