# 📝 Gerador de Redações com Gemini + LangGraph

Este projeto é um agente inteligente que:
- Planeja uma redação
- Pesquisa informações em tempo real
- Gera um rascunho
- Critica e revisa o texto automaticamente

Tudo isso usando **Gemini**, **LangGraph**, **Tavily** e **Gradio**.

---

## 🚀 Como rodar o projeto

### 1. Clone o repositório
```bash
git clone https://github.com/SEU_USUARIO/essay-agent.git
cd essay-agent
2. Crie e ative um ambiente virtual
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
3. Instale as dependências
pip install -r requirements.txt
4. Configure o .env
Crie um arquivo .env:

GEMINI_API_KEY= SUA_CHAVE_AQUI
TAVILY_API_KEY= SUA_CHAVE_AQUI
5. Rode a aplicação
python app.py
A interface Gradio abrirá no navegador 🚀

🧠 Tecnologias usadas
Python

Gradio

LangGraph

Gemini (Google Generative AI)

Tavily Search

SQLite (checkpoints)

1️⃣ Estrutura correta do projeto

Antes de tudo, organize os arquivos assim:

Projeto_gerar_redações/
│
├── app.py
├── new_backend.py
├── requirements.txt
├── .gitignore
└── README.md  