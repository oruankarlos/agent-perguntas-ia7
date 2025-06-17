# Agente de IA para Análise de Documentos

Este é um projeto acadêmico que utiliza n8n e um modelo de linguagem do Google para criar um agente de IA capaz de responder perguntas sobre dados contidos em arquivos CSV.

## Arquivos do Projeto

* `workflow.json`: O fluxo completo do n8n, contendo toda a lógica de automação.
* `index.html`: Uma interface de usuário simples para interagir com o agente de IA.

## Como Executar o Projeto

Para rodar este projeto, você precisará ter o **Docker** e o **n8n** instalados e funcionando localmente.

1.  **Baixe os Arquivos:** Faça o download ou clone este repositório para o seu computador.

2.  **Importe o Workflow:**
    * Abra sua instância do n8n.
    * Vá em "Workflows" e clique em "Import from File".
    * Selecione o arquivo `workflow.json` que você baixou.

3.  **Ative o Workflow:** Após importar, abra o workflow e clique no botão **"Active"** no canto superior direito para que o Webhook fique ativo e esperando por requisições.

4.  **Abra a Interface:**
    * Abra o arquivo `index.html` em seu navegador de internet (ex: Google Chrome, Firefox).
    * **Importante:** Dentro do arquivo `index.html`, talvez seja necessário ajustar a URL do webhook na linha 120 para corresponder à URL da sua instância local do n8n.

5.  **Teste:** Digite uma pergunta na interface e clique em "Obter Resposta" para ver o agente em ação.
