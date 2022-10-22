## Acadêmico

Sistema acadêmico de escolas.

## 🚀 Como executar o projeto

💡Tanto o Frontend quanto o Backend esteja sendo executado para funcionar.

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
- [Node.js](https://nodejs.org/en/) (LTS version)
- [PHP](https://www.php.net/) (v8.0.2 ou acima)
- [Composer](https://getcomposer.org/) (v2.0.4 ou acima)
- [Laravel](https://laravel.com/) (v9.19)

---

#### 🧭 Rodando a aplicação web (Backend e Frontend)

```bash

# Clone este repositório (ssh)
$ git clone git@github.com:gilmarodp/academico.git

# OU se prefere usar https:
$ git clone https://github.com/gilmarodp/academico.git

# Acesse a pasta do projeto no seu terminal/cmd
$ cd academico

# Copie o exemplo do .env e configure de acordo com suas configurações
$ cp .env.example .env

# Instale as dependências do php
$ composer install

# Gerando chave da aplicação laravel
$ php artisan key:generate

# Gerando chave de criptografia da lib de JWT
$ php artisan jwt:secret

# Instale as dependências do node
$ yarn

# Execute a aplicação em modo de desenvolvimento
$ yarn dev

# (OPCIONAL) Ou se preferir que o yarn identifique novas mudanças automaticamente
$ yarn watch

# Rode as migrações junto com as seeds
$ php artisan migrate --seed

# A aplicação será aberta na porta:8000 - acesse http://localhost:8000
$ php artisan serve

# Para rodar os testes, você pode rodar
$ ./vendor/bin/behat

```

Agora pronto, você pode iniciar o desenvolvimento 🚀.
