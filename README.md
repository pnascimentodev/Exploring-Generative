# Explorando Recursos de IA Generativa com Copilot e OpenAI

## Modelos de Linguagem Grandes (LLMs)

Os aplicativos de IA generativa utilizam LLMs (Modelos de Linguagem Grandes), que são modelos especializados em tarefas de Processamento de Linguagem Natural (PLN). Estes modelos são usados para:

- Determinar o sentimento ou classificar texto.
- Resumir textos.
- Comparar diferentes fontes de texto e analisar a semelhança semântica.
- Gerar novos textos em linguagem natural.

## Modelos de Linguagem Grandes - Arquitetura Transformer

A arquitetura dos modelos transformer é composta por dois componentes principais:

1. **Codificador:** Cria representações semânticas das palavras ou frases do vocabulário de treinamento.
2. **Decodificador:** Gera sequências de linguagem a partir das representações criadas pelo codificador.

O texto é tokenizado, ou seja, transformado em tokens numéricos exclusivos que representam palavras ou frases. Cada token recebe um vetor de inserção (embeddings), e as camadas de atenção analisam a importância das relações semânticas entre os tokens para prever a sequência mais provável de tokens.

## Modelos de Linguagem Grandes - Tokenização

1. **Tokenização:** A primeira etapa no treinamento de um modelo transformer é a decomposição do texto em tokens.
2. **Inserções ou Embeddings:** Cada token é atribuído a um vetor de inserção que captura seu significado semântico.
   
## Modelos de Linguagem Grandes - Atenção

A técnica de atenção é utilizada para capturar a força das relações entre os tokens. Essa técnica permite ao modelo focar em diferentes partes do texto para entender melhor o contexto e gerar respostas mais precisas.

## Copilotos

Copilotos são funcionalidades frequentemente integradas em aplicativos para auxiliar os usuários com tarefas comuns, utilizando IA generativa. Desenvolvedores podem criar copilotos que geram conteúdo a partir de prompts enviados para grandes modelos de linguagem, como os do GPT-4.

## Aprimorando Respostas de IA Generativa com Engenharia de Prompt

A engenharia de prompt é o processo de aprimorar os prompts dados ao modelo para gerar respostas de melhor qualidade. Desenvolvedores e usuários podem melhorar a qualidade das respostas usando linguagens diretas, mensagens de sistema, exemplos ou dados fundamentados.

## Fundamentos do Serviço Azure OpenAI

O **Serviço OpenAI do Azure** é uma solução de nuvem fornecida pela Microsoft para implementar, personalizar e hospedar grandes modelos de linguagem. Ele oferece:

- Modelos de IA generativa pré-configurados.
- Funcionalidades de personalização.
- Ferramentas para detectar e mitigar usos prejudiciais da IA.
- Segurança corporativa com RBAC (controle de acesso baseado em função) e redes privadas.

É possível usar o Azure OpenAI por meio de diferentes métodos, como:

- **Estúdio de IA do Azure**
- **API REST**
- **SDKs com suporte CLI do Azure**

## Como Usar o OpenAI do Azure

### Estúdio Azure OpenAI:
- Permite criar e implantar modelos de IA para aplicativos de software.
- Alimentado por modelos otimizados para tarefas específicas.
- Modelos disponíveis incluem GPT-4, GPT-3.5, Embeddings e DALL-E.

### Playgrounds:
- Permite experimentar os modelos do Azure OpenAI sem a necessidade de codificação.
- Usufrui de uma interface para configurar como o modelo deve se comportar.

## Funcionalidade de Linguagem Natural do OpenAI do Azure

Os modelos GPT são eficazes para entender e gerar linguagem natural. Além disso, eles podem traduzir trechos de código em linguagem natural e vice-versa.

### Geração e Edição de Imagens

Com o **DALL-E**, é possível gerar imagens a partir de descrições, além de editar imagens ou criar variações. A edição pode incluir mudanças no estilo, adição ou remoção de itens, ou até mesmo a criação de novos elementos para incluir na imagem original.

## IA Generativa Responsável

O desenvolvimento de IA generativa responsável segue quatro fases principais:

1. **Identificar**: Reconhecer os riscos e desafios associados ao uso de IA generativa.
2. **Medir**: Avaliar o impacto potencial e os resultados do uso da IA.
3. **Mitigar**: Implementar estratégias para reduzir riscos e impactos negativos.
4. **Operar**: Continuar monitorando e ajustando a solução para garantir o uso responsável.

## Links

- [Laboratório 12 - IA Generativa](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/12-generative-ai.html)
- [Laboratório 13 - Azure OpenAI](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/13-azure-openai.html)
- [Laboratório 14 - Filtros de Conteúdo Azure OpenAI](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/14-azure-openai-content-filters.html)
