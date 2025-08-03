# Jogo de Xadrez com Java
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/pedrosntx/chess-game-java/blob/main/LICENSE) 

# Sobre o projeto

Este jogo foi desenvolvido como parte da prática aplicada durante um curso de desenvolvimento back-end com Java. O objetivo foi consolidar conhecimentos em Programação Orientada a Objetos, além de adquirir experiência com a aplicação de conceitos e técnicas fundamentais da linguagem Java.

A aplicação consiste em um sistema que simula um jogo de xadrez completo, com todas as regras e funcionalidades essenciais. Ao executar o jogo, o sistema permite a visualização do tabuleiro, peças diferenciadas pela cor e identificadas por uma letra, contagem de rodadas, a cor do usuário que deve efetuar a jogada e as jogadas possíveis.

## Funcionalidades
- Representação completa do tabuleiro e das peças (identificação no tabuleiro): Rei (K), Rainha (Q), Torre (R), Bispo (B), Cavalo (N) e Peão (P)
- Suporte às cores das peças: brancas e pretas
- Lógicas de movimentação, check e checkmate
- Lógicas de jogadas especiais: En Passant, Roque e Promoção de peão
- Adaptações para melhor contraste na impressão do tabuleiro: Peças brancas continuam brancas, pretas são amarelas e as possíveis jogadas de cada rodada são destacadas em vermelho

## Modelo conceitual
![Modelo Conceitual](https://github.com/pedrosntx/assets/blob/main/chess-game-java/modelo-conceitual-jogo-xadrez.png)

# Tecnologias utilizadas
## Back-end
- Java

## Objetivos de aprendizado
- Aperfeiçoar conceitos de POO como: estruturação de classes e objetos, encapsulamento e herança e lógica condicional e manipulação de fluxo

# Como executar o projeto via IDE

Pré-requisitos: Ter uma IDE com terminal que suporte saída colorida instalada (Ex: IntelliJ)

```bash
# clonar repositório
# git clone git@github.com:pedrosntx/chess-game-java.git

# execute a aplicação localizada em:
# \src\application\Program.java

# se a IDE for compatível com as cores o programa já deve funcionar normalmente
```

# Como executar o projeto via terminal (Git Bash)

Pré-requisitos: Ter o JDK instalado na máquina

```bash
# clonar repositório
# git clone git@github.com:pedrosntx/chess-game-java.git

# execute a aplicação no caminho:
# \src\application\Program.java

# abra o terminal na pasta \bin\ ou onde os arquivos ".class" compilados ficam salvos

# execute com o comando:
# java application/Program

# o jogo deverá funcionar normalmente e você poderá efetuar os movimentos digitando as posições
```

# Autor

Pedro Henrique Gomes dos Santos

https://www.linkedin.com/in/pedrosantos091/

