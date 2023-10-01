<!-- Este é um comentário: omitir os tópidos redundantes -->
<!--  **| [Brazil](README.md) | [asdf](README_en.md) |** -->

# Northwind db Query

O "Northwind Database" é um esquema de banco de dados usado para fins educacionais. Neste projeto foram praticadas consultas SQL para recuperar e manipular informações das tabelas.

## Pré-Requisitos

O esquema de banco de dados precisa de uma ferramenta de gerenciamento de sua preferencia, este dev usou o MySQL Workbench, um ambiente Docker ou o MySQL Server.

- [Docker](https://docs.docker.com/compose/)
- [MySQL Workbench](https://dev.mysql.com/downloads/workbench/)
- [MySQL Server](https://dev.mysql.com/downloads/mysql/)

## Uso

- Os scripts criados durante o projeto se encontram na raiz e precisam ser executados na ferramenta de gerenciamento de usa preferencia.

- Faça o download ou clone este repositório:

```bash
git clone git@github.com:lionelsu/MySQL-northwind-db-query.git && cd MySQL-northwind-db-query
```

- Caso esteja usando um ambiente `Docker compose` inicialize o `mysql server` e as demais dependencias no ambiente virtual:

```bash
docker compose up -d
```

Este comando já inicializa o `northwind.sql` no servidor de banco de dados `MySQL SERVER` localizada dentro da pasta `db`

- Sem o docker:
  - execute o script MySQL localizado na pasta `db`

## Habilidades desenvolvidas

- Encontrar dados com `SELECT`.
- Filtrar dados com `WHERE, LIKE, BETWEEN, IN`.
- Manipular tabelas com `INSERT, UPDATE, DELETE, TRUNCATE.`
- Acessar dados e tableas com `USE, AS, SHOW, TABLES`.
- Paginar com `LIMIT, OFFSET, ORDER BY`.
