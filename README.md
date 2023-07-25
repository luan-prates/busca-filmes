# Construindo um site com Next.js e React: Tutorial passo a passo

Vamos iniciar o desenvolvimento com
`npm init`
Agora vamos instalar as primeiras dependencias do projeto
`npm install next@13.1.6 react@18.2.0 react-dom@18.2.0`

Mudar de branch no projeto
`git fetch origin`
`git checkout 1-preparando-o-ambiente`

criar o arquivo `.gitignore` e adicionar a pasta `node_modules`

criar o arquivo `.nvmrc` e adicionar a versão do node.js utilizada no projeto `lts/hydrogen`

vamos adicionar o `Script dev` no `package.json`

ao rodar esse script notamos que foi criada uma pasta `.next` que tbm vamos adicinar no `.gitignore`

criar a pagina index.js
<code>
export default function Home() {
return (
<div>
<title>Meu site Next.js</title>
<h1>Bem-vindo ao meu site Next.js</h1>
</div>
);
}
</code>
criar a pagina search.js
