O projeto consiste em uma lista de tarefas onde é possível adicionar 
e remover tarefas, além de marcar quais foram concluídas.
O projeto foi desenvolvido em FLASK e possui um sistema de login simples para autenticação dos usuários.

Foram utilizadas as seguintes tecnologias:
- Python 3
- Flask
- Flask-Login
- Flask-SQLAlchemy
- SQLite
- HTML / CSS (style.css)

Funcionalidades do app:
- Adicionar tarefas
- Marcar tarefas como concluídas
- Editar tarefas
- Deletar tarefas
- Sistema de login e signup com usuários individuais
- Cada usuário vê apenas suas próprias tarefas
- API REST para listar tarefas em formato JSON

## ⚙️ Como rodar localmente

```bash
# Criar ambiente virtual
python -m venv .venv

# Ativar ambiente virtual
# Windows PowerShell
.venv\Scripts\Activate.ps1
# Linux/Mac
source .venv/bin/activate

# Instalar dependências
pip install -r requirements.txt

# Rodar a aplicação
python app.py
