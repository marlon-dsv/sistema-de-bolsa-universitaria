
# Sistema de Avaliação de Bolsa Universitária

## Sobre o Projeto

Projeto desenvolvido em linguagem C++ para a disciplina de **Algoritmos e Programação** da Universidade do Vale do Itajaí (UNIVALI). O sistema tem como objetivo automatizar a análise de elegibilidade de candidatos a bolsas universitárias, considerando critérios socioeconômicos e acadêmicos.

A aplicação utiliza estruturas condicionais, operadores lógicos e aritméticos para processar as informações fornecidas pelo usuário e determinar se o candidato atende aos requisitos para a concessão de uma bolsa integral ou parcial.

## Funcionalidades

- Coleta de dados acadêmicos e socioeconômicos do candidato.
- Cálculo da renda familiar per capita.
- Cálculo da nota final por meio de média ponderada.
- Análise dos critérios para concessão de bolsa integral (100%) ou parcial (50%).
- Verificação de condições relacionadas à renda, ao desempenho acadêmico e aos vínculos sociais.
- Validação dos dados informados.
- Exibição do resultado da análise, incluindo os critérios não atendidos em caso de indeferimento.

## Regras de Avaliação

A nota final é calculada utilizando a seguinte média ponderada:

```text
Nota Final = (PS × 0.4) + (ENEM × 0.3) + (EM × 0.3)
```

Onde:

- **PS:** Nota do processo seletivo interno.
- **ENEM:** Nota do Exame Nacional do Ensino Médio.
- **EM:** Média geral do ensino médio.

### Critérios para Bolsa Integral

- Renda familiar per capita menor ou igual a R$ 800,00.
- Nota final maior ou igual a 8,0.
- Ensino médio cursado em escola pública.
- Nenhum familiar bolsista na universidade.

### Critérios para Bolsa Parcial

- Renda familiar per capita menor ou igual a R$ 1.600,00.
- Nota final maior ou igual a 6,0.
- No máximo um familiar bolsista na universidade.
- Aplicação da condição adicional de nota mínima 7,5 para candidatos que não estudaram na rede pública e não possuem deficiência.

## Conceitos Aplicados

- Lógica de programação.
- Variáveis, constantes e tipos de dados.
- Operadores aritméticos, relacionais e lógicos.
- Estruturas condicionais (`if`, `else if` e `else`).
- Validação de entradas.
- Construção de tabelas-verdade.
- Representação de algoritmos por fluxogramas.

## Tecnologias

- **Linguagem:** C++
- **Execução:** Terminal/console
- **Documentação acadêmica:** PDF com fluxograma e tabelas-verdade.

## Objetivo Acadêmico

Aplicar os fundamentos da lógica proposicional e das estruturas de decisão na construção de um sistema de análise de critérios, desenvolvendo habilidades de modelagem de problemas e implementação de algoritmos.

## Instituição

Universidade do Vale do Itajaí (UNIVALI)  
Disciplina: Algoritmos e Programação 1

