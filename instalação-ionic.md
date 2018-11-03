
O Ionic é um framework open-source usado para o desenvolvimento de aplicações móveis nativas para iOS e Android, bem como aplicações Web progressivas. (PWA).

A documentação base desse framework pode ser acessada aqui: https://ionicframework.com
Para instalá-lo, você pode usar o Node Package Manager (npm), que deve ser primeiramente instalado em seu sistema operacional.


Antes de começar a desenvolver com o Ionic, você precisará das seguintes ferramentas. Eles são um requisito para desenvolver praticamente qualquer aplicativo JavaScript moderno nos dias de hoje Mas mesmo se você já os tiver, verifique se está usando versões recentes.

* Um computador com Windows, macOS ou Linux.

* O navegador da Web Chrome, que possui um rico suporte para ferramentas de desenvolvimento e depuração de aplicações.

* Um editor de texto ou IDE, de preferência com suporte a TypeScript. Bons exemplos incluem o Visual Studio Code e o editor online StackBlitz (https://stackblitz.com). Ambos são gratuitos. Outras opções populares incluem Atom, WebStorm, Sublime Text, Visual Studio IDE.

* O Node.js, porque inclui o npm, uma ferramenta usada para instalar pacotes JavaScript. Eu recomendo usar a versão mais recente do Node.js LTS (Long Term Support). Em Novembro de 2018, a versão era a 10.13 - https://nodejs.org/en/download/

* No macOS e no Linux, eu recomendo usar o nvm para instalar o Node.js. Ele permite manter várias versões do Node.js ao mesmo tempo, e você nunca precisa usar o sudo porque tudo está instalado dentro da sua pasta HOME.

* IONIC CLI

Para criar builds e rodar nossos projetos, podemos usar o Ionic CLI (Command Line Interface). Você pode instalá-lo como um pacote npm globalmente em sua máquina simplesmente executando o seguinte comando:

```console
npm install -g ionic
```

O Ionic requer que o Cordova crie os aplicativos para Android e iOS. Portanto instale o Cordova CLI também com:


```console
npm install -g cordova
```


