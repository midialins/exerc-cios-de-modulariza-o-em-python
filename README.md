# Exercícios de Modularização em Python

Repositório desenvolvido para a disciplina de **Sistemas Operacionais**, contendo exercícios de Python com foco em **modularização, procedimentos, variáveis globais, variáveis locais e passagem de parâmetros**.

## Objetivo

A atividade consiste em refazer exercícios já desenvolvidos anteriormente, aplicando modularização em Python.

Os exercícios foram organizados em dois grupos:

- **Exercícios 18 a 26:** procedimentos sem retorno, sem passagem de parâmetros e utilizando variáveis globais.
- **Exercícios 27 a 29:** procedimentos com passagem de parâmetros e utilização de variáveis locais.

Os programas também utilizam a função `main()` para organizar a execução principal.

## Arquivos

```text
Ex18.py
Ex19.py
Ex20.py
Ex21.py
Ex22.py
Ex23.py
Ex24.py
Ex25.py
Ex26.py
Ex27.py
Ex28.py
Ex29.py
```

## Conceitos praticados

- Modularização
- Procedimentos
- Função `main()`
- Variáveis globais
- Variáveis locais
- Passagem de parâmetros
- Estruturas condicionais
- Operadores aritméticos e relacionais
- Execução de aplicações Python em Docker
- Mapeamento de volume entre o hospedeiro e o contêiner

## Python

Versão utilizada na atividade:

```text
Python 3.10.20
```

## Docker

Além da execução local, os exercícios foram executados em um contêiner Docker utilizando a imagem:

```bash
python:3.10.20
```

Exemplo de criação do contêiner com mapeamento da pasta dos exercícios:

```bash
sudo docker run -it --name modularizacao2 -v "$(pwd)":/app python:3.10.20 bash
```

Dentro do contêiner:

```bash
cd /app
ls
python --version
```

Para executar um exercício:

```bash
python Ex18.py
```

ou:

```bash
python Ex27.py
```


