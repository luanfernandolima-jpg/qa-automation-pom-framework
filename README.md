# 🚖 QA Automation POM Framework

Framework de automação de testes para o sistema **Urban Routes**, desenvolvido em **Python + Selenium WebDriver**, utilizando o padrão **Page Object Model (POM)** para garantir organização, reutilização e escalabilidade dos testes.

---

## 📂 Estrutura do Projeto

- `data/` → Dados e variáveis de configuração (ex: URLs, endereços de teste).
- `pages/` → Classes de páginas seguindo o padrão POM (ex: `UrbanRoutesPage`).
- `tests/` → Scripts de testes automatizados (ex: `test_main.py`).
- `utils/` → Funções auxiliares (ex: `helpers.py`).
- `requirements.txt` → Lista de dependências do projeto.

---

## 🚀 Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/qa-automation-pom-framework.git
   cd qa-automation-pom-framework

2. Intalar as dependências com: 
    ```bash
   pip install -r requirements.txt
3. Rodar o teste. 
   ```bash
   pytest tests/

