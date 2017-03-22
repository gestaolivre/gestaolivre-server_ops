---
layout: page
title: "Configuração"
category: doc
date: 2017-03-20 00:00:00
order: 2
---

Adicione um arquivo `.env` com o seguinte conteúdo na raiz do projeto

```bash
DEBUG=on
SECRET_KEY=dev-secret-key
DATABASE_URL=postgres://postgres:postgres@localhost:5432/postgres
CACHE_URL=redis://localhost:6379/0
```
