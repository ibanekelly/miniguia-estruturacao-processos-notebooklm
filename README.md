# Miniguia de Estudos: Estruturação de Processos
Projeto feito para o Desafio de Projeto da DIO, com foco em usar Inteligência Artificial para aprender de forma mais ativa. O objetivo foi testar o Google NotebookLM como ferramenta para organizar, analisar criticamente, resumir e documentar conhecimentos a partir de diferentes fontes sobre gestão e organização de processos.

## Contexto e Objetivos
Escolhi o tema "Estruturação de Processos" com o objetivo de compreender os conceitos fundamentais de estruturação e modelagem de processos organizacionais, desenvolvendo habilidades para diagnosticar fluxos de trabalho, identificar gargalos e desenhar procedimentos otimizados para futura padronização e automação.

## Curadoria de Fontes
- Metodologia de Gestão de Processos - PDF (https://www.cnmp.mp.br/portal/images/forum_nacional_de_gestao/comites/CPGE/20160404_Metodologia_de_Gest%C3%A3o_de_Processos_4%C2%AA_vers%C3%A3o.pdf)
  
- Estruturação de processos: 5 pilares para criar processos eficientes (https://blogdaqualidade.com.br/estruturacao-de-processos-5-pilares-para-criar-processos-eficientes/)
  
- Mapeamento de processos: o que é, objetivos e como fazer - Zendesk Insights (https://www.zendesk.com.br/blog/zendesk-insights/mapeamento-de-processos/)
  
- Processos organizacionais: o que são, tipos e importância (https://www.levty.com/br/blog/processos-organizacionais-651f263e3715666b16c7d2e6)
  
- Gestão e Mapeamento de Processos - YouTube (https://www.youtube.com/watch?v=j2xgFAAzozU)

## Engenharia de Prompts e "Cicatrizes"

### Cicatriz 1: Falha de Geração e Reenquadramento de Pergunta
- **Prompt que falhou:** "Como sei que preciso dar início à uma estruturação de processos?"
- **Dificuldade/Cicatriz:** A IA retornou o erro "Não foi possível gerar uma resposta".
- **Refinamento aplicado:** Em vez de desistir, a pergunta foi reescrita dividindo o problema em dois blocos claros (gatilhos de início e momentos de execução): "Em que momento é necessária a aplicação da estruturação de processos em uma empresa? Quais são os momentos em que precisaremos colocar em ação o plano?"
- **Resultado:** A IA destravou e respondeu com precisão, listando os sinais de alerta operacionais (queda de métricas, retrabalho, gargalos) e os 4 marcos de ativação do plano 5W2H.

### Cicatriz 2: Da Dúvida Binária à Análise de Cenários (Preventivo vs. Corretivo)
- **Prompt que falhou:** "A estruturação também pode ser feita para aplicação de um processo em criação de uma empresa nova, ou só para efeito corretivo?" (Retornou erro de geração).
- **Refinamento aplicado:** A pergunta foi refraseada com maior clareza de escopo: "Estes métodos também se aplicam para uma empresa recém-fundada que ainda não realiza processos, ou somente tem efeito corretivo de processos existentes?"
- **Resultado e Aprendizado:** A IA gerou uma diferenciação conceitual riquíssima: a **Abordagem Preventiva** (desenho direto do *To-Be* para novos negócios) versus a **Abordagem Corretiva** (diagnóstico do *As-Is* e eliminação de vícios em empresas existentes).

### Cicatriz 3: Controle Rígido de Didática e Formatação de Saída
- **Prompt:** "Mantenha o tom mais didático possível, lembrando que sou nova no assunto, e traga, simplificado, um resumo o mais enxuto possível (poucas linhas por tópico) sem que perca o que é essencial a respeito da estruturação de processos; Estruture da seguinte forma: Introdução, Ferramentas mais indicadas e porquê, Cenários aplicáveis, Tutorial simplificado."
- **Dificuldade/Cicatriz:** O excesso de conteúdo acumulado estava disperso e longo.
- **Refinamento aplicado:** Imposição de restrição de formato com tópicos pré-determinados e limitação de poucas linhas por conceito.
- **Resultado:** A IA gerou a síntese executiva perfeita, limpa e pronta para documentação.

## Resumo Estruturado

### 1. Introdução
**Definição:** Um processo é um conjunto ordenado de atividades que recebe insumos (inputs), agrega valor por meio de transformações e gera entregas (outputs) para clientes internos ou externos.

**Objetivo Principal:** Organizar, padronizar e otimizar as rotinas de trabalho, conectando a operação diária diretamente à missão e às metas estratégicas da organização.

**Principais Benefícios:** Eliminação de gargalos e retrabalhos, padronização da qualidade, aumento da produtividade e redução de custos operacionais.

### 2. Ferramentas Mais Indicadas
As ferramentas não competem entre si; atuam de forma complementar em cada fase do projeto:
**SIPOC:** Constrói a visão macro (Fornecedores, Entradas, Processo, Saídas e Clientes), definindo as fronteiras de início e fim antes do detalhamento.

**Matriz GUT:** Prioriza os problemas ou processos mais críticos com base em Gravidade (impacto), Urgência (prazo) e Tendência (piora).

**Notação BPMN (Bizagi):** Fornece uma linguagem visual universal padronizada (com piscinas e raias) para desenhar o fluxo de atividades de forma clara.

**Diagrama de Ishikawa + 5 Porquês:** Investigam e identificam as causas raízes dos gargalos diagnosticados no fluxograma.

**5W2H:** Transforma a solução em um plano de ação prático respondendo a 7 perguntas (O que, Por que, Onde, Quando, Quem, Como e Custo).

### 3. Cenários Aplicáveis
**Cenário Corretivo (Empresas Existentes):** Focado em identificar dores reais, mapear o estado atual (As-Is), eliminar gargalos e redesenhar o fluxo viciado para recuperar margens e qualidade.

**Cenário Preventivo (Empresas Novas ou Novos Projetos):** Funciona como a "planta baixa" da operação. Projeta diretamente o estado futuro ideal (To-Be) e mapeia riscos com antecedência para evitar que as ineficiências sequer aconteçam.

### 4. Tutorial Simplificado de Aplicação
  1. **Planejar e Priorizar:** Selecionar o processo prioritário com a Matriz GUT e alinhar objetivos com as lideranças.
  2. **Delimitar o Escopo (SIPOC):** Mapear as entradas, saídas e limites de atuação antes de detalhar rotinas.
  3. **Mapear a Realidade Prática (As-Is):** Entrevistar quem executa as tarefas no dia a dia e modelar o fluxograma em BPMN.
  4. **Analisar Causa Raiz:** Descobrir as causas primárias dos atrasos e gargalos com Ishikawa e os 5 Porquês.
  5. **Redesenhar o Fluxo (To-Be):** Eliminar desperdícios, modelar o fluxo otimizado e estruturar o plano de ação 5W2H.
  6. **Implementar e Monitorar:** Capacitar a equipe com Instruções de Trabalho (IT), medir indicadores de desempenho e manter o ciclo de melhoria contínua.

## Glossário
1. **As-Is (Estado Atual):** Representação gráfica e documental de como o processo realmente acontece no dia a dia, incluindo suas falhas, gargalos e improvisos reais.
2. **To-Be (Estado Futuro):** Desenho do modelo de processo reorganizado e otimizado, sem desperdícios, que passará a ser adotado pela organização.
3. **BPMN (Business Process Modeling Notation):** Notação gráfica internacionalmente padronizada que utiliza símbolos específicos (tarefas, eventos, conexões) para desenhar e modelar fluxos de processos de forma compreensível para qualquer área.
4. **SIPOC (Suppliers, Inputs, Process, Outputs, Customers):** Ferramenta de síntese macro que identifica os Fornecedores, Entradas, Etapas Principais, Saídas e Clientes envolvidos no processo.
5. **Gargalo:** Etapa ou obstáculo no fluxo que acumula trabalho, gera atrasos e limita a capacidade geral de produção e entrega da organização.
6. **Matriz GUT:** Matriz de priorização que pontua problemas ou processos com base nas variáveis Gravidade (impacto), Urgência (tempo disponível) e Tendência (piora caso o problema continue).
7. **Diagrama de Ishikawa (Espinha de Peixe/6M):** Ferramenta gráfica usada para investigar as causas raízes de um problema organizando-as em categorias como Método, Mão de Obra, Material, Máquina, Medição e Meio Ambiente.
8. **5W2H:** Matriz de plano de ação estruturada em 7 perguntas (What, Why, Where, When, Who, How, How Much/O que, Por que, Onde, Quando, Quem, Como e Quanto custa).
9. **Baseline (Linha de Base)** | Medição inicial de indicadores (tempo, erros, custo) usada como referência para medir a evolução.
  
## Prompts Reutilizáveis
- **Prompt:** "Preciso relembrar rapidamente o ciclo de estruturação de processos. Gere um checklist em tópicos contendo:
  - As 6 fases metodológicas do planejamento à governança
  - Os 5 pilares de sustentação
  - A função de cada ferramenta (SIPOC, BPMN, Ishikawa e 5W2H) de forma resumida."

- **Prompt:** "Estou mapeando um processo real de [inserir o processo]. Com base nas boas práticas do caderno:
  - Estruture uma tabela SIPOC sugerida para este fluxo
  - Indique se devo adotar uma abordagem preventiva ou corretiva
  - Aponte 2 indicadores (KPIs) essenciais para monitorar esse processo."

- **Prompt:** "Identifiquei o seguinte problema no meu processo operacional: [descrever a falha]. Me ajude a aplicar o Diagrama de Ishikawa (6M) e a técnica dos 5 Porquês para encontrar a causa raiz desse gargalo, e em seguida estruture 2 ações corretivas no formato 5W2H."
