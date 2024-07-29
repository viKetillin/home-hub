# Home-Hub

**Home-Hub** é um microfrontend dedicado a fornecer o layout de automação residencial. Ele oferece apenas a interface de usuário, servindo como base para futuras integrações e funcionalidades.

## Índice

- [Descrição](#descrição)
- [Requisitos](#requisitos)
- [Instalação](#instalação)
- [Uso](#uso)
- [Contribuição](#contribuição)
- [Licença](#licença)

## Descrição

O Home-Hub é um microfrontend projetado para fornecer uma interface de usuário centralizada para sistemas de automação residencial. Atualmente, ele fornece apenas o layout básico e a estrutura visual necessária para integrar futuras funcionalidades de automação residencial.

## Requisitos

- Node.js (versão 14 ou superior)
- npm ou yarn
- Navegador moderno (Chrome, Firefox, Edge, Safari)

## Instalação

1. Clone o repositório:

    ```sh
    git clone https://github.com/seu-usuario/home-hub.git
    ```

2. Navegue até o diretório do projeto:

    ```sh
    cd home-hub
    ```

3. Instale as dependências para cada um dos projetos (`root`, `navbar`, `dashboard`, `home-hub`):

    ```sh
    cd root
    npm install
    cd ..

    cd navbar
    npm install
    cd ..

    cd dashboard
    npm install
    cd ..
    ```

## Uso

Para rodar o Home-Hub junto com os outros microfrontends (root, navbar, dashboard):

1. Inicie cada um dos projetos em terminais separados:

    ```sh
    cd root
    npm start
    ```

    ```sh
    cd navbar
    npm start
    ```

    ```sh
    cd dashboard
    npm start
    ```

2. Abra o navegador e acesse:

    ```
    http://localhost:9000
    ```

3. Navegue pelo layout da interface de automação residencial integrada com os outros microfrontends.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests. Antes de contribuir, por favor, leia nosso [guia de contribuição](CONTRIBUTING.md).

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
