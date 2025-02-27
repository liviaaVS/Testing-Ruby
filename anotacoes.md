### **Rails - Comandos Essenciais**

#### **1. Gerenciador de Pacotes**
- `bundle install` → Instala as dependências do projeto.
- **Bundle** é o gerenciador de pacotes do Ruby.
- **Gemfile** → Arquivo que define os requisitos do sistema (dependências).

#### **2. Modelos (Models)**
- `bin/rails g model User name` → Gera um modelo `User` com um campo `name`.
- `bin/rails g model NomeModelo nome:tipo` → Gera um modelo com um campo específico (se for `string`, não precisa especificar).
- `bin/rails db:migrate` → Aplica as migrações do banco de dados.

#### **3. Console e Servidor**
- `bin/rails console` → Abre o console interativo do Rails.
- `rails s` → Inicia o servidor da aplicação.

#### **4. Controllers**
- `bin/rails g controller users index` → Cria um controller `UsersController` com a ação `index` (CRUD padrão).

#### **5. Rotas**
- `rails routes` → Lista todas as rotas disponíveis no sistema.
- `rails routes -c users` → Lista as rotas relacionadas ao controller `UsersController`.

#### **6. Arquitetura**
- Rails segue o padrão **MVC (Model-View-Controller)**.