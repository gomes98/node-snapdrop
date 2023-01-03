# node-snapdrop [![CodeQL](https://github.com/Bellisario/node-snapdrop/actions/workflows/codeql-analysis.yml/badge.svg)](https://github.com/Bellisario/node-snapdrop/actions/workflows/codeql-analysis.yml)

Apenas o original [Snapdrop](https://github.com/RobinLinus/Snapdrop), com servidor Node.js completo e traduzido para Portugues.

> **Warning**\
> Due to [Heroku Free Plan Shutdown](https://github.com/Bellisario/node-snapdrop/issues/15), node-snapdrop server has changed and can now be reached [here](https://node-snapdrop.onrender.com).\
> Old server will be kept (without any code update) until November 28, 2022, then it will be shutdown by Heroku.

## Começando

Para começar, clone e copie o repositório:

```bash
git clone https://github.com/gomes98/node-snapdrop.git && cd node-snapdrop
```

Instale todas as dependências com NPM:

```bash
npm install
```

Inicie o servidor com:

```bash
node index.js
```

### Funcionamento público

Se você deseja executar em seu IP público "compartilhável" em vez de localmente, pode usar este comando:

```bash
node index.js public
```

> Lembre-se de verificar seu endereço IP usando o comando do sistema operacional para ver onde você pode acessar o servidor.
