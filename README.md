# Apache + PHP 7

# Criar e levantar os containers
docker-compose up -d

# Iniciar o container Docker
docker-compose start

# Parar o container Docker
docker-compose stop

# Parar e remover containers da máquina
docker-compose down

# Entrar no container
docker exec -i -t nome_do_cantainer /bin/bash

# Enviar o php.ini custom
echo "short_open_tag = On" > /etc/apache2/conf.d/custom.ini
