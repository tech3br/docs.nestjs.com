<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

[travis-image]: https://api.travis-ci.org/nestjs/nest.svg?branch=master
[travis-url]: https://travis-ci.org/nestjs/nest
[linux-image]: https://img.shields.io/travis/nestjs/nest/master.svg?label=linux
[linux-url]: https://travis-ci.org/nestjs/nest

  <p align="center">Uma estrutura progressiva do <a href="http://nodejs.org" target="_blank">Node.js</a> para construir aplicações eficientes e escaláveis do lado do servidor.</p>
    <p align="center">
<a href="https://www.npmjs.com/~nestjscore"><img src="https://img.shields.io/npm/v/@nestjs/core.svg" alt="NPM Version" /></a>
<a href="https://www.npmjs.com/~nestjscore"><img src="https://img.shields.io/npm/l/@nestjs/core.svg" alt="Package License" /></a>
<a href="https://www.npmjs.com/~nestjscore"><img src="https://img.shields.io/npm/dm/@nestjs/core.svg" alt="NPM Downloads" /></a>
<a href="https://travis-ci.org/nestjs/nest"><img src="https://api.travis-ci.org/nestjs/nest.svg?branch=master" alt="Travis" /></a>
<a href="https://travis-ci.org/nestjs/nest"><img src="https://img.shields.io/travis/nestjs/nest/master.svg?label=linux" alt="Linux" /></a>
<a href="https://coveralls.io/github/nestjs/nest?branch=master"><img src="https://coveralls.io/repos/github/nestjs/nest/badge.svg?branch=master#6" alt="Coverage" /></a>
<a href="https://discord.gg/G7Qnnhy" target="_blank"><img src="https://img.shields.io/badge/discord-online-brightgreen.svg" alt="Discord"/></a>
  <a href="https://dev.to/nestjs"><img src="https://img.shields.io/badge/blog-dev.to-green"/></a>
<a href="https://opencollective.com/nest#backer"><img src="https://opencollective.com/nest/backers/badge.svg" alt="Backers on Open Collective" /></a>
<a href="https://opencollective.com/nest#sponsor"><img src="https://opencollective.com/nest/sponsors/badge.svg" alt="Sponsors on Open Collective" /></a>
  <a href="https://paypal.me/kamilmysliwiec"><img src="https://img.shields.io/badge/Donate-PayPal-dc3d53.svg"/></a>
  <a href="https://twitter.com/nestframework"><img src="https://img.shields.io/twitter/follow/nestframework.svg?style=social&label=Follow"></a>
</p>
  <!--[![Backers on Open Collective](https://opencollective.com/nest/backers/badge.svg)](https://opencollective.com/nest#backer)
  [![Sponsors on Open Collective](https://opencollective.com/nest/sponsors/badge.svg)](https://opencollective.com/nest#sponsor)-->

## Descrição

Este projeto é construído em cima da [CLI Angular](https://github.com/angular/angular-cli). Ele usa o gerador de documentação [Dgeni](https://github.com/angular/dgeni) para compilar a documentação de origem em formato markdown para o formato publicado. O Repositório contém o código fonte [docs.nestjs.com](https://docs.nestjs.com), a documentação oficial do Nest.

## Instalando

Instale as dependências do projeto e inicie um servidor local com os seguintes comandos no terminal:

```bash
$ npm install
$ npm run start
```

Navegue até [`http://localhost:4200/`](http://localhost:4200/).

Todas as páginas são escritas em [markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) e estão localizadas na pasta `content`.

## Construir

Rode `npm run build` para contruir o projeto. Os artefatos de construção serão armazenados no diretório `dist/'.

Para executar build em modo _watch_, execute `npm run build:watch`. Qualquer mudança no conteúdo será recompilada e reconstruída, e o conteúdo servido em [`http://localhost:4200/`](http://localhost:4200/).

Utilize `npm run build:prod` para uma construção de produção.

## Apoiar

Nest é um projeto de código aberto licenciado pelo MIT. Ele pode crescer graças aos patrocinadores e ao apoio dos incríveis patrocinadores. Se você gostaria de se juntar a eles, por favor [leia mais aqui](https://opencollective.com/nest).

## Manter contato

- Autor - [Kamil Myśliwiec](https://twitter.com/kammysliwiec)
- Website - [https://nestjs.com](https://nestjs.com/)
- Twitter - [@nestframework](https://twitter.com/nestframework)

## Licença

Nest tem [MIT licenciado](LICENSE).
