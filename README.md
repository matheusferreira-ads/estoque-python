# estoque-python
PROJETO DE APP PARA GESTÃO DE ESTOQUE E AUDITORES DE ESTOQUE  

📦 Sistema Inteligente de Gestão de Estoque & Validade
Este projeto foi desenvolvido para resolver o problema crítico da contagem manual de estoque e a perda de produtos por vencimento. Utilizando Python e a metodologia FEFO (First Expired, First Out), a aplicação automatiza o controle de inventário e prioriza a saída de itens com validade próxima.

🚀 Funcionalidades
Contagem Automatizada: Substitui planilhas de papel por uma interface web intuitiva para entradas e saídas.

Monitoramento de Validade: Aba exclusiva para gestão de lotes com alertas automáticos (Vencido, Crítico, Regular).

Logística Inteligente: Ordenação automática por data de validade (estratégia FEFO).

Exportação de Dados: Geração de relatórios em CSV para análise externa.

Banco de Dados Persistente: Armazenamento seguro utilizando SQLite.

🛠️ Tecnologias Utilizadas
Linguagem: Python 3.12

Interface Web: Streamlit

Análise de Dados: Pandas

Banco de Dados: SQLite3

🏗️ Arquitetura do Projeto

O sistema foi construído seguindo princípios de modularização, separando a lógica de banco de dados da interface do usuário, facilitando a manutenção e futuras escalabilidades.

⚙️ Como executar o projeto localmente
Certifique-se de ter o Python 3.12+ instalado.

Clone este repositório.

Crie um ambiente virtual:

Bash
python -m venv venv

Ative o ambiente e instale as dependências:

Bash
pip install streamlit pandas

Execute a aplicação:

Bash
streamlit run app.py


👨‍💻 Sobre o Autor

Matheus Ferreira
Estudante de Análise e Desenvolvimento de Sistemas (TADS). Apaixonado por automação de processos e desenvolvimento de soluções que geram valor real para o negócio.
