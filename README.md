# Galeria CC — Peixe (SVG + D3)

## Contexto

Artefato da disciplina **CC05 — Visualização de Grafos** (módulo de UX / visualização), **Aula 01**: aplicações de visualização, introdução ao **SVG** e à biblioteca **D3.js** (data binding, seleções, elementos gerados a partir de dados).

Este projeto responde à **Parte II — Desenho com código** da aula: composição em **HTML com SVG + D3** e **interação** (hover no peixe, além da animação contínua).

## Material e versões

| Item        | Detalhe                          |
|------------|-----------------------------------|
| Arquivo    | `peixinho.html`                   |
| Biblioteca | **D3.js v7** (`d3.v7.min.js`)     |
| Linguagem  | HTML5, CSS embutido, JavaScript   |

## O que o sketch faz

- **Cenário**: fundo em gradiente e bolhas geradas com `d3.range`, `data` / `enter` / `append("circle")`, animadas subindo.
- **Personagem**: peixe construído com primitivas SVG (`ellipse`, `polygon`, `path`, `line`) via D3.
- **Movimento**: trajetória com `requestAnimationFrame` (translação + rotação leve).
- **Interação**: ao passar o mouse sobre o peixe, ele **aumenta levemente de escala** e as cores **transicionam** do laranja para um tom turquesa (interpolação com `d3.interpolate`); cursor vira ponteiro na área do peixe.

## Como visualizar

Abra `peixinho.html` no navegador (duplo clique ou “Open with Live Server”, se usar). Não é necessário servidor para o D3 carregar do CDN.

## Observação sobre entrega

O envio oficial costuma ser pelo **formulário indicado no Slack** da turma; este repositório/arquivo serve como artefato nomeado e documentado para essa entrega.
