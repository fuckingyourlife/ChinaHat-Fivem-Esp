# China Hat ESP

Um pequeno módulo ESP que desenha um "China Hat" sobre a cabeça de jogadores no jogo, com suporte à configuração de cor pelo GUI (ImGui/Wexize).

---

## Funcionalidades

- Desenha um chapéu em forma de cone sobre a cabeça dos jogadores.
- Permite alterar a cor do chapéu via GUI.
- Configuração simples para habilitar/desabilitar.
- Compatível com interfaces ImGui e Wexize.

---

## Arquivos Principais

### `Esp.cpp`

- Responsável por desenhar o China Hat sobre a cabeça do jogador.
- Usa `D3DXVECTOR3` para posição do jogador e `ImDrawList` para desenhar.
- Segmentos e proporções do chapéu podem ser ajustados:

```cpp
float hatHeight = CircleValue * 1.2f;  // Altura
float hatRadius = CircleValue * 1.5f;  // Largura
float topOffset = CircleValue * 0.6f;  // Cabeça
```


---

## Preview

https://streamable.com/ntuh9b
