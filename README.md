# Receitas

O projeto de Receitas tem como objetivo o desenvolvimento de uma apliacação web para exibição de receitas
utilizando as tecnologias Python 3, Django e PostgreSQL.

## Requisitos de software

asgiref==3.2.3
<br>dj-database-url==0.5.0
<br>Django==3.0
<br>django-heroku==0.3.1
<br>gunicorn==20.0.4
<br>psycopg2==2.8.4
<br>psycopg2-binary==2.8.4
<br>pytz==2019.3
<br>sqlparse==0.3.0
<br>whitenoise==4.1.4

## Como utilizar

Para executar esta aplicação, basta clonar o projeto e executar o comando abaixo na raiz do mesmo:
```
$ python manage.py runserver
```
Deploy no heroku realizado, porém falta configuração do banco de dados

## A fazer

- Configuração do banco de dados no Heroku
- Criar mais receitas no banco Postgres
- Imagens customizadas para cada receita
- Implementar o campo de busca de receitas
- Criar app no banco para registrar a pessoa que postou a receita
