# Implementação do Jogo da Velha em Prolog

Este projeto é inspirado e baseado na implementação do Jogo da Velha originalmente criada por Steven L. Tanimoto na Universidade de Washington.



## Características Principais do Design Original de Tanimoto

A implementação original incluía vários conceitos-chave que estão presente neste projeto:

- Verificação de condições de vitória através de:
  - Vitórias por linha
  - Vitórias por coluna
  - Vitórias por diagonal
- IA com:
  - Previsão de jogadas vencedoras
  - Bloqueio de jogadas vencedoras do oponente
- Jogabilidade interativa com entrada do usuário

## Recursos Estendidos Nesta Implementação

Nossa implementação NxN estende o design original 3x3 de Tanimoto através de:
- Suporte a tabuleiros de tamanho variável
- Reconhecimento de padrões

## Como Jogar

1. Carregue o jogo no seu interpretador Prolog

```
#Use o comando play com o numero de linhas e colunas para iniciar o tabuleiro
play(3).
```

2. Siga as instruções na tela para fazer as jogadas

## Referências

> Implementação original: [Jogo da Velha de Tanimoto](https://courses.cs.washington.edu/courses/cse341/03sp/slides/PrologEx/tictactoe.pl.txt)

## Licença

Este projeto é baseado no material educacional do Professor Tanimoto, adicionando funcionalidade NxN e recursos adicionais. Por favor, consulte o arquivo LICENSE para mais detalhes.
