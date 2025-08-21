# 🗣️ Ferramenta Para Análise de Conteúdo Socioambiental

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/resiliencia-socioecologica-ic/Ferramenta_de_Analise_de_Conteudo/blob/main/Ferramenta_de_Analise_de_Conteudo.ipynb)


Uma ferramenta de código aberto, desenvolvida como um notebook Python interativo, para apoiar a análise de conteúdo em pesquisas qualitativas. O projeto automatiza e enriquece o fluxo de trabalho do pesquisador, desde a transcrição de mídias até a codificação e análise temática.

## 🎯 O Problema

Pesquisadores que analisam entrevistas, depoimentos e outros tipos de mídia frequentemente dependem de softwares comerciais caros ou recorrem a alternativas gratuitas. Contudo, as ferramentas gratuitas geralmente não são tão completas em funcionalidades quanto as pagas, o que torna necessário o uso de um conjunto de ferramentas desconectadas para realizar a análise completa. Essa fragmentação torna o processo manual, demorado e, muitas vezes, impede análises mais profundas.

## 💡 A Solução

Este notebook centraliza todo o fluxo de análise em um único ambiente. Ele foi projetado para ser executado prioritariamente no Google Colab, que oferece de forma nativa os elementos de interface (como botões e menus) que dispensam a interação direta com o código. Com essas interfaces gráficas simples, a ferramenta permite que pesquisadores, mesmo com pouca ou nenhuma experiência em programação, utilizem técnicas avançadas de Processamento de Linguagem Natural (PLN) para explorar seus dados.

**-> [Clique aqui para abrir e executar a ferramenta diretamente no Google Colab.](https://colab.research.google.com/github/resiliencia-socioecologica-ic/Ferramenta_de_Analise_de_Conteudo/blob/main/Ferramenta_de_Analise_de_Conteudo.ipynb)**

---

## 🛠️ Funcionalidades

A ferramenta é organizada em um fluxo sequencial e oferece um robusto conjunto de análises:

* **🎙Transcrição Automática:** Utiliza o modelo **Whisper (OpenAI)** para gerar transcrições precisas de múltiplos arquivos de áudio e vídeo, com a opção de analisar os textos de forma individual ou conjunta.

* **☁Análise Exploratória Visual:**
    * **Nuvem de Palavras e Gráfico de Frequência:** Identifique rapidamente os termos mais recorrentes nos textos.
    * **Grafo de Coocorrência:** Visualize um "mapa de ideias" que mostra quais palavras importantes aparecem juntas, revelando as principais associações temáticas.

* **Reconhecimento de Entidades Nomeadas (NER):** Mapeie rapidamente os principais atores e lugares de um discurso, identificando automaticamente nomes de **Pessoas (PER)**, **Locais (LOC)** e **Organizações (ORG)**.

* **Busca Interativa:** Encontre frases relevantes através da busca por palavras-chave:
    * **Busca Exata (Booleana):** Utilize operadores (`AND`, `OR`) para consultas precisas.
    * **Busca por Lema:** Encontre todas as variações de uma palavra (ex: `poluir` encontra "poluiu", "poluição", "poluindo").
    * **Busca Semântica (Contexto):** Pesquise por uma ideia ou frase e encontre trechos com significado similar, mesmo que usem palavras diferentes.
    * **Busca Semântica (Palavras Similares):** Encontre trechos que contenham ideias similares à sua palavra-chave.

* **Codificação Manual e Automática:**
    * **Auto-Codificação Semântica:** Crie um dicionário de códigos e conceitos (`IMPACTO_AMBIENTAL: desmatamento, contaminação do rio`) e deixe a ferramenta pré-codificar automaticamente os segmentos relevantes com base na similaridade de significado.
    * **Interface de Codificação Manual:** Revise, adicione ou remova códigos em cada segmento do texto através de uma interface interativa, garantindo total controle sobre a análise final.
    * **Análise de Códigos:** Após a codificação, visualize a frequência de cada código em um gráfico e recupere facilmente todos os segmentos associados a um tema específico.

## 🔓 Código Aberto e Expansível

Por ser uma solução de código aberto, esta ferramenta se destaca pela flexibilidade. A comunidade de pesquisadores pode adaptar o código, expandir funcionalidades e integrar novas metodologias para atender a necessidades emergentes. Sua contribuição é muito bem-vinda!

---

## 🎓 Autoria e Apoio

Esta ferramenta foi desenvolvida por **Gabriel de Antonio Mazetto** como parte de seu projeto de Iniciação Científica (PIBIC/CNPq/INPE) durante o período de Agosto/2024 a Agosto/2025.

**Orientação e Colaboração:**
* **Orientadora:** Dra. Minella Alves Martins (INPE)
* **Co-orientadora:** Dra. Maria Paula Pires de Oliveira (PUC-Campinas)
* **Colaboradora:** Denise Helena Lombardo Ferreira (PUC-Campinas)

**Apoio Institucional:**
* Este trabalho foi elaborado com apoio do **Conselho Nacional de Desenvolvimento Científico e Tecnológico (CNPq)**, por meio de bolsa PIBIC/CNPq/INPE, e da **Coordenação de Aperfeiçoamento de Pessoal de Nível Superior - Brasil (CAPES)** – Código de Financiamento 001.

---
