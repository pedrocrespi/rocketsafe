# 🚀 Rocket Safe (Scratch)

Endless runner feito no Scratch 3 (programação por blocos) e empacotado com TurboWarp.

**▶️ Jogar agora:** https://pedrocrespi.github.io/rocketsafe/

---

## 🎮 Como jogar
- **Seta ↑ / ↓**: mover a nave
- **SPACE**: iniciar / reiniciar
- Desvie dos asteroides. A pontuação (**Score**) sobe com o tempo; a velocidade (**Speed**) aumenta gradualmente.

---

## ✨ Features
- Sistema de **game state**: `menu`, `playing`, `gameover`
- **Spawn** de asteroides com clones e dificuldade dinâmica (`spawnWait = 0.8 - Score/300`, mínimo 0.25s)
- **Colisão** com `gameover` e tela de UI
- **Score** e **Speed** com rampa de dificuldade
- Sons: **click** (start), **hit** (colisão), **BGM** (loop)

---

## 🛠️ Stack
- **Scratch 3** (editor online)
- **TurboWarp Packager** → formato **HTML (one file)**
- **GitHub Pages** para hospedagem

---

## 📦 Como atualizar o jogo
1. No Scratch, **File → Save to your computer** para exportar o `.sb3`.
2. No **TurboWarp Packager**:
   - **Project → Upload file** (seu `.sb3`)
   - **Format → HTML (One file)**
   - **Package** → salva como `index.html`
3. No GitHub:
   - **Upload** o novo `index.html` (substitui o antigo)
   - (Opcional) Envie o `.sb3` em `/src`

---

## 📁 Estrutura sugerida
