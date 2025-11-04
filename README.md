# 🚀 Flask REST API CRUD

API REST desenvolvida com **Flask** e **SQLite** e implementando operações completas de **CRUD** (Criar, Ler, Atualizar e Excluir).  
O projeto foi baseado no tutorial [Python REST API for Beginners](https://www.youtube.com/watch?v=z3YMz-Gocmw) e adaptado para fins de aprendizado e portfólio.

---

## 📚 Índice
- [Sobre o Projeto](#-sobre-o-projeto)
- [Funcionalidades](#-funcionalidades)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Instalação e Execução](#-instalação-e-execução)
- [Endpoints da API](#-endpoints-da-api)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Créditos](#-créditos)

---

## 📖 [Sobre o Projeto](#-sobre-o-projeto)

Este projeto tem como objetivo consolidar o aprendizado em **desenvolvimento backend com Python**, utilizando o framework **Flask** para construção de uma **API RESTful**.  
A aplicação implementa as operações CRUD e persistência de dados em um banco de dados **SQLite**, com testes realizados via **Thunder Client**.

---

## ✨ [Funcionalidades](#-funcionalidades)

- 📦 Criação, leitura, atualização e exclusão de registros (CRUD)   
- 🌐 Rotas RESTful com respostas em JSON  
- 💾 Integração com banco de dados SQLite  
- 🧪 Testes de requisições com Thunder Client

---

## 🛠 [Tecnologias Utilizadas](#-tecnologias-utilizadas)

- **Linguagem:** Python  
- **Framework:** Flask  
- **Banco de Dados:** SQLite  
- **Testes de API:** Thunder Client
- **Ambiente Virtual:** venv  

---

## ⚙️ [Instalação e Execução](#-instalação-e-execução)

1. **Clonar o repositório:**
   ```bash
   git clone https://github.com/jeanmcorreia/flask-rest-api-crud.git
   cd flask-rest-api-crud

2. **Criar e ativar o ambiente virtual:**
   ```bash
   python -m venv venv
   source venv/bin/activate # Linux/Mac
   venv\Scripts\activate    # Windows

3. **Instalar as dependências:**
   ```bash
   pip install -r requeriments.txt

4. **Executar aplicação:**
   ```bash
   py api.py

```markdown
A API estará disponível no servidor local em:
👉 `http://localhost:5000/`
```

---

## 🔗 [Endpoints da API](#-endpoints-da-api)

```markdown
| Método | Endpoint      | Descrição                       |
| ------ | ------------- | ------------------------------- |
| GET    | `/users`      | Retorna todos os usuários       |
| POST   | `/users`      | Cria um novo usuário            |
| GET    | `/users/<id>` | Retorna um usuário específico   |
| PATCH  | `/users/<id>` | Atualiza informações do usuário |
| DELETE | `/users/<id>` | Remove um usuário               |
```

---

## 🗂 [Estrutura do Projeto](#-estrutura-do-projeto)

```css
flask-rest-api-crud/
│
├── api.py
├── create_db.py
├── requirements.txt
└── .gitignore
```

## 🙌 [Créditos](#-créditos)

Projeto baseado no tutorial “Python REST API for Beginners” do canal [Dave Gray](https://www.youtube.com/@DaveGrayTeachesCode) · Adaptado e documentado para fins de estudo e portfólio pessoal.

## 💡 Autor
🔗 [LinkedIn](https://www.linkedin.com/in/jeanmarcoscor/)
