# 📰 Projeto Job-Finder

A ***Job-Finder*** é um projeto desenvolvido em JavaScript/Node.js durante o curso oferecido pela Hora de Codar. Ele auxilia na busca e organização de oportunidades de emprego, permitindo aos usuários cadastrar, visualizar e gerenciar vagas de interesse. Com uma interface simples e intuitiva, o sistema facilita o acompanhamento das candidaturas, tornando o processo de busca de emprego mais eficiente. Além disso, a aplicação pode ser facilmente integrada a outras plataformas para otimizar o processo seletivo.

## 🎯 Objetivos do Projeto

1. Facilitar a organização de vagas de emprego;
2. Acompanhar candidatura;
3. Automatizar a busca por emprego.


## 🌐 Interface Web

A página principal do projeto permite que você visualize a lista de vagas cadastras, detalhes das oportunidades e possui um design focado na usabilidade

![Página Principal](/public/img/print1.png)

A página de adição de vagas permite cadastrar novas oportunidades, fornecendo informaçõs como nome da vaga, empresa e salário.

![Página de adição de vagas](/public/img/print2.png)

### 🔍 Testando Localmente

Para testar o projeto localmente, siga estas etapas:

1. Abra o terminal (ou prompt de comando) e execute o seguinte comando para clonar o repositório:

   `git clone https://github.com/joaocastro95/Projeto-Job-Finder`

2. Após clonar o repositório, entre no diretório do projeto com o comando:

   `cd Projeto-Job-Finder`

3. Execute o comando abaixo para instalar todas as dependências necessárias para o projeto:

   `npm install`

4. Inicie o servidor local com o comando:

   `npm run dev`

5. Abra um navegador web e digite o seguinte endereço na barra de endereços:

   `http://localhost:3000`

Isso abrirá a interface web do projeto. Se o servidor estiver funcionando corretamente, você verá a página principal onde poderá utilizar a "Job-Finder".


### 🐋 Testando por Docker

Usar Docker em um projeto Node.js traz diversas vantagens, principalmente relacionadas à portabilidade, escalabilidade e independencia do sistema operacional, como por exemplo no AWS. para testar:

1. Abra o terminal (ou prompt de comando) e execute o seguinte comando para clonar o repositório:

   `git clone https://github.com/joaocastro95/Projeto-Job-Finder`

2. Após clonar o repositório, entre no diretório do projeto com o comando:

   `cd Projeto-Job-Finder`

3. Execute o comando abaixo para instalar todas as dependências necessárias para o projeto:

    `docker-compose up --build`

- Se quiser rodar em background: `docker-compose up -d`

4. Abra um navegador web e digite o seguinte endereço na barra de endereços:

   `http://localhost:3000`


#### 📝 Observação
Se você encontrar algum problema ou a página não carregar, verifique as mensagens no terminal para possíveis erros e certifique-se de que o servidor está rodando corretamente. Caso precise de mais assistência, consulte a seção de [Autores] e entre em contato conosco.


## 🛠️ Estrutura do Projeto
Mantivemos uma estrutura organizada para facilitar a manutenção e a compreensão do código:

#### ⚙️ Backend e 🎨 Frontend

- **db/**
    - `app.db` - Base de dados.
    - `connection.js` - Arquivo para configuração de conexão com o banco de dados.
- **models/** - Modelos de dados.
    - `job.js`
- **public/** - Recursos estáticos.
    - **css/** - Arquivos CSS.
    - **img/** - Imagens.
- **routes/** - Rotas da aplicação.
    - `jobs.js`
- **views/** - Arquivos de templates.
    - **layouts/** - Layout principal
    - Outros arquivos `.handlebars` para diferentes páginas.
- `app.js` - Arquivo principal da aplicação.
- `add.html` - Página de adição de vagas.
- `index.html` - Página principal.
- `docker-compose.yml` - Arquivo para orquestração do Docker.
- `Dockerfile` - Arquivo de definição da imagem Docker.
- `package.json` e `package-lock.json` - Dependências do Node.js.
- `README.md` - Documentação do projeto.

  ---
## 🚀 Tecnologias Utilizadas

| Ferramenta       | Descrição                                         |
| ---------------- | ------------------------------------------------- |
| ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)      | Usado para criar a API                            |
| ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)          | Banco de dados utilizado para armazenar os dados |
| ![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)   | Framework para criar o servidor da API            |
| ![HTML, CSS, JS](https://img.shields.io/badge/HTML%20/%20CSS%20/%20JS-000000?style=for-the-badge&logo=html5&logoColor=white) | Criação da interface e visualização dos dados     |
| ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)       | Conteinerização da aplicação                      |
| ![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white) | Editor de código utilizado no desenvolvimento     |
| ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)     | Ferramenta para testar e documentar APIs          |
| ![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)    | Sistema operacional utilizado durante o desenvolvimento  |

## 📝 Autores

| [<img loading="lazy" src="https://avatars.githubusercontent.com/u/131407565?v=4" width=115><br><sub>Danilo Vaz</sub>](https://github.com/danilovaz7) | [<img loading="lazy" src="https://avatars.githubusercontent.com/u/132524175?v=4" width=115><br><sub>João Castro</sub>](https://github.com/joaocastro95) |
| --- | --- |
