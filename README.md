# Laboratório AWS Step Functions

## Descrição

Este repositório contém as anotações, conceitos aprendidos e experiências adquiridas durante o laboratório de AWS Step Functions realizado na plataforma DIO.

---

## Objetivos

- Entender o funcionamento do AWS Step Functions.
- Criar workflows utilizando máquinas de estado.
- Automatizar processos na AWS.
- Integrar diferentes serviços da AWS.

---

## O que é AWS Step Functions?

AWS Step Functions é um serviço de orquestração da AWS que permite criar fluxos de trabalho (workflows) utilizando máquinas de estado (State Machines).

Com ele é possível coordenar serviços como:

- AWS Lambda
- Amazon SNS
- Amazon SQS
- DynamoDB
- ECS
- Batch
- entre outros.

---

## Conceitos Aprendidos

### State Machine

É o fluxo principal da aplicação.

Ela contém todos os estados que serão executados.

---

### States

Cada etapa do fluxo representa um estado.

Exemplos:

- Task
- Choice
- Wait
- Parallel
- Pass
- Fail
- Succeed

---

### Task

Executa uma ação.

Normalmente chama uma função Lambda ou outro serviço da AWS.

---

### Choice

Permite criar decisões no fluxo.

Exemplo:

Se o pedido foi aprovado → continua.

Caso contrário → encerra.

---

### Wait

Adiciona um tempo de espera antes da próxima etapa.

---

### Parallel

Executa várias tarefas ao mesmo tempo.

---

### Fail

Finaliza o fluxo informando erro.

---

### Success

Finaliza o fluxo com sucesso.

---

## Benefícios

- Automatização de processos
- Redução de código
- Escalabilidade
- Monitoramento das execuções
- Integração entre serviços AWS

---

## O que aprendi

Durante este laboratório aprendi como construir workflows utilizando AWS Step Functions, entendendo como criar máquinas de estado, definir transições entre estados e integrar diferentes serviços da AWS.

Também compreendi como monitorar execuções e identificar possíveis falhas no fluxo.

---

## Conclusão

AWS Step Functions facilita bastante a criação de processos automatizados e torna aplicações distribuídas mais organizadas, escaláveis e de fácil manutenção.

---

## Referências

https://docs.aws.amazon.com/step-functions/

https://aws.amazon.com/step-functions/
