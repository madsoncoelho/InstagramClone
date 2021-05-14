# InstagramClone
Projeto criado no curso "Criando um Clone do Instagram com React Native" da [Digital Innovation One](https://digitalinnovation.one).

Este app foi feito com React Native e trata-se de um clone do Instagram para os posts do usuário. Para montar a interface de posts, o app faz requisições à uma API fake criada com o auxílio do JSON Server.

## Instruções

Depois de obter o seu projeto na máquina local, acesse o diretório do projeto na interface de linha de comandos do sistema.

Em seguida, instale as dependências:
```bash
yarn
```

Para criar a API de postagens, faça o seguinte:
```bash
json-server server.json
```

Em outra janela de linha de comandos, acesse novamente o diretório do projeto e execute o Metro Server:
```bash
yarn start
```

Em outra janela de linha de comandos, no diretório do projeto, execute a aplicação. Neste passo, assegure-se de ter o emulador aberto no computador local.
```bash
yarn android
```

**Nota:** Para iOS, excute `yarn ios`.

## Bibliotecas e dependências de projeto principais
- React Native
- React Navigation
- JSON Server
- Axios
- Styled Components

## Screenshots
<img src="screenshot.png" width="216" height="384">
