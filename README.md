# Zapix - online Zabbix API tool

Esse é um fork do projeto original que pode ser encontrado em http://monitoringartist.github.io/zapix/.

O objetivo do fork é tornar o projeto compativel com o Zabbix 6.0 onde podemos testar as queries da Zabbix API diretamente no navegador

Possue autocomplete das bibliotecas e guarda usuário e senha do servidor Zabbix API utilizado

Se você usa docker:

```shell
docker build -t ldetbr/zapix .
docker run -p 8080:80 -d ldetbr/zapix
```

Depois disso, você pode acessar http://localhost:8080 no navegador


# Original project

https://bitbucket.org/Vedmak/zapix

