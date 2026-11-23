# Estudos de Python e automações com IA

Este projeto é um ponto de partida para quem está aprendendo a programar. O primeiro exercício usa apenas o Python 3 e funciona sem instalar bibliotecas ou criar contas.

## Estrutura

| Pasta | O que você vai encontrar |
| --- | --- |
| [`aulas/`](aulas/) | Uma primeira aula sobre variáveis, entrada de dados e saída no terminal. |
| [`exercicios/`](exercicios/) | Programas curtos para executar, entender e modificar. |
| [`projetos/`](projetos/) | Ideias para aplicar Python à automação de tarefas e, depois, integrar IA. |

## Comece pelo exercício de saudação

1. Instale o Python 3, caso ainda não tenha. [Download oficial do Python](https://www.python.org/downloads/)
2. Abra um terminal na pasta `estudos-automacoes-ia`, onde está este README.
3. Execute o comando para o seu sistema.

   **Windows (PowerShell)**

   ```powershell
   py -3 exercicios/01_saudacao.py
   ```

   **macOS ou Linux**

   ```bash
   python3 exercicios/01_saudacao.py
   ```

4. Digite seu nome e pressione Enter. Com o nome `Ana`, a saída esperada é `Olá, Ana! Boas-vindas aos estudos de Python.`

O objetivo é ler um valor com `input()`, guardá-lo em uma variável e exibir uma mensagem com `print()`. Depois de rodar o exemplo, altere a saudação e execute novamente. Como desafio, peça também a cidade da pessoa e use as duas respostas na mensagem. [Funções embutidas do Python](https://docs.python.org/pt-br/3/library/functions.html#input) · [Entrada e saída](https://docs.python.org/pt-br/3/tutorial/inputoutput.html)

## Trilha de estudos

1. Pratique variáveis, texto e números. Depois, avance para condições, repetições e funções.
2. Aprenda a ler e gravar arquivos para automatizar uma tarefa que você faz manualmente.
3. Quando estiver confortável trabalhando com arquivos, experimente um projeto de resumo de texto com uma API de IA. [Guia de início rápido da API da OpenAI](https://developers.openai.com/api/docs/quickstart)
