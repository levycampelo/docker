# docker

O arquivo docker-compose.yml configura o Docker e cria 4 containers: zabbix-server, zabbix-frontend, grafana e mysql. As imagens oficiais são utilizadas para instalação do Zabbix, do Grafana e do MySQL.

Ao executar o comando docker-compose up, o Docker irá subir de forma automática os containers do Zabbix, do Grafana e do MySQL. Além disso, o Zabbix já estará conectado ao banco de dados MySQL e o Grafana já estará com o plugin do Zabbix instalado.

Executar o seguinte comando na pasta que esta localizado o arquivo docker-compose.yml para suber os containers:

docker-compose up -d

Fonte: Iago Ferreira TI 
