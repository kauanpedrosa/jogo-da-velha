# 📝 Jogo da Velha

Bem-vindo ao **Jogo da Velha** em sua forma mais minimalista trazendo a experiência clássica de forma simples e manual.

---

## 🎮 Como Jogar

1. **Clone o repositório** para sua máquina:
   ```sh
   git clone https://github.com/seu-usuario/jogo-da-velha-txt.git
   cd jogo-da-velha-txt
   ```

2. **Abra** o arquivo `jogo_da_velha.txt` em um editor de texto simples (como o Bloco de Notas, VS Code, ou outro de sua preferência).

3. O arquivo contém um tabuleiro vazio no seguinte formato:
   ```
   1 | 2 | 3
   ---------
   4 | 5 | 6
   ---------
   7 | 8 | 9
   ```

4. **Dois jogadores** devem alternar as jogadas, substituindo os números por `X` ou `O`.
   - Exemplo após algumas jogadas:
   ```
   X | O | 3
   ---------
   4 | X | O
   ---------
   7 | 8 | X
   ```

5. Após cada jogada, salve o arquivo e faça commit das alterações:
   ```sh
   git add jogo_da_velha.txt
   git commit -m "Jogador X marcou a posição 5"
   git push origin main
   ```

6. O outro jogador pode fazer pull para atualizar o arquivo localmente:
   ```sh
   git pull origin main
   ```

7. O jogo termina quando um dos jogadores forma uma linha, coluna ou diagonal com o mesmo símbolo (`X` ou `O`).
8. Para iniciar um novo jogo, basta redefinir o tabuleiro para a versão original e commitar a alteração.

---

## 📌 Regras
- O jogo é para **dois jogadores**.
- Cada jogador deve substituir um dos números pelo seu símbolo (`X` ou `O`).
- O primeiro jogador a completar uma linha, coluna ou diagonal com seu símbolo vence!
- Se todas as casas forem preenchidas sem um vencedor, o jogo termina em **empate**.

---

## 🚀 Dicas
- Para organizar as rodadas, os jogadores podem alternar a edição do arquivo e commitar as alterações.
- Se preferir, use pull requests para cada rodada e acompanhe a história do jogo no GitHub.
- Caso queira desfazer uma jogada, use `git revert` ou volte para um commit anterior.

🎉 **Divirta-se jogando!**

