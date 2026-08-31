# 🚀 Algoritmos Fundamentais (Estrutura de Dados)

Bem-vindo ao repositório de **Algoritmos Fundamentais**! Este projeto contém a implementação, documentação e análise dos algoritmos clássicos de ciência da computação e estruturas de dados básicos, codificados em **JavaScript** e **Java** com base nos conceitos apresentados no material de apoio.

---

## 👤 Autor
* **Desenvolvedor:** Vinicius Lisboa de Albuquerque
---

## 📌 Objetivo do Repositório (Caso de Uso)

O objetivo principal deste repositório é servir como um **caso de uso acadêmico e prático** para a construção, testes e conversão de algoritmos fundamentais. A partir de descrições lógicas e pseudocódigos em VisuAlg, este projeto demonstra a implementação prática de 9 algoritmos estruturados.

---

## 📋 Casos de Uso dos Algoritmos

Abaixo estão os fluxos de caso de uso e escopos dos algoritmos cobertos neste repositório:

| ID | Nome do Algoritmo | Descrição / Caso de Uso |
|:--:|:------------------|:------------------------|
| **UC01** | **Troca de Valores** | Permite trocar o valor armazenado entre duas variáveis ($A$ e $B$) com auxílio de uma variável temporária ou por operações lógicas/matemáticas. |
| **UC02** | **Contagem** | Dado um conjunto de $N$ dados (ex: notas de alunos), realiza a leitura contínua e incrementa um contador com base em um critério pré-definido (ex: $\text{nota} \ge 50$). |
| **UC03** | **Soma de Números** | Dado um número $N$ positivo, calcula o somatório de uma sequência de $N$ números inseridos sequencialmente. |
| **UC04** | **Cálculo de Fatorial** | Recebe um valor inteiro $N \ge 0$ e calcula o resultado do seu fatorial ($N!$) acumulando as multiplicações sucessivas. |
| **UC05** | **Função Seno (Série Infinita)** | Aproxima o valor da função trigonométrica Seno de um ângulo $x$ através do cálculo de $N$ termos de sua série infinita de Maclaurin. |
| **UC06** | **Série de Fibonacci** | Gera e exibe os $N$ primeiros números da sequência de Fibonacci ($0, 1, 1, 2, 3, 5, 8, \dots$) recalculando cada termo como a soma dos dois anteriores. |
| **UC07** | **Inversão de Dígitos** | Recebe um inteiro positivo $N$ e inverte a ordem dos seus dígitos matematicamente utilizando divisões sucessivas e cálculo do resto da divisão (`mod 10` e `div 10`). |
| **UC08** | **Decimal para Binário** | Recebe um valor inteiro em base decimal e realiza a conversão para a sua representação em código binário utilizando armazenamento em array. |
| **UC09** | **Caractere para Número** | Lê uma cadeia/string de caracteres numéricos e converte símbolo a símbolo para o seu formato numérico equivalente utilizando deslocamento de dígitos. |

---

## 🛠️ Tecnologias Utilizadas
* **VisuAlg:** Para representação dos pseudocódigos.
* **JavaScript:** Implementações para ambientes web / Node.js[cite: 1].
* **Java:** Implementação orientada a objetos das soluções[cite: 1].

---

## 📁 Estrutura de Pastas

```text
├── src/
│   ├── java/
│   │   ├── TrocaDeVariaveis.java
│   │   ├── Contagem.java
│   │   ├── SomaDeNumeros.java
│   │   ├── Fatorial.java
│   │   ├── SerieInfinita.java
│   │   ├── Fibonacci.java
│   │   ├── InverteDigitos.java
│   │   ├── ConversaoBase.java
│   │   └── CaractereParaNumero.java
│   └── javascript/
│       ├── troca_variaveis.js
│       ├── contagem.js
│       ├── soma_numeros.js
│       ├── fatorial.js
│       ├── seno.js
│       ├── fibonacci.js
│       ├── inverter_digitos.js
│       ├── decimal_binario.js
│       └── caractere_numero.js
└── README.md
