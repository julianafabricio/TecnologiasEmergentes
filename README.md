# 🛒 EcommerceBemBarato

Sistema web de anúncios e vendas de produtos com gerenciamento de usuários, categorias, perguntas, anúncios e relatórios.

---

## 💻 Ambiente de Desenvolvimento

- **Sistema Operacional:** Windows 10/11  
- **Editor:** VSCode  
- **Terminal:** PowerShell / CMD  
- **Banco de Dados:** MySQL 5.7+  
- **Servidor Web:** Flask (Python)  

---

## 🧰 Tecnologias Utilizadas

- Python 3.10+  
- Flask  
- Flask-SQLAlchemy  
- Flask-Login  
- MySQL  
- HTML/CSS com Jinja2 (templates)  

---

## 🚀 Como Instalar e Executar

### 1. Clonar o repositório

```bash
git clone https://github.com/seu-usuario/EcommerceBemBarato.git
cd EcommerceBemBarato
```

### 2. Criar ambiente virtual e ativar

```bash
python -m venv venv
venv\Scripts\activate
```

### 3. Instalar dependências

```bash
pip install -r requirements.txt
```

### 4. Configurar Banco de Dados

- Crie um banco no MySQL chamado `banco_bembarato`  
- Altere a URI de conexão no `app.py`, se necessário:

```python
app.config['SQLALCHEMY_DATABASE_URI'] = 'mysql://usuario:senha@localhost:3306/banco_bembarato'
```

### 5. Criar tabelas

```bash
python
>>> from app import db
>>> db.create_all()
>>> exit()
```

### 6. Rodar Aplicação

```bash
python app.py
```

---

## 📋 Requisitos de Sistema

- Python 3.10+  
- MySQL Server 5.7+  
- Pip (gerenciador de pacotes do Python)  

---

## 🤝 Como Contribuir

1. Faça um fork  
2. Crie uma branch:  
   ```bash
   git checkout -b feature/NomeDaFeature
   ```
3. Faça commit das mudanças:  
   ```bash
   git commit -m 'Adiciona nova funcionalidade'
   ```
4. Faça push para o repositório remoto:  
   ```bash
   git push origin feature/NomeDaFeature
   ```
5. Crie um Pull Request

---

## 🧼 Código Limpo

- Uso de nomes descritivos  
- Organização por responsabilidade (views, models, templates)  
- Senhas criptografadas com hash seguro  
- Rotas protegidas com `@login_required`  
- Aplicação do padrão MVC (Model-View-Controller)


## 📄 Licença

Este projeto é apenas para fins educacionais.
