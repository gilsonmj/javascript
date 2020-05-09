# Estudos de javascript

## Para iniciar abrir o projeto em seu computador, siga as instruções abaixo:


> ### 1. **Clone** o repositório através do link no botão verde **Clone or download.**
> #### `git clone <link do arquivo>`

> ### 2. Instale o **NodeJS**.
> ### https://nodejs.org/en/

> ### 3. Instale o **yarn** (gerenciador de dependências) na pasta baixada
> ### https://classic.yarnpkg.com/en/docs/install/#debian-stable

>### 4. Na pasta **javascript**, digite o comando no terminal

```
yarn init -y
```

>### 5. Para obter o recarregamento automático do servidor Node, instale o **nodemon**. O parâmetro "-D" garante que ele não será usado em produção.

```
yarn add nodemon -D
```

>### 6.  Após as instalações, edite o arquivo **package.json** acrescentendo, depois de "license": "MIT", o código abaixo. Isso fará com quem o nodemon carregue a aplicação a partir do arquivo principal.

```
"scripts": {
    "start": "nodemon index.js"
    },
```
>### 7. Por fim, inicie  o servidor por meio do comando

```
yarn start 
```

 


