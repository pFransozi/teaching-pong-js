# 🎮 Pong em JS para ensino

Projeto didático que recria o clássico Pong em JavaScript com p5.js. Use este repositório para guiar aulas práticas, mostrando de forma incremental como construir um jogo simples, tocar sons e trabalhar lógica básica de colisão.

## 🎯 Objetivos do projeto
- Apresentar o ciclo básico de um jogo (setup → draw → atualizar estado → renderizar).
- Praticar lógica de movimento, colisão e pontuação em 2D.
- Explorar uso de bibliotecas (p5.js e p5.sound) e organização de código em funções.
- Exercitar depuração e ajustes finos (velocidades, bordas, dificuldade do oponente).

## 🧠 Competências a desenvolver
- JavaScript no navegador: variáveis, funções, condicionais, loop de renderização.
- Manipulação de canvas com p5.js: desenho de formas, atualização quadro a quadro.
- Detecção de colisão retângulo × círculo usando biblioteca auxiliar.
- Leitura de código legado e adição de novas funcionalidades (sons, placar, IA simples).
- Boas práticas iniciais: separar responsabilidades e usar nomes claros.

## 🚀 Como rodar rapidamente
1) Baixe/clonar o repo.  
2) Abra `index.html` em um navegador moderno (Live Server do VS Code facilita).  
3) Confirme que há áudio: `trilha.mp3`, `raquetada.mp3` e `ponto.mp3` na mesma pasta.  
4) Use as setas ↑ ↓ para mover sua raquete; a outra é controlada por uma IA simples.

## 📚 Passo a passo (aulas sugeridas)
- Aula 1 — Primeiros pixels: configurar `createCanvas`, desenhar a bolinha estática.
- Aula 2 — Movimento básico: atualizar posição da bolinha a cada `draw`.
- Aula 3 — Colisão com bordas: inverter velocidades ao tocar limites do canvas.
- Aula 4 — Raquetes: desenhar retângulos, criar controles de teclado para o jogador.
- Aula 5 — Colisão bola×raquete: usar `collideRectCircle` para detectar contato e refletir a bola.
- Aula 6 — Oponente: mover a raquete adversária seguindo a bola; introduzir chance de erro.
- Aula 7 — Placar e feedback: mostrar pontos, tocar sons de trilha, raquetada e pontuação.
- Aula 8 — Balanceamento: ajustar velocidades, tamanhos e dificuldade adaptativa.
- Aula 9 — Polimento final: revisar variáveis, comentar partes críticas e limpar código.

## ✅ Conclusão e próximos passos
- Refletir: quais conceitos de física simples e de lógica foram aplicados?
- Ideias de melhoria: 
  - 🛠️ adicionar modos de jogo (2 jogadores locais, melhor de 3/5). 
  - 🎵 trocar trilha ou inserir efeitos visuais ao marcar ponto. 
  - 📱 adaptar layout/controles para mobile (toques ou tilt). 
  - 🧠 IA ajustável por nível e power-ups temporários. 
  - 🧪 criar testes manuais automatizados de colisão/pontuação (prints do placar esperado).