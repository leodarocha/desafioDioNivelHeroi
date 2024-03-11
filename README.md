# Classificador de Nível de Herói em JS

Este projeto implementa um simples classificador de nível de herói utilizando a linguagem de programação JavaScript.

## 🚀 Como foi feito

O programa foi construído usando os fundamentos básicos de programação em JavaScript:

- **Variáveis**: para armazenar dados, como o nome do herói e sua experiência (XP).
- **Operadores**: para comparar a experiência do herói e determinar seu nível.
- **Estruturas de decisões**: para atribuir o nível de herói correspondente à sua experiência.

Não foram utilizados laços de repetição, pois a lógica do programa não requeria iteração.

## 🎯 Objetivo

O script determina o nível de um herói baseado em sua quantidade de experiência (XP) de acordo com os seguintes critérios:

- Ferro: XP < 1.000
- Bronze: 1.001 ≤ XP ≤ 2.000
- Prata: 2.001 ≤ XP ≤ 5.000
- Ouro: 5.001 ≤ XP ≤ 7.000
- Platina: 7.001 ≤ XP ≤ 8.000
- Ascendente: 8.001 ≤ XP ≤ 9.000
- Imortal: 9.001 ≤ XP ≤ 10.000
- Radiante: XP ≥ 10.001

## ▶️ Como usar

1. Abra o arquivo `nivelHerois.js` com um editor de texto.
2. Modifique as variáveis `nomeDoHeroi` e `experiencia` no início do script para refletir o nome do seu herói e sua experiência em XP.
3. Execute o arquivo em um ambiente JavaScript como o Node.js ou no console do navegador.

```javascript
node nivelHerois.js
