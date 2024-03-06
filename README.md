# My Bank API

<img width="1512" alt="bank-api-authBasic" src="https://github.com/marceloabbadia/bank-api-authBasic/assets/112344339/1683f827-8747-4ab0-8e6a-c3f3c75802ac">


## Descrição

My Bank API é uma aplicação Node.js que fornece serviços bancários básicos através de uma API RESTful. A API permite a criação, leitura, atualização e exclusão de contas bancárias, bem como a autenticação e autorização de usuários.

## Recursos

- Criação, leitura, atualização e exclusão de contas bancárias.
- Autenticação básica para usuários.
- Autorização baseada em funções para acessar determinados endpoints da API.
- Documentação Swagger disponível em `/doc`.

## Requisitos

- Node.js
- NPM (Node Package Manager)

## Instalação

1. Clone o repositório
2. Instale as dependências:

```bash
cd my-bank-api
npm install
```

## Configuração

Antes de iniciar a API, você pode ajustar algumas configurações no arquivo `config.js`, como o nome do arquivo de dados e a porta em que a API será executada.

## Uso

Para iniciar a API, execute o seguinte comando:

```bash
npm start
```

A API estará disponível em `http://localhost:3000` por padrão.

## Autenticação

A API usa autenticação básica. Dois usuários estão pré-configurados para autenticação:

- Usuário: admin, Senha: admin (Administrador)
- Usuário: angelo, Senha: 1234 (Usuário comum)

## Autorização

A autorização é baseada em funções. Alguns endpoints requerem privilégios de administrador para acessar.

## Documentação

A documentação da API está disponível em `http://localhost:3000/doc`.

## Licença

Este projeto está licenciado sob a Licença MIT. Consulte o arquivo [LICENSE](LICENSE) para obter detalhes.

