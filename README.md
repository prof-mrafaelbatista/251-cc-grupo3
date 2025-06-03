# 📘 Projeto Final – Introdução à Programação

**Colaboradores:**  
Bruno de Araújo, Rebecca Cândido, Kaike Araújo e Caio Simões

Este projeto é uma aplicação web desenvolvida como trabalho final da disciplina **Introdução à Programação**, utilizando o framework **Flask** em Python. O objetivo é apresentar os principais conceitos de programação aplicados em um sistema real e funcional.

Desenvolvido como parte da disciplina de **Introdução à Programação – Curso de Ciência da Computação**.

---

## 📚 Funcionalidades

- 🔍 **Visualizar termos**: Exibe todos os termos cadastrados em uma tabela com número, termo e definição.  
- ➕ **Adicionar termo**: Formulário para inserir um novo termo e sua definição. Termos duplicados são ignorados.  
- ❌ **Excluir termo**: Cada termo possui um botão "Apagar" que permite sua remoção, com confirmação do usuário.  
- ✅ **Editar termo**: Termos podem ser editados diretamente via modal com atualização da definição.  
- 📀 **Persistência em arquivo**: Todos os dados são armazenados em um arquivo `bd_glossario.csv`, utilizando o separador `;`.  
- 🤖 **Integração com IA**: O sistema inclui uma página que permite perguntar dúvidas sobre programação para a IA Google Gemini.

---

## 🛠️ Tecnologias Utilizadas

- Python 3  
- Flask  
- HTML5  
- Bootstrap 5  
- CSV (para armazenamento de dados)

---

## 📁 Estrutura do Projeto

```
Projeto_Final_ip_cc/
│
├── static/              # Arquivos CSS e recursos estáticos
├── templates/           # Arquivos HTML (modelo base e páginas)
│   ├── modelo.html
│   ├── glossario.html
│   ├── novo_termo.html
│   ├── gemini.html
│   ├── fundamentos.html
│   └── equipe.html
│
├── bd_glossario.csv     # Arquivo com os termos cadastrados
├── app.py               # Código principal em Flask
├── README.md            # Documentação do projeto
└── LICENSE              # Licença MIT
```

---

## 🚀 Como Executar?

1. Clone o repositório:

```bash
git clone https://github.com/Uuiskas/Projeto_Final_ip_cc.git
cd Projeto_Final_ip_cc
```

2. Crie um ambiente virtual e instale o Flask:

```bash
python -m venv venv
# Ative o ambiente:
source venv/bin/activate      # Linux/macOS
venv\Scripts\activate       # Windows

# Instale as dependências:
pip install flask
```

3. Execute a aplicação:

```bash
flask run
```

---

## 📅 Observações

- O projeto foi desenvolvido com foco **didático**, sem uso de banco de dados relacional.
- Enfatiza a **manipulação de arquivos**, uso de **formulários HTML** e **rotas no Flask**.
- Inclui exemplos de **estruturas condicionais**, **laços de repetição**, **listas**, **exceções** e **funções** estudadas ao longo da disciplina.

---

## 📄 Licença

Distribuído sob a licença **MIT**. Consulte o arquivo `LICENSE` para mais detalhes.
