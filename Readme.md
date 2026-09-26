# Sistema de Controle de Chamados de Suporte Técnico - Planejamento de Projeto

Este repositório reúne o planejamento inicial de um projeto fictício, desenvolvido como atividade acadêmica na disciplina de Gestão de Projetos. O objetivo foi aplicar, de forma prática, os principais artefatos de iniciação e planejamento propostos pelo PMBOK (Termo de Abertura, Stakeholders, EAP e Cronograma), utilizando o **ProjectLibre** para gerar o cronograma e o Gráfico de Gantt.

> **Contexto:** trabalho acadêmico. O cenário (empresa, orçamento, prazos) é fictício, proposto pelo enunciado da atividade, mas o planejamento foi elaborado como se fosse um projeto real.

## Situação-problema

Uma empresa deseja desenvolver um sistema web de controle de chamados de suporte técnico, que permita aos usuários registrar chamados, acompanhar o andamento das solicitações e consultar o histórico de atendimentos.

**Restrições iniciais definidas pela empresa:**
| Item | Detalhe |
|---|---|
| Prazo máximo | 45 dias úteis |
| Orçamento disponível | R$ 25.000,00 |
| Equipe | 2 desenvolvedores, 1 analista de requisitos, 1 responsável por testes |
| Patrocinador | Diretor de Tecnologia |
| Gerente do projeto | Definido pela equipe |

## 1. Termo de Abertura Simplificado (TAP)

| Item | Descrição |
|---|---|
| **Nome do projeto** | Sistema de Controle de Chamados de Suporte Técnico |
| **Justificativa** | Facilitar o gerenciamento dos chamados de suporte, permitindo que os usuários registrem solicitações, acompanhem o andamento dos atendimentos e consultem o histórico. |
| **Objetivo geral** | Desenvolver um sistema web que permita registro, acompanhamento e consulta do histórico de chamados. |
| **Principais entregas** | Sistema funcionando, banco de dados de usuários/chamados/histórico e documentação do sistema. |
| **Premissas** | As informações necessárias para registro e acompanhamento dos chamados estarão disponíveis para o sistema. |
| **Restrições** | Respeitar o orçamento disponível (R$ 25.000,00) e o prazo de entrega (45 dias úteis). |

## 2. Partes interessadas (Stakeholders)

| Stakeholder | Responsabilidade / Interesse |
|---|---|
| **Gerente do projeto** | Entregar as tarefas no prazo; planejar, organizar, controlar e resolver problemas. |
| **Clientes** | Fornecer informações para o desenvolvimento, validar requisitos e aprovar entregas. |
| **Usuários finais** | Interesse em utilizar o produto final. |
| **Equipe de desenvolvimento** | Responsável pelo desenvolvimento do sistema. |
| **Sponsor (Diretor de Tecnologia)** | Apoiar o projeto, disponibilizar recursos e aprovar decisões importantes. |

## 3. EAP (Estrutura Analítica do Projeto)

Estrutura em 3 níveis, organizada por macroentregas do sistema:

```
1. Sistema de Controle de Chamados
├── 1.1 Cadastro de usuários
│   ├── 1.1.1 Tela de cadastro
│   └── 1.1.2 Funcionalidade de cadastro
├── 1.2 Sistema de registro de chamados
│   ├── 1.2.1 Tela de registro
│   └── 1.2.2 Funcionalidade de registro
├── 1.3 Acompanhamento das solicitações
│   ├── 1.3.1 Tela de acompanhamento
│   └── 1.3.2 Funcionalidade de atualização
└── 1.4 Consulta de histórico de atendimentos
    ├── 1.4.1 Tela de consulta do histórico
    └── 1.4.2 Funcionalidade de consulta ao histórico
```



## 4. Cronograma

| Id | Atividade | Duração | Predecessora |
|---|---|---|---|
| 1 | Levantamento de requisitos | 7 dias | — |
| 2 | Aprovar requisitos | 0 dias | 1 FS |
| 3 | Criar banco de dados | 5 dias | 2 FS |
| 4 | Desenvolver telas | 15 dias | 2 FS |
| 5 | Criar documentação | 9 dias | 4 SS |
| 6 | Realizar testes | 7 dias | 3 FS + 4 FS |
| 7 | Corrigir os problemas | 5 dias | 6 FS |
| 8 | **Marco: Sistema aprovado** | 0 dias | 7 FS |
| 9 | Treinar usuários | 5 dias | 8 FS |
| 10 | Implantação do sistema | 4 dias | 9 FS |
| 11 | **Marco: Encerramento do projeto** | 0 dias | 10 FS |

## 5. ProjectLibre

O projeto foi cadastrado no ProjectLibre com:
- Calendário configurado conforme dias úteis da equipe;
- As 11 atividades do cronograma acima, com suas respectivas durações;
- Dependências (FS e SS) configuradas entre as tarefas;
- Gráfico de Gantt gerado a partir do cronograma.



## 6. Análise final

**a) O cronograma está dentro do prazo de 45 dias úteis?**
Sim, o cronograma está dentro do prazo estabelecido.

**b) Quais atividades podem ser executadas em paralelo?**
A criação do banco de dados e o desenvolvimento das telas podem ser executados em paralelo. A criação da documentação também pode ser iniciada em paralelo ao desenvolvimento das telas.

**c) Quais são os principais riscos identificados?**
O principal risco é o término do projeto muito próximo do limite do prazo, o que deixa pouca margem para absorver atrasos ou imprevistos.

**d) O que poderia acontecer se o orçamento fosse reduzido?**
Uma redução no orçamento provavelmente levaria a cortes na equipe de desenvolvimento, o que aumentaria o tempo necessário para a entrega do projeto.

**e) Quais medidas poderiam ser tomadas para evitar atrasos?**
Aumentar o orçamento para viabilizar a contratação de mais integrantes para a equipe de desenvolvimento, reduzindo assim o risco de atrasos.

## Tecnologias e ferramentas utilizadas

- **ProjectLibre** - elaboração do cronograma e Gráfico de Gantt
- Markdown - documentação deste repositório

## Sobre a atividade

Atividade desenvolvida para a disciplina de Gestão de Projetos, com o objetivo de integrar os conhecimentos teóricos de PMBOK (Termo de Abertura, EAP, cronograma, stakeholders) em um planejamento próximo da realidade profissional.
