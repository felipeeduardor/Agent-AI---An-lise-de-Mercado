 # 🤖 Agent AI - Análise de Mercado com IA
                                                                                                                             
  Agent AI que pesquisa, coleta e analisa automaticamente empresas de qualquer setor do mercado brasileiro — entregando
  insights competitivos em minutos.

  ## 🎯 O que faz

  Você digita um setor de mercado. O agente faz o resto:

  - 🔍 Busca os principais players do setor
  - 🕸️  Coleta informações reais dos sites de cada empresa
  - 💡 Gera análise competitiva com prós, contras e recomendações estratégicas

  ## 🚀 Como funciona

  Termo de busca → Exa AI → Web scraping → GPT-4o-mini → Relatório

  1. **Exa AI** busca semanticamente as principais empresas do setor
  2. Para cada empresa, coleta o conteúdo real do site
  3. **GPT-4o-mini** gera um relatório estruturado com:
     - Introdução e resumo da empresa
     - Prós e contras competitivos
     - Análise de mercado + recomendações estratégicas
  4. **Gradio** entrega tudo numa interface web simples

  ## 🛠️  Stack

  - [Exa AI](https://exa.ai) — busca semântica
  - [OpenAI API](https://openai.com) — GPT-4o-mini
  - [Gradio](https://gradio.app) — interface web
  - Google Colab — ambiente de execução

  ## ⚙️  Como usar

  1. Abra o notebook no Google Colab
  2. Configure suas chaves de API:
     - `OPENAI_API_KEY`
     - `EXA_API_KEY`
  3. Execute todas as células
  4. Na interface Gradio, digite o setor e número de empresas
  5. Receba o relatório completo

  ## 📋 Exemplo de output

  **Setor:** mercado de nutrição bovina no Brasil

  O agente encontra 15 empresas e gera para cada uma:
  - Resumo da empresa
  - Pontos fortes e fracos
  - Posicionamento no mercado
  - Recomendações estratégicas
