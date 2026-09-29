# Avaliação de risco de escorregamento: casas 1, 2 e 3 (Teresina)

Introdução ao Projeto na Engenharia (0313102), Tarefa 5: Canvas revisado e Plano de Trabalho.

| Participante | NUSP |
| :--- | :--- |
| André Ferrari Silva | 17878387 |
| André Sugai Wrege | 18130440 |
| Fernando do Carmo Moura | 17889730 |
| Lucas Lopes Harada | 18119259 |

Este documento tem duas partes. A primeira é o Canvas da iniciação, corrigido. A segunda é o planejamento (Aula 6): o que vamos fazer, como, quando, quanto custa e quem faz.

---

## Parte 1. Canvas revisado

**Objetivo:** avaliar o risco de escorregamento das encostas das casas 1, 2 e 3 e propor medidas para reduzir esse risco.

### 1. Justificativas

- As três casas estão em encosta e podem desabar. Isso ameaça a vida e a rotina dos moradores.
- A área tem pouca vegetação, o que deixa o solo mais exposto à chuva.
- A população de baixa renda não tem acesso a apoio técnico de engenharia.
- A política habitacional e o controle do uso do solo não impediram a ocupação dessas encostas.

### 2. Produto

Um relatório técnico com:

- o fator de segurança (FS) de cada encosta;
- a classificação de risco de cada casa (R1 a R4);
- um plano de ação com as intervenções recomendadas, custo estimado e prioridade.

### 3. Requisitos

As intervenções recomendadas precisam:

- caber no orçamento da Prefeitura;
- ser simples de executar com mão de obra local;
- durar, com pouca manutenção;
- ter baixo impacto visual e ambiental;
- não piorar a drenagem do córrego nem bloquear a passagem dos moradores.

### 4. Stakeholders e fatores externos

**Stakeholders:** Prefeitura (cliente), Defesa Civil municipal, moradores das três casas, CREA e Prof. Pedro (valida o trabalho).

**Fatores externos:** chuva durante o trabalho de campo, tipo de solo encontrado e disposição dos moradores em liberar o acesso aos terrenos.

### 5. Premissas

- A Prefeitura entrega os dados que já tem: clima, topografia, tipo de solo e cadastro das casas.
- Os moradores liberam o acesso para vistoria, sondagem e instalação de instrumentos.
- Não haverá chuva extrema que mude a geometria das encostas antes das medições.
- Um laboratório de solos consegue entregar os ensaios em até 4 semanas.

### 6. Riscos

Estão detalhados, com resposta planejada, na seção 2.7. Os principais:

- escorregamento ou desabamento durante o projeto, antes das medidas;
- ensaios com resultado inconsistente, exigindo nova coleta de solo;
- acesso negado por algum morador;
- atraso do laboratório.

### 7. Meta

Em até 3 meses, entregar à Prefeitura:

- as casas 1, 2 e 3 classificadas na escala R1 a R4;
- o FS de cada encosta na condição atual e na condição saturada;
- para cada casa em R3 ou R4, uma solução que leve o FS a pelo menos 1,5 (NBR 11682, nível de segurança alto para vidas humanas).

### 8. Benefícios

- Menos chance de morte e de perda das casas.
- A Prefeitura e a Defesa Civil passam a saber quais casas exigem ação imediata.
- O método pode ser repetido em outras encostas da cidade.

### 9. Equipe

| Papel | Quem |
| :--- | :--- |
| Gerente do projeto e relatório | Lucas Harada |
| Investigação geotécnica e ensaios | André Ferrari |
| Análise de estabilidade | André Sugai |
| Campo, topografia e drenagem | Fernando Moura |
| Apoio externo (contratado) | Laboratório de solos, equipe de sondagem, topógrafo com estação total |

A divisão acima é uma sugestão. A equipe pode trocar os nomes, mas cada frente precisa de um dono.

### 10. Restrições

- Prazo: 3 meses (13 semanas).
- Orçamento: valor fechado pela Prefeitura.
- Escopo: seguir as exigências da Prefeitura e as normas NBR 11682 (estabilidade de encostas) e NBR 6484 (sondagem SPT).

### 11. Pacotes de entrega e linha do tempo

| Pacote | Entrega | Quando |
| :--- | :--- | :--- |
| P1. Levantamento | Dados organizados, vistoria e topografia | Semanas 1 a 3 |
| P2. Investigação geotécnica | Perfil de solo e parâmetros (c, φ, γ, sucção) | Semanas 3 a 7 |
| P3. Análise de estabilidade | FS de cada encosta | Semanas 7 a 9 |
| P4. Classificação de risco | Casas classificadas em R1 a R4 | Semana 9 |
| P5. Soluções e plano de ação | Intervenções com FS verificado e custo | Semanas 10 a 11 |
| P6. Relatório e apresentação | Relatório final e apresentação à Prefeitura | Semanas 12 a 13 |

O Canvas anterior colocava a classificação de risco antes dos ensaios. Isso não funciona: a classificação depende do FS, e o FS depende dos parâmetros do solo. A ordem foi corrigida.

### 12. Custos

Ver seção 2.6. Os percentuais agora somam 100%.

### 13. Obstáculos atuais

A equipe deve confirmar e completar esta lista:

- Ainda não sabemos quais dados a Prefeitura já tem e em que formato.
- Ainda não há contato com os moradores nem com a Defesa Civil.
- O valor do orçamento não foi informado, então os custos estão só em percentual.

---

## Parte 2. Plano de Trabalho

### 2.1 Como vamos avaliar a estabilidade

O método segue o que foi visto na Aula 6.

**Solo arenoso (coesão nula).** Para encosta longa e pouco inclinada, usamos o talude infinito:

$$FS = \frac{\tan\phi}{\tan\beta}$$

onde φ é o ângulo de atrito do solo e β é a inclinação da encosta. Exemplo: com φ = 30° e β = 25°, FS = 0,577 / 0,466 ≈ 1,24. Esse valor fica abaixo de 1,5 e exigiria intervenção.

**Solo argiloso.** A coesão permite inclinações maiores. Usamos o método das fatias (Bishop) com superfície de ruptura circular e conferimos a altura crítica da encosta.

**Solo não saturado.** A água nos poros cria sucção, e a sucção aumenta a resistência do solo. Quando chove, a sucção cai e o FS cai junto. Por isso calculamos o FS em duas condições:

1. atual, com a sucção medida em campo;
2. crítica, com o solo saturado (sucção zero).

As soluções são dimensionadas para a condição crítica. Isso pesa mais se o campo for feito no período seco de Teresina (junho a novembro), quando a sucção está alta e o solo parece mais estável do que é na época de chuva.

**Instrumentação.** Em cada encosta instalamos tensiômetros em duas ou três profundidades e um pluviômetro. Se a sondagem encontrar nível d'água, instalamos também um piezômetro. A referência é o talude instrumentado de Leong et al. (1998), apresentado em aula. As leituras mostram quanto a sucção cai a cada chuva.

**Classificação de risco.** Usamos a escala R1 (baixo), R2 (médio), R3 (alto) e R4 (muito alto), combinando o FS com o que for visto na vistoria: trincas, muros inclinados, degraus de abatimento, árvores tortas, água escorrendo pela encosta.

**Intervenções candidatas.** Partimos das opções mais baratas e discretas, em linha com os requisitos:

- levar a água do telhado para fora da encosta, com calha e tubo até a drenagem;
- manter a vegetação existente e replantar onde o solo está exposto;
- canaleta na crista da encosta para desviar a enxurrada;
- estrutura leve apoiada em fundação profunda, que descarregue abaixo da superfície de ruptura;
- retaludamento ou contenção, só quando as opções acima não chegarem a FS 1,5.

### 2.2 EAP (estrutura analítica do projeto)

```
Avaliação de risco das casas 1, 2 e 3
├── 1. Gerenciamento
├── 2. Levantamento
│   ├── 2.1 Dados fornecidos pela Prefeitura
│   ├── 2.2 Vistoria das casas e da encosta
│   └── 2.3 Levantamento topográfico
├── 3. Investigação geotécnica
│   ├── 3.1 Sondagens
│   ├── 3.2 Ensaios de laboratório
│   └── 3.3 Instrumentação (tensiômetros, pluviômetro)
├── 4. Análise de estabilidade
│   ├── 4.1 Modelo geotécnico de cada encosta
│   └── 4.2 Cálculo do FS (condição atual e saturada)
├── 5. Classificação de risco
├── 6. Soluções e plano de ação
│   ├── 6.1 Escolha das intervenções
│   ├── 6.2 Verificação do FS após intervenção
│   └── 6.3 Estimativa de custo e prioridade
└── 7. Relatório e apresentação
```

### 2.3 Atividades por fase

| Fase | Atividade | Entrega |
| :--- | :--- | :--- |
| 1 | Reunião de abertura com a Prefeitura | Ata com escopo e dados disponíveis |
| 1 | Reunião semanal da equipe e relatório de andamento | Status semanal |
| 2.1 | Reunir e revisar dados de clima, solo, topografia e cadastro | Base de dados organizada |
| 2.2 | Vistoriar as três casas e fotografar sinais de instabilidade | Ficha de vistoria por casa |
| 2.3 | Levantar a topografia com estação total | Planta e seções transversais |
| 3.1 | Fazer sondagem SPT ou a trado em cada encosta | Boletins de sondagem |
| 3.2 | Coletar amostras e enviar ao laboratório (caracterização, cisalhamento direto, curva de retenção) | Parâmetros c, φ, γ e sucção |
| 3.3 | Instalar tensiômetros e pluviômetro, ler toda semana | Série de leituras |
| 4.1 | Montar o perfil de solo de cada encosta | Seção geotécnica |
| 4.2 | Calcular o FS nas duas condições | Planilha e memória de cálculo |
| 5 | Classificar cada casa em R1 a R4 | Mapa de risco |
| 6.1 | Selecionar as intervenções para casas em R3 e R4 | Lista de soluções |
| 6.2 | Recalcular o FS com as intervenções | FS ≥ 1,5 comprovado |
| 6.3 | Orçar as soluções e definir prioridade | Plano de ação |
| 7 | Redigir relatório, revisar e apresentar | Relatório final e apresentação |

### 2.4 Matriz RACI

R = executa, A = aprova, C = é consultado, I = é informado.

| Atividade | Lucas | André F. | André S. | Fernando | Prefeitura | Prof. Pedro |
| :--- | :-: | :-: | :-: | :-: | :-: | :-: |
| Reunião de abertura | R/A | C | C | C | C | I |
| Revisão dos dados | A | C | C | R | C | I |
| Vistoria | A | C | C | R | I | I |
| Topografia | A | I | C | R | I | I |
| Sondagens | A | R | C | C | I | I |
| Ensaios de laboratório | A | R | C | I | I | I |
| Instrumentação | A | R | C | C | I | I |
| Cálculo do FS | A | C | R | I | I | C |
| Classificação de risco | A | C | R | C | I | C |
| Escolha das intervenções | A | C | R | R | C | C |
| Orçamento das soluções | R/A | C | C | R | C | I |
| Relatório final | R | C | C | C | A | C |
| Apresentação | R | R | R | R | A | I |

### 2.5 Cronograma (13 semanas)

| Fase | S1 | S2 | S3 | S4 | S5 | S6 | S7 | S8 | S9 | S10 | S11 | S12 | S13 |
| :--- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| 1. Gerenciamento | ■ | ■ | ■ | ■ | ■ | ■ | ■ | ■ | ■ | ■ | ■ | ■ | ■ |
| 2. Levantamento | ■ | ■ | ■ | | | | | | | | | | |
| 3. Investigação geotécnica | | | ■ | ■ | ■ | ■ | ■ | | | | | | |
| 4. Análise de estabilidade | | | | | | | ■ | ■ | ■ | | | | |
| 5. Classificação de risco | | | | | | | | | ■ | | | | |
| 6. Soluções e plano de ação | | | | | | | | | | ■ | ■ | | |
| 7. Relatório e apresentação | | | | | | | | | | | ■ | ■ | ■ |

**Marcos:**

| Marco | Semana | Critério de conclusão |
| :--- | :-: | :--- |
| M1 | 3 | Vistoria e topografia das três casas prontas |
| M2 | 7 | Parâmetros de solo de todas as encostas recebidos |
| M3 | 9 | FS calculado e casas classificadas |
| M4 | 12 | Relatório entregue à Prefeitura |
| M5 | 13 | Apresentação feita |

Se uma casa for classificada como R4 antes do M3 (por exemplo, pela vistoria), a equipe avisa a Defesa Civil na hora. Não espera o relatório.

### 2.6 Orçamento por fase

| Fase | % do orçamento | O que pesa no custo |
| :--- | :-: | :--- |
| 1. Gerenciamento | 5% | Horas de coordenação, deslocamento |
| 2. Levantamento | 10% | Topógrafo e estação total |
| 3. Investigação geotécnica | 45% | Sondagem, ensaios, tensiômetros |
| 4. Análise de estabilidade | 15% | Horas de engenharia, software |
| 5. Classificação de risco | 5% | Horas de engenharia |
| 6. Soluções e plano de ação | 15% | Horas de engenharia, cotações |
| 7. Relatório e apresentação | 5% | Horas de redação e revisão |
| **Total** | **100%** | |

A investigação geotécnica é o maior custo porque depende de serviços contratados. Quando a Prefeitura informar o valor total, convertemos os percentuais em reais.

### 2.7 Plano de riscos

| Risco | Chance | Impacto | Resposta |
| :--- | :-: | :-: | :--- |
| Escorregamento durante o projeto | Baixa | Muito alto | Avisar a Defesa Civil assim que a vistoria indicar R4 |
| Morador nega acesso | Média | Alto | Contato prévio pela Prefeitura e explicação do trabalho aos moradores |
| Chuva forte atrasa o campo | Média | Médio | Duas semanas de folga entre S3 e S7; campo remarcado para o primeiro dia seco |
| Laboratório atrasa | Média | Alto | Contratar na semana 1 e pedir prazo por escrito |
| Ensaios inconsistentes | Baixa | Alto | Coletar amostra extra na primeira ida a campo |
| Dados da Prefeitura incompletos | Alta | Médio | Topografia própria já está no plano |
| Custo das soluções acima do orçamento | Média | Alto | Priorizar casas R4 e soluções de drenagem, que são mais baratas |

### 2.8 Controle e monitoramento

- Reunião da equipe toda semana: o que foi feito, o que atrasou, o que muda.
- Relatório curto de andamento para a Prefeitura a cada duas semanas.
- A cada marco, conferir prazo e gasto contra este plano e replanejar se preciso.
- As leituras dos tensiômetros entram na planilha de cálculo do FS assim que chegam.

---

## Referências

- ABNT NBR 11682: Estabilidade de encostas.
- ABNT NBR 6484: Solo, sondagem de simples reconhecimento com SPT.
- Leong, E. C. et al. (1998). Instrumentação de talude em solo residual, Singapura.
- Pinto, C. S. *Curso Básico de Mecânica dos Solos em 16 Aulas*. 3ª ed. São Paulo: Oficina de Textos, 2006.
- Buelta, M.; Wellington, P. Aula 6: Planejamento do projeto proposto. Introdução ao Projeto na Engenharia, EPUSP, 2026.
