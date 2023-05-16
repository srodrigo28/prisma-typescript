## Node API JWT + Prisma ORM
### Referências
    * https://www.udemy.com/course/dev-fullstack/learn/lecture/31683250#questions
### Dependências Iniciais Config
    * typescript
        * npm install typescript -D
        * npm install tsc --init
        * npm install tsc-init
        * npm install ts-node-dev -D
        * tsc-init

        * sudo npm install tsc-init -g
    * express
        * npm install --save express
        * npm install --save @types/express -D
    * JWT
    * Prisma
    * jsonwebtoken
### package.json
    "scripts": {
        "dev": "ts-node-dev --transpile-only src/server.ts"
     },
### tsconfig.json
~~~javascript
{ "compilerOptions": { "module": "commonjs", "esModuleInterop": true, "allowSyntheticDefaultImports": true, "target": "es6", "noImplicitAny": true, "moduleResolution": "node", "sourceMap": true, "outDir": "dist", "baseUrl": ".", "paths": { "": [ "node_modules/", "src/types/" ] } }, "include": [ "src/**/" ] }
~~~
## Dependências Outras
    * express
        * npm install --save express
        * npm install --save @types/express -D
    * 
### Starting project
    * npm run dev
### Tabelas
    * Users
    * Orders
    * Itens
    * Produtos
    * Login
### Controllers
### Services
### Rotas