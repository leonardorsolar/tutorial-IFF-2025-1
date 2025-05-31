# Tutorial Sequencial para Iniciantes em JavaScript e Frontend com Node.js]

Claro! Aqui está um resumo objetivo e direto do seu tutorial sequencial:

---

# Resumo: Tutorial Sequencial para Iniciantes em JavaScript e Backend com Node.js

## Parte 1 — Projeto Básico JavaScript + MVC no Node.js

-   Aprenderá a baixar o projeto do GitHub
-   Comprender rodar e a saber como funciona uma função em javascript
-   Será desafiado a rodar e acomprender um projeto simples mvc.
-   Uso do paradigma Procedural (ou Estruturado) - Uso de função (usuario) para encapsular um comportamento.
-   Repositório: [https://github.com/leonardorsolar/iff-basic-program-javascript-](https://github.com/leonardorsolar/iff-basic-program-javascript-)

## Parte 2 — Projeto Frontend em HTML, CSS e JavaScript para Registrar Usuário

-   Aprenderá a baixar o projeto do GitHub
-   Como abrir e entender os arquivos HTML, CSS e JavaScript.
-   Como rodar o projeto localmente para testar no navegador.
-   Como funciona o código que envia dados do formulário para um servidor (backend).
-   Repositório: [https://github.com/leonardorsolar/iff-basic-program-javascript-front](https://github.com/leonardorsolar/iff-basic-program-javascript-front)

## Parte 3 — Executando um servidor Node.js com TypeScript e Express

-   Aprenderá a baixar o projeto do GitHub
-   Compreenderá como rodar um servidor (localmente) do tipo Express.
-   Utilizaremos TypeScript (Linguagem de programação fortemente tipada)
-   Entraremos no paradigma orientado a objetos (OOP)
-   Será desafiado a conectar um projeto Front end com um Back end.
-   Repositório: [https://github.com/leonardorsolar/iff-basic-program-javascript-server-express](https://github.com/leonardorsolar/iff-basic-program-javascript-server-express)

## Parte 4 — Rodando backend Node.js + TypeScript + Express

-   Aprenderá a baixar o projeto do GitHub
-   Conhecerá uma arquitetura em camadas
-   Utilizaremos TypeScript (Linguagem de programação fortemente tipada)
-   Utilizará o paradigma orientado a objetos (OOP)
-   Será desafiado a conectar um projeto Front end com um Back end.
-   Repositório: [https://github.com/leonardorsolar/iff-basic-program-javascript-server](https://github.com/leonardorsolar/iff-basic-program-javascript-server)

## Parte 5 — Organizando backend com arquitetura em camadas (Layers)

-   Será desafiado a estruturar o backend em camadas para facilitar manutenção e escalabilidade, usando:

    -   Routes: definição das rotas HTTP
    -   Controller: entrada e saída das requisições
    -   Service: regras de negócio
    -   Repository: acesso ao banco de dados
    -   Model: estrutura da entidade
    -   Database: configuração da conexão

-   Projeto simples para cadastrar usuários com Express, TypeScript e SQLite.
-   Repositório: [https://github.com/leonardorsolar/iff-architecture-program-javascript-server](https://github.com/leonardorsolar/iff-architecture-program-javascript-server)

---

## Parte 1 — Projeto Básico JavaScript + MVC no Node.js

Repositório:
[https://github.com/leonardorsolar/iff-basic-program-javascript-](https://github.com/leonardorsolar/iff-basic-program-javascript-)

### Objetivo

Aprender a baixar, entender e executar um projeto básico em Node.js usando JavaScript puro e a arquitetura MVC (Model-View-Controller).

### Passo a passo

---

### 1. Pré-requisitos — O que você precisa instalar

-   **Git:** para baixar o projeto do GitHub.
    Baixe em: [https://git-scm.com/downloads](https://git-scm.com/downloads)
    Teste:

    ```bash
    git --version
    ```

    Deve mostrar a versão do Git instalada.

-   **Node.js:** para rodar código JavaScript fora do navegador.
    Baixe em: [https://nodejs.org/](https://nodejs.org/)
    Teste:

    ```bash
    node -v
    ```

    Deve mostrar a versão do Node.js.

---

### 2. Baixando o projeto

No terminal, rode:

```bash
git clone https://github.com/leonardorsolar/iff-basic-program-javascript-
```

---

### 3. Entrar na pasta do projeto

```bash
cd iff-basic-program-javascript-
```

---

### 4. Entender e rodar código simples

Abra o arquivo `01Function/function.js`. Esse código cria uma função simples e imprime o resultado.

Para rodar:

```bash
node 01Function/function.js
```

Saída esperada no terminal:

```
leonardo
```

---

### 5. Entender o projeto MVC

Pasta: `02mvc`

Arquivos principais:

-   **app.js:** ponto inicial, chama o controller.
-   **controller.js:** processa dados, chama service.
-   **service.js:** lógica principal, chama database.
-   **database.js:** simula banco de dados.

Fluxo:
`app.js` → `controller.js` → `service.js` → `database.js` → resposta volta para `app.js`.

---

### 6. Rodar o projeto MVC

```bash
cd 02mvc
node app.js
```

Você verá no terminal mensagens que mostram o fluxo funcionando, com dados sendo passados entre as camadas.

---

### 7. Próximos passos para estudar

-   Funções, variáveis e objetos em JavaScript.
-   Como importar/exportar módulos (require/module.exports).
-   Como o Node.js executa o código.
-   Entender arquitetura MVC para organizar o código.

---

### Resumo comandos Parte 1

```bash
git clone https://github.com/leonardorsolar/iff-basic-program-javascript-
cd iff-basic-program-javascript-
node 01Function/function.js
cd 02mvc
node app.js
```

---

## Parte 2 — Projeto Frontend para Registrar Usuário

Repositório:
[https://github.com/leonardorsolar/iff-basic-program-javascript-front](https://github.com/leonardorsolar/iff-basic-program-javascript-front)

### Objetivo

Aprender a baixar, abrir e rodar um projeto frontend simples com HTML, CSS e JavaScript para enviar dados a um backend.

---

### 1. O que você precisa instalar

-   Git (já instalado na Parte 1).
-   Editor de código: [Visual Studio Code](https://code.visualstudio.com/download).
-   Navegador moderno (Chrome, Firefox, Edge).

---

### 2. Baixando o projeto frontend

```bash
git clone https://github.com/leonardorsolar/iff-basic-program-javascript-front.git
cd iff-basic-program-javascript-front
```

---

### 3. Estrutura dos arquivos

-   `index.html` → Formulário para registrar usuário.
-   `styles.css` → Estilo do site (cores, fontes, espaçamento).
-   `script.js` → Código JavaScript que envia os dados para o backend.

---

### 4. Abrindo o projeto no navegador

-   Abra a pasta do projeto no VSCode (`code .` no terminal ou abrir via menu).
-   Clique em `index.html`.
-   Use a extensão **Live Server** (se disponível) para rodar localmente no navegador, ou apenas dê dois cliques no arquivo para abrir no navegador.

---

### 5. Como funciona o formulário (index.html)

Formulário com campos: Nome, Email, Senha.
Botão “Registrar” envia os dados.

---

### 6. Como funciona o JavaScript (script.js)

-   Escuta o envio do formulário.
-   Pega os valores digitados.
-   Monta um objeto com os dados.
-   Envia para o backend usando `fetch` com método POST.
-   Mostra mensagem de sucesso ou erro na tela.

---

### 7. Importante: Rodar o backend para o frontend funcionar

O frontend espera que tenha um servidor backend rodando em:

```
http://localhost:3000/criar-usuario
```

Sem o backend rodando, o envio de dados vai falhar.

---

### 8. Testando tudo

-   Primeiro rode o backend (da Parte 1) para ter o servidor funcionando na porta 3000.
-   Depois abra o `index.html` no navegador.
-   Preencha e envie o formulário.
-   Veja mensagens na tela e no console do navegador (F12 > Console).

---

### Resumo comandos Parte 2

```bash
git clone https://github.com/leonardorsolar/iff-basic-program-javascript-front.git
cd iff-basic-program-javascript-front
code .
```

Abra `index.html` no navegador (via Live Server ou direto).

---

### Dicas finais para iniciantes

-   Sempre verifique o console do terminal (backend) e do navegador (frontend) para mensagens e erros.
-   Teste pequenas mudanças nos arquivos `.js` e `.css` para aprender na prática.
-   Lembre-se que frontend depende do backend para enviar e receber dados.

Claro! Aqui está um **resumo didático da Parte 3** do tutorial do projeto **Node.js + TypeScript + Express** do repositório:

---

## Parte 3 — Executando um projeto Node.js com TypeScript e Express

Repositório:
[https://github.com/leonardorsolar/iff-basic-program-javascript-server-express](https://github.com/leonardorsolar/iff-basic-program-javascript-server-express)

### Passos para rodar o projeto localmente

1. **Pré-requisitos:**

    - Ter instalado Node.js (versão 18+).
    - Ter instalado Git.

2. **Clonar o projeto do GitHub:**

    - Use o comando:

        ```
        git clone https://github.com/seu-usuario/nome-do-projeto.git
        ```

    - Isso cria uma pasta local com o código.

3. **Acessar a pasta do projeto:**

    - Entre nela com:

        ```
        cd nome-do-projeto
        ```

4. **Instalar dependências:**

    - Rode:

        ```
        npm install
        ```

    - Isso instala pacotes necessários como Express, nodemon, TypeScript.

5. **Executar o projeto (modo desenvolvimento):**

    - Inicie o servidor com:

        ```
        npm run start
        ```

    - O servidor inicia e fica monitorando mudanças, reiniciando automaticamente.

6. **Acessar a aplicação no navegador:**

    - Abra:

        ```
        http://localhost:3000/
        ```

    - Vai mostrar mensagem: "Olá, Mundo! Bem-vindo ao Express com TypeScript."

    - Para ver dados do usuário (JSON):

        ```
        http://localhost:3000/usuario
        ```

    - Mostra:

        ```json
        {
            "nome": "leonardo",
            "email": "leo@gmail.com",
            "senha": "123456"
        }
        ```

7. **Visualizar frontend:**

    - Abra o arquivo `frontend.html` na pasta `front/` com um duplo clique.
    - Garanta que o backend esteja rodando.
    - Recomenda-se usar um servidor local (ex: Live Server do VSCode).

---

### Entendendo o código principal

-   **index.ts:** configura o servidor Express, define rotas `/` e `/usuario`, e inicia o servidor na porta 3000.
-   **modelos/Usuario.ts:** classe TypeScript que define um usuário com atributos nome, email e senha, com métodos getter/setter.

---

### Scripts no package.json

-   `npm run start` — roda o servidor com nodemon (recarregamento automático).
-   `npm run build` — compila TypeScript para JavaScript.
-   `npm run start:prod` — executa a versão compilada (produção).
-   `npm test` — roda testes (não usado ainda).

---

### Dicas finais

-   Sempre rode `npm install` ao baixar o projeto.
-   Use `npm run start` durante o desenvolvimento.
-   Use `npm run build` para compilar o projeto manualmente.
-   Use `npm run start:prod` para rodar a versão final em produção.

---

Claro! Aqui está o tutorial **Parte 4** detalhado, passo a passo, didático, ideal para iniciantes, baseado no projeto do link que você enviou e conectando com a Parte 2 — Frontend para Registrar Usuário.

---

# 🧑‍💻 Tutorial Parte 4 — Como rodar seu backend com Node.js + TypeScript + Express

Este tutorial vai te ensinar a clonar, instalar e executar o projeto backend usando Node.js com TypeScript e Express. Essa parte será a base para conectar ao frontend que vimos na Parte 2, onde registramos usuários.

Repositório:
[https://github.com/leonardorsolar/iff-basic-program-javascript-server](https://github.com/leonardorsolar/iff-basic-program-javascript-server)

---

## 📦 1. Pré-requisitos

Antes de começar, certifique-se que seu computador tenha:

-   **Node.js instalado** (recomenda-se versão 18+):
    [https://nodejs.org/](https://nodejs.org/)

-   **Git instalado**:
    [https://git-scm.com/](https://git-scm.com/)

---

## ⬇️ 2. Clonar o projeto do GitHub

Abra o terminal (Prompt de comando, PowerShell ou Git Bash) e execute o comando:

```bash
git clone https://github.com/leonardorsolar/iff-basic-program-javascript-server.git
```

Isso vai copiar o projeto para sua máquina, criando uma pasta `iff-basic-program-javascript-server`.

---

## 📁 3. Entrar na pasta do projeto

Digite no terminal:

```bash
cd iff-basic-program-javascript-server
```

Agora você está dentro da pasta com o código do backend.

---

## 📦 4. Instalar as dependências

Para instalar todas as bibliotecas necessárias (Express, TypeScript, nodemon, etc), execute:

```bash
npm install
```

Esse comando lê o arquivo `package.json` e instala tudo que o projeto precisa.

---

## 🚀 5. Executar o backend

Para rodar o servidor local em modo de desenvolvimento, com reinício automático em caso de alteração, use:

```bash
npm run start
```

Você verá no terminal a mensagem:

```
Servidor rodando na porta 3000
```

Isso significa que o backend está funcionando.

---

## 🌐 6. Testar a aplicação no navegador

-   Acesse no navegador o endereço:

```
http://localhost:3000/
```

Você verá:

```
Olá, Mundo! Bem-vindo ao Express com TypeScript.
```

-   Para acessar a rota que retorna os dados de usuário simulado, acesse:

```
http://localhost:3000/usuario
```

Você verá o seguinte JSON:

```json
{
    "nome": "leonardo",
    "email": "leo@gmail.com",
    "senha": "123456"
}
```

---

## 🧠 7. Entendendo o código principal

-   **index.ts**
    Cria o servidor Express, define rotas `/` e `/usuario`, e escuta na porta 3000. Usa a classe `Usuario` para organizar dados do usuário.

-   **modelos/Usuario.ts**
    Define a classe `Usuario` com os atributos `nome`, `email` e `senha` e métodos para acessar/modificar esses dados.

---

## 🧰 8. Scripts disponíveis no package.json

```json
"scripts": {
  "start": "nodemon",               // Roda o servidor com reinício automático
  "build": "tsc",                   // Compila o TypeScript em JavaScript
  "start:prod": "node dist/index.js", // Roda o backend compilado para produção
  "test": "jest"                    // Roda testes (não usado ainda)
}
```

---

## 💡 9. Dicas para você

-   Sempre rode `npm install` ao baixar um projeto novo.
-   Use `npm run start` para desenvolver, assim o servidor reinicia automaticamente ao salvar arquivos.
-   Se quiser compilar o TypeScript manualmente, rode `npm run build`.
-   Quando o projeto estiver pronto para produção, use `npm run start:prod`.

---

## 🔗 Próximo passo: conectar esse backend com um frontend

Front end se encontra na parte 2: Parte 2: Projeto Frontend para Registrar Usuário

Agora que você já sabe rodar o backend com Express + TypeScript, o próximo passo será conectar esse backend com um frontend.

Na **Parte 2** do nosso curso, vamos criar a interface para o usuário registrar seu cadastro, enviando os dados para esse servidor backend.

Você aprenderá como:

-   Criar formulários HTML para registrar usuário.
-   Fazer requisições HTTP para o backend.
-   Exibir respostas e mensagens para o usuário.

---

Assim, você terá o ciclo completo: **Frontend + Backend trabalhando juntos!**

---

Claro! Aqui está o tutorial **Parte 5**, focado em arquitetura de software e organização do backend em camadas, para ajudar o aluno a entender e aplicar boas práticas, deixando o projeto mais escalável e fácil de manter.

---

# 🧑‍💻 Tutorial Parte 5 — Organizando o backend com arquitetura em camadas (Layers) em Node.js + TypeScript

Repositório:
[https://github.com/leonardorsolar/iff-architecture-program-javascript-server](https://github.com/leonardorsolar/iff-architecture-program-javascript-server)

Neste tutorial, você vai aprender a organizar o código do seu backend em camadas, seguindo um padrão muito usado na indústria: **Arquitetura em Camadas**.

Essa abordagem separa responsabilidades do código para facilitar a manutenção, escalabilidade, reutilização e teste.

Uma API simples para cadastrar usuários, utilizando:

Express (servidor web)
TypeScript (tipagem e organização do código)
SQLite (banco de dados leve)
Arquitetura modular com separação por responsabilidade

## 📁 Estrutura inical do Projeto (dentro da pasta `src/`)

```
src/
├── index.ts                      # Arquivo principal (server)
├── controladora/
│   └── ControladorUsuario.ts     # Controller responsável pelas regras de negócio
├── bancodados/
│   └── database.ts               # Conexão e operações com o banco de dados
```

---

## 🎯 Objetivo

Transformar o backend atual em um projeto organizado com as seguintes camadas:

| Camada         | Responsabilidade                                         |
| -------------- | -------------------------------------------------------- |
| **Routes**     | Configuração e definição das rotas HTTP                  |
| **Controller** | Recebe requisições e retorna respostas (entrada/saída)   |
| **Service**    | Contém as regras de negócio e lógica da aplicação        |
| **Repository** | Responsável pelo acesso e manipulação dos dados no banco |
| **Model**      | Define a estrutura das entidades (ex: Usuário)           |
| **Database**   | Configura conexão e operações do banco de dados          |

---

## 📁 Estrutura Final do Projeto (dentro da pasta `src/`)

```
src/
├── routes/
│   └── usuario.routes.ts           # Define rotas relacionadas ao usuário
├── controllers/
│   └── UsuarioController.ts        # Controlador para regras de entrada e saída
├── services/
│   └── UsuarioService.ts           # Lógica e regras de negócio
├── repositories/
│   └── UsuarioRepository.ts        # Acesso aos dados do usuário no banco
├── models/
│   └── Usuario.ts                  # Modelo da entidade usuário
├── database/
│   └── sqlite.ts                   # Configuração do banco de dados
├── index.ts                       # Arquivo principal que inicia o servidor
```

---

## 📝 Recapitulando

-   Dividimos o backend em camadas que separam responsabilidades.
-   Criamos modelo, repositório, serviço, controlador e rotas.
-   Esse padrão torna seu código mais organizado, fácil de entender e manter.
-   Você pode agora expandir seu backend para usar banco de dados real e regras complexas.

---

## 🔗 Próximos passos

-   Continue usando o **frontend da Parte 2** para consumir essas rotas e fazer o registro de usuários no seu backend organizado.
-   A partir daqui, você poderá adicionar autenticação, validações, testes automatizados e muito mais.

---

Se quiser, posso ajudar com exemplos para integrar este backend organizado ao frontend da Parte 2! Quer que eu faça?
