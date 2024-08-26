# AI Agent

## Descrição

Construção de um projeto de IA utilizando LLM GPT 3.5-Turbo, Python e CrewAI, com o objetivo de implementar um Agente IA para avaliação de ações (Stocks).

### Importante:

O aplicativo usa LLM da OpenAI, que é executado em consultas pagas feitas para o modelo. Mais informações de crédito e cobrança em: https://platform.openai.com/settings/organization/billing/overview

## Funcionalidades

- **Interface amigável**: UI limpa e fácil de usar com resposta rápida.
- **Análise de tickets do mercado de ações**: verifica o histórico de preços e cria uma análise de tendências - para cima, para baixo ou para os lados.
- **Análise de Notícias**: Verifica as últimas notícias sobre o ativo desejado, gerando um resumo do mercado geral e do ativo. Também informa uma pontuação de medo/ganância baseada em notícias lidas.
- **Previsões**: Com base nas informações coletadas anteriormente, considerações sobre o futuro do ativo serão incluídas no resumo da pesquisa.

##  Status do Projeto

> Em manutenção

## Tecnologias utilizadas

- **Python**
- **OpenAI LLM**
- **CrewAI Python Library**
- **Streamlit**
- **StreamlitCloud**

## Pré-requisitos e como rodar a aplicação

Siga estas etapas para configurar o projeto localmente:

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/laisbrme/aiagent.git
   cd aiagent
   ```
   
2. **Acesse a pasta do projeto:**

   ```bash
   cd webappStocks
   ```

3. **Crie e ative o ambiente virtual:**

   ```bash
   python -m venv venv
   source venv\Scripts\activate #No MacOS: venv/bin/activate
   ```

4. **Instale as dependências:**

   ```bash
   pip install -r requirements.txt
   ```

5. **Execute a aplicação:**

   ```bash
   python crewai_stocks.py
   ```

6. **Acesse o aplicativo em 'http://localhost:5000' em seu navegador**

### Como usar:

1. **Abra a aplicação em seu navegador**
2. **Insira o ticket do ativo desejado**
3. **Clique em 'Run Research' para receber a análise de mercado do ticket desejado**

## ISENÇÃO DE RESPONSABILIDADE

As informações apresentadas na resposta do aplicativo foram geradas através de consultas feitas por um modelo de inteligência artificial e não devem ser consideradas na tomada de decisão de compra de qualquer ativo de qualquer carteira. Consulte um especialista do mercado financeiro devidamente credenciado para trabalhar com seu portfólio.
