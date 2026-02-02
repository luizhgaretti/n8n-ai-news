# 🤖 n8n AI News Digest

## ✨ Funcionalidades
* **Coleta Automática:** Busca notícias de IA das últimas 24h via Google News RSS.
* **Resumos Individuais:** IA cria um resumo de 2 frases para cada link.
* **Visão Executiva:** Gera uma análise das tendências principais observadas no dia.
* **Notificação Clean:** Mensagem formatada enviada diretamente para o Slack.

## 🚀 Como Usar
1.  **Importar:** No seu n8n, vá em `Import from File` e selecione o arquivo `workflow.json`.
2.  **Configurar IA:** Conecte sua credencial da OpenAI ou Azure no node de modelo (GPT-4o ou similar).
3.  **Configurar Slack:** Insira seu *Bot Token* e selecione o canal de destino.
4.  **Ativar:** Mude a chave para `Active` para receber os resumos diariamente.

## 🛠️ Stack Técnica
* **n8n** (Orquestração de fluxo)
* **OpenAI / Azure OpenAI** (Processamento de Linguagem Natural)
* **Google News RSS** (Fonte de dados)
* **Slack** (Interface de entrega)
