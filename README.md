# 🎓 Gerenciador de Alunos com PHP e PDO

Bem-vindo ao **Gerenciador de Alunos**, um sistema desenvolvido em PHP procedural com PDO para facilitar a administração de cadastros de estudantes de forma segura, prática e intuitiva. Com um design moderno baseado no tema **Admin LTE**, o sistema oferece uma interface responsiva e fácil de usar.

---

## 🎯 Recursos Principais

### 🔐 Área de Login e Cadastro
- **Segurança Avançada:** Senhas totalmente criptografadas.
- **Cadastro de Usuários:** Novo usuário pode se registrar através de um link simples.

### 🧑‍🎓 Gerenciamento de Alunos
- **Acesso Individualizado:** Cada usuário gerencia apenas os seus alunos.
- **Dados dos Estudantes:** Nome, idade, telefone, e-mail e outras informações relevantes.

### 👤 Perfil do Usuário
- **Edição Completa:** Atualize nome, e-mail, senha e foto de perfil.
- **Interface Intuitiva:** Rápida e fácil de usar.

### 📊 Relatórios e Exportações
- **DataTable Avançado:** Busca, ordenação e filtros inteligentes.
- **Exportações:** Gere relatórios em PDF ou exporte para planilhas XLSX.

---

## 🛠️ Tecnologias Utilizadas
- **Backend:** PHP procedural + PDO  
- **Banco de Dados:** MySQL  
- **Frontend:** HTML, CSS, JavaScript  
- **Tema:** Admin LTE  

---

## 📚 Como Instalar no Servidor Local

### 1. Clone o repositório
```bash
git clone https://github.com/levi835/Gerenciador-de-alunos.git

### 2. Configure o ambiente local
- Utilize **XAMPP**, **WAMP**, **MAMP** ou outro servidor PHP/MySQL.
- Coloque o projeto na pasta:
  - `htdocs` (XAMPP)  
  - `www` (WAMP)

---

### 3. Configure o banco de dados
1. Inicie o serviço **MySQL**.
2. Acesse o phpMyAdmin:

*(Este arquivo contém a estrutura completa do Gerenciador de Alunos.)*

---

### 4. Configure a conexão com o banco
Edite o arquivo `config.php` e ajuste os campos:

- **host**
- **usuário**
- **senha**
- **nome do banco**

Exemplo:
```php
$host = "localhost";
$user = "root";
$pass = "";
$dbname = "seu_banco";

