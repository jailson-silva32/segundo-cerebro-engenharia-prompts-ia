# evidencias
# Segundo Cérebro: Engenharia de Prompts e Arquitetura de LLMs

Projeto desenvolvido para o desafio **"Treinando uma IA de Aprendizagem: Explore o Poder do NotebookLM"** da DIO, utilizando o **Gemini Notebook** para criar uma base de conhecimento curada e auditável.

## Tema e Objetivo
Atuar como um especialista técnico em Engenharia de Prompts e Arquitetura de LLMs, explicando técnicas avançadas de estruturação de contexto, raciocínio (Chain-of-Thought) e estratégias práticas para reduzir alucinações em modelos de linguagem, estritamente com base nas fontes fornecidas.

## Diretriz de Comportamento Configurada
> "Comporte-se como um Engenheiro de IA Sênior e mentor didático. Responda às perguntas de forma estruturada, objetiva e tecnicamente precisa, baseando-se exclusivamente nas fontes anexadas a este caderno. Sempre que explicar uma técnica, apresente um exemplo prático de aplicação. Caso uma pergunta fuja do escopo das fontes fornecidas, informe claramente que a informação não consta na base de conhecimento atual em vez de supor ou inventar respostas."

## Fontes Selecionadas e Justificativa de Confiança

| Formato | Título / Referência da Fonte | Por que é confiável? |
| :--- | :--- | :--- |
| **Documentação Oficial** | Guia de Engenharia de Prompts (Google AI / OpenAI) | Documentação primária mantida diretamente pelos criadores dos modelos fundacionais. |
| **Artigo Científico (PDF)** | *Chain-of-Thought Prompting Elicits Reasoning in Large Language Models* (Wei et al.) | Paper acadêmico revisado por pares publicado por pesquisadores do Google Research, referência original da técnica CoT. |
| **Vídeo Técnico (YouTube)** | *State of GPT* — Andrej Karpathy | Palestra técnica ministrada por um dos principais pesquisadores de Deep Learning e ex-diretor de IA da Tesla/OpenAI. |
| **Artigo Técnico** | Guia sobre *Retrieval-Augmented Generation (RAG)* (Google Cloud / IBM) | Material de referência arquitetural sobre aterramento de dados (grounding) e redução de alucinações em produção. |

## Evidências de Uso e Citações

### 1. Técnicas de Raciocínio (Zero-Shot vs. Few-Shot vs. Chain-of-Thought)
* **Pergunta feita:** *"Quais são as principais diferenças entre Zero-Shot, Few-Shot e Chain-of-Thought prompting, e quando devo usar cada um?"*
* **Resumo da resposta:** O notebook explicou que Zero-Shot envia a instrução direta sem exemplos; Few-Shot fornece pares de entrada/saída para calibrar o formato; e Chain-of-Thought (CoT) induz o modelo a gerar passos intermediários de raciocínio antes da resposta final, sendo ideal para problemas lógicos e matemáticos complexos.
* **Fontes citadas na resposta:** `[1] Guia de Engenharia de Prompts` e `[2] Paper Chain-of-Thought Prompting (Wei et al.)`.

### 2. Mitigação de Alucinações com RAG
* **Pergunta feita:** *"De acordo com as fontes, por que ocorrem alucinações em LLMs e como a técnica de RAG ajuda a mitigá-las?"*
* **Resumo da resposta:** A resposta detalhou que LLMs preveem o próximo token com base em probabilidades estatísticas e não em verificação factual nativa. O RAG mitiga esse comportamento recuperando documentos externos confiáveis antes da geração e obrigando o modelo a fundamentar a resposta no contexto recuperado.
* **Fontes citadas na resposta:** `[3] Palestra State of GPT` e `[4] Guia Técnico sobre RAG`.

### 3. Otimização da Janela de Contexto
* **Pergunta feita:** *"Crie um checklist prático baseado nas fontes para otimizar o uso da janela de contexto e evitar viés nas respostas."*
* **Resumo da resposta:** Listou práticas como posicionar instruções críticas no início ou no fim do prompt, utilizar delimitadores claros para separar dados de instruções e evitar instruções ambíguas ou tendenciosas.
* **Fontes citadas na resposta:** `[1] Guia de Engenharia de Prompts` e `[3] Palestra State of GPT`.

## Materiais Gerados no Estúdio e Prints
* [Mapa Mental (PNG)](./evidencias/mapa-mental-ia.png)
* [Apresentação de Slides (PDF)](./evidencias/apresentacao-engenharia-prompts.pdf)
* [Print do Chat com Citações](./evidencias/print-chat-citacoes.png)

## Link do Notebook Compartilhado
* **Acesse o Gemini Notebook:** [INSIRA AQUI O LINK PÚBLICO DO SEU NOTEBOOK]
