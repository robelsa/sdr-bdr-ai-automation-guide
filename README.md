# IA Aplicada a Pré-Vendas B2B: SDRs, BDRs e Automação com NotebookLM

[Acesse o Notebook LM](https://notebooklm.google.com/notebook/492ad8a7-e19a-473f-b0cc-a844ba9f3175)

Projeto desenvolvido para o desafio da DIO sobre o uso de Inteligência Artificial como ferramenta de aprendizagem ativa, curadoria de fontes e organização do conhecimento com NotebookLM.

Repositório: `sdr-bdr-ai-automation-guide`

## Contexto

O tema escolhido para este caderno temático foi o uso de Inteligência Artificial em pré-vendas B2B, com foco nas rotinas de SDRs, BDRs e equipes de RevOps.

Em vendas B2B, profissionais de pré-vendas lidam diariamente com pesquisa de contas, priorização de leads, personalização de mensagens, follow-ups, atualização de CRM e qualificação de oportunidades. A IA pode apoiar essas tarefas ao organizar dados, sugerir mensagens, identificar padrões e acelerar pesquisas. Ao mesmo tempo, o uso de IA exige senso crítico: dados ruins geram respostas ruins, automação sem estratégia prejudica a experiência do prospect e respostas de IA precisam ser validadas em fontes confiáveis.

Este projeto usa o NotebookLM como ferramenta de estudo para transformar fontes abertas em um miniguia prático sobre como aplicar IA de forma responsável e produtiva em pré-vendas B2B.

## Objetivos do Estudo

1. Entender como a IA está mudando a rotina de SDRs e BDRs.
2. Mapear casos de uso práticos de IA em prospecção, qualificação e cadências.
3. Identificar limites, riscos e cuidados no uso de automação em vendas.
4. Criar prompts reutilizáveis para estudar, revisar e aplicar o tema.
5. Produzir um miniguia de estudo organizado para consulta futura e portfólio.

## Curadoria de Fontes

As fontes abaixo foram selecionadas para alimentar o caderno no NotebookLM. A ideia foi combinar relatórios de mercado, artigos de análise e documentação oficial da ferramenta utilizada.

| Fonte | Tipo | Link | Por que foi escolhida |
|---|---|---|---|
| Salesforce State of Sales, 7th Edition | Relatório de mercado | https://www.salesforce.com/en/wp-content/uploads/sites/4/documents/reports/sales/salesforce-state-of-sales-report-2026.pdf | Traz dados recentes sobre vendas, IA, agentes, qualidade de dados e produtividade comercial. |
| HubSpot 2025 State of Sales Report | Relatório/artigo de tendências | https://blog.hubspot.com/sales/hubspot-sales-strategy-report | Mostra desafios atuais de vendas, uso de IA por compradores e vendedores, e mudanças no papel do vendedor. |
| McKinsey - The economic potential of generative AI | Pesquisa executiva | https://www.mckinsey.com/capabilities/tech-and-ai/our-insights/the-economic-potential-of-generative-ai-the-next-productivity-frontier | Ajuda a entender impactos de IA generativa em marketing e vendas, incluindo produtividade e personalização. |
| Google NotebookLM Help - Add or discover sources | Documentação oficial | https://support.google.com/notebooklm/answer/16215270 | Fonte oficial para entender como adicionar fontes, usar pesquisa e organizar materiais no NotebookLM. |
| Apollo.io | Página de produto/ferramenta | https://www.apollo.io/pt | Exemplo prático de plataforma usada em prospecção B2B, enriquecimento de dados e cadências comerciais. |

## Como Configurei o NotebookLM

Nome do caderno:

`IA em Pré-Vendas B2B: SDRs, BDRs e RevOps`

Fontes adicionadas:

1. Relatório Salesforce State of Sales.
2. Artigo/relatório HubSpot State of Sales.
3. Artigo McKinsey sobre potencial econômico da IA generativa.
4. Documentação oficial do NotebookLM.
5. Página da Apollo.io como exemplo de ferramenta de mercado.

## Engenharia de Prompts

Durante o estudo, usei prompts em quatro categorias: compreensão, comparação, aplicação prática e revisão crítica.

### Prompt 1 - Resumo Executivo

```texto
Com base apenas nas fontes adicionadas ao caderno, crie um resumo executivo sobre IA em pré-vendas B2B. Estruture em: contexto, principais tendências, impacto para SDRs/BDRs, riscos e recomendações práticas.
```

Resultado esperado: uma visão geral e uma explicação do tema de forma clara.

### Prompt 2 - Conceitos Fundamentais

```texto
Explique os conceitos SDR, BDR, RevOps, ICP, lead scoring, intent data, cadência comercial e automação de vendas. Para cada conceito, traga uma definição simples, um exemplo prático e um cuidado importante.
```

Resultado esperado: base para o glossário.

### Prompt 3 - Comparação Antes e Depois

```texto
Compare a rotina de um SDR antes e depois do uso de IA. Considere pesquisa de contas, personalização, priorização de leads, follow-up, CRM e qualificação. Mostre também quais tarefas continuam exigindo julgamento humano.
```

Resultado esperado: entender onde a IA ajuda e onde o humano continua essencial.

### Prompt 4 - Guia de Implementação

```texto
Crie um plano de implementação de IA em pré-vendas para uma empresa B2B pequena ou média. Divida em 30, 60 e 90 dias. Inclua objetivos, atividades, responsáveis, métricas e riscos.
```

Resultado esperado: framework prático de aplicação.

### Prompt 5 - Revisão Crítica

```texto
Revise a resposta anterior como se você fosse um gestor de RevOps. Aponte lacunas, riscos, dados que precisam de validação e perguntas que deveriam ser feitas antes de implementar a solução.
```

Resultado esperado: evitar uma resposta superficial.

### Prompt 6 - Prompts para Revisão

```texto
Crie 10 perguntas de revisão para eu testar se entendi o tema IA em pré-vendas B2B. Separe em nível iniciante, intermediário e avançado. Depois, gere um gabarito comentado.
```

Resultado:  

## Cicatrizes e Troubleshooting

### 1. Respostas genéricas

Problema: o NotebookLM respondeu com frases muito amplas, sem exemplos concretos.

Como ajustei: pedi para responder "com base apenas nas fontes" e exigir exemplos, riscos e aplicações práticas.

### 2. Excesso de foco em ferramenta

Problema: algumas respostas davam a entender que comprar uma ferramenta resolveria o processo comercial.

Como ajustei: incluí perguntas sobre processo, dados, treinamento, CRM, governança e métricas.

### 3. Números sem contexto

Problema: relatórios de mercado trazem estatísticas que podem variar por amostra, país, setor e ano.

Como ajustei: passei a registrar fonte, data e contexto antes de usar qualquer número no miniguia.

### 4. Prompts muito longos

Problema: prompts com muitas tarefas geravam respostas confusas.

Como ajustei: dividi em etapas: primeiro resumo, depois glossário, depois comparação, depois plano prático.

### 5. Falta de visão crítica

Problema: a IA tende a listar benefícios e pode reduzir os riscos.

Como ajustei: usei prompts pedindo limitações, riscos, pré-condições e perguntas de diagnóstico.

## Miniguia de Estudo

### 1. O que é IA em pré-vendas B2B?

É o uso de modelos de IA, automações e análise de dados para apoiar atividades anteriores ao fechamento da venda, como pesquisa de empresas, identificação de leads, priorização de contas, criação de mensagens personalizadas e qualificação inicial.

### 2. Onde a IA ajuda SDRs e BDRs?

- Pesquisa de contas e segmentos.
- Criação de listas com critérios de ICP.
- Priorização de prospects com maior potencial.
- Sugestão de mensagens personalizadas.
- Resumo de informações sobre empresas.
- Preparação para calls.
- Registro e organização de informações no CRM.
- Análise de padrões em ganhos e perdas.

### 3. Onde a IA não substitui o humano?

- Construir relação com o prospect.
- Interpretar contexto político e emocional da compra.
- Negociar prioridades e objeções complexas.
- Validar se uma oportunidade realmente faz sentido.
- Tomar decisões éticas sobre abordagem, dados e privacidade.

### 4. Framework simples de implementação

#### Primeiros 30 dias: diagnóstico

- Mapear processo atual de prospecção.
- Definir ICP e critérios de qualificação.
- Identificar tarefas repetitivas.
- Auditar qualidade dos dados no CRM.
- Escolher um caso de uso pequeno para piloto.

#### Dias 31 a 60: piloto

- Testar IA em pesquisa de contas e personalização.
- Criar biblioteca de prompts.
- Medir tempo economizado e qualidade das respostas.
- Coletar feedback dos SDRs/BDRs.
- Ajustar cadências e critérios de lead scoring.

#### Dias 61 a 90: escala controlada

- Padronizar prompts e playbooks.
- Treinar o time.
- Integrar aprendizados ao CRM e ao processo comercial.
- Criar dashboard de métricas.
- Revisar riscos de dados, privacidade e qualidade.

### 5. Métricas para acompanhar

- Tempo médio de pesquisa por conta.
- Taxa de resposta por cadência.
- Conversão de lead para oportunidade.
- Qualidade dos dados no CRM.
- Volume de leads qualificados por semana.
- Taxa de reuniões agendadas.
- Motivos de perda.
- Aderência dos SDRs ao processo.

## Glossário

| Termo | Definição |
|---|---|
| SDR | Profissional focado em prospectar, abordar e qualificar leads, geralmente inbound ou outbound. |
| BDR | Profissional focado em desenvolvimento de novos negócios, muitas vezes com prospecção outbound e contas estratégicas. |
| RevOps | Área que integra vendas, marketing, sucesso do cliente, dados, processos e ferramentas para melhorar receita. |
| ICP | Perfil de Cliente Ideal; define quais empresas têm maior fit com a solução. |
| Lead Scoring | Método para pontuar leads de acordo com fit, interesse e comportamento. |
| Intent Data | Sinais que indicam possível interesse de compra, como pesquisas, visitas, downloads ou comportamento digital. |
| Cadência | Sequência planejada de contatos por e-mail, telefone, LinkedIn, WhatsApp ou outros canais. |
| CRM | Sistema usado para registrar e acompanhar relacionamento com leads, oportunidades e clientes. |
| Enriquecimento de Dados | Processo de complementar dados de uma conta ou contato com informações adicionais. |
| Handoff | Passagem de um lead qualificado do SDR/BDR para o executivo de vendas. |
| Automação | Uso de sistemas para executar tarefas repetitivas com pouca intervenção manual. |
| Prompt | Instrução escrita para orientar uma IA a gerar uma resposta ou executar uma tarefa. |

## Prompts Reutilizáveis

```texto
1. Resuma esta fonte em 10 bullets e destaque os pontos mais importantes para SDRs.
```

```texto
2. Liste os principais riscos de aplicar IA em pré-vendas sem uma estratégia de dados.
```

```texto
3. Crie uma cadência de prospecção B2B com 5 etapas para uma empresa SaaS, incluindo objetivo, canal e mensagem de cada etapa.
```

```texto
4. Gere um checklist para avaliar se uma empresa está pronta para usar IA em pré-vendas.
```

```texto
5. Compare lead scoring tradicional, lead scoring com IA e intent data em uma tabela.
```

```texto
6. Crie perguntas de entrevista para uma vaga de SDR que exige conhecimento de IA e automação.
```

```texto
7. Transforme os aprendizados deste caderno em um post de LinkedIn com linguagem profissional.
```

```texto
8. Aponte quais afirmações deste resumo precisam de fonte, validação ou cuidado antes de serem publicadas.
```

## Aprendizados Finais

Este projeto mostrou que a IA pode ser uma ferramenta poderosa de aprendizagem e produtividade, mas seu valor depende da qualidade das fontes, da clareza dos prompts e da capacidade humana de revisar criticamente as respostas.

Para SDRs e BDRs, a IA não deve ser vista apenas como automação de mensagens. O maior ganho está em estudar melhor o mercado, priorizar contas com mais critério, personalizar abordagens com responsabilidade e transformar dados em decisões comerciais melhores.
