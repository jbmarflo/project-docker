# Proyecto Docker
Esta es una estructura para comenzar un proyecto indpendientemente del lenguaje o framework.

# Carpeta /App
Aqui va tu proyecto.

# Carpeta /Config
Aquí va tus variables de entorno

# Carpeta /Docker
Aqui estan todos las configuraciones de las diferentes imágenes de docker.
Podrán encontra elasticsearch, kibana, logstash, mysql, nginx, php-fpm.

# script.sh
1. Modificar la variable DOMAIN="local.tu-pagina-web.com" en script.sh
2. Escrbie en tu consola "make install"
4. Para construir tus imágenes "make buld"

# Deploy con Bitbucket
Si trabajas con bitbucket y deseas hacer deploy, en este caso amazon web service (aws), lee este artículo: 
http://deepmy.com/blog/2017/11/03/conectar-instancia-ec2-aws-usando-ssh-a-la-terminal-ubuntu/
