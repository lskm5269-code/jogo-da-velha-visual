# Jogo da Velha - [Versão Console / Versão Visual]

Este projeto foi desenvolvido durante as aulas de Programação em Python para praticar lógica, estruturas de controle e boas práticas de desenvolvimento.

## Funcionalidades principais
- Esse projeto é um jogo da velha, criado usando a linguagem pyton e o tkinter (GUI-visual) para prática lógica, interface gráfica, estruturas de controle e boas práticas de desenvolvimento. Ele foi desenvolvido no curso técnico em desenvolvimento de sistemas do SENAC DF com o Prof Alexandre

Jogo da Velha – Versão Visual (Tkinter)
Descrição Geral

O Jogo da Velha – Versão Visual é uma versão aprimorada do clássico Tic-Tac-Toe, desenvolvida em Python com a biblioteca Tkinter.
Esta edição apresenta uma interface gráfica moderna, placar dinâmico, controle de jogadores e recursos visuais interativos, mantendo toda a lógica do jogo tradicional.

 Funcionalidades Principais

 Tabuleiro 3x3 Interativo
 
Nove botões dispostos em uma grade 3x3, representando as casas do jogo.

Cada botão exibe o símbolo do jogador atual (X ou O) ao ser clicado.

As jogadas alternam automaticamente entre os jogadores.

Casas já ocupadas não podem ser jogadas novamente.

 Placar de Pontuação

Exibe os pontos acumulados de cada jogador (X e O).

O placar é atualizado automaticamente a cada vitória.

Os valores permanecem mesmo ao reiniciar o tabuleiro.

 Verificação de Vitória e Empate

O programa detecta automaticamente quando há três símbolos iguais em linha, coluna ou diagonal.

Exibe uma mensagem informando o vencedor.

Caso todas as casas sejam preenchidas sem vencedor, o jogo declara empate.

 Botão "Reiniciar Partida"

Limpa o tabuleiro e inicia uma nova rodada sem zerar o placar.

Mantém o jogador alternando corretamente.

 Botão "Zerar Placar"

Redefine os pontos dos jogadores para zero.

Ideal para iniciar um novo campeonato entre os mesmos jogadores.

Botão "Créditos"

Exibe uma janela (messagebox.showinfo) com os créditos do projeto, incluindo nome do autor e turma.

Botão "Mudar Tema"

Alterna dinamicamente entre dois estilos visuais:

Tema Claro: fundo cinza claro, botões brancos e texto preto.

Tema Escuro: fundo escuro, botões cinza e texto branco.

A troca é instantânea, sem reiniciar o jogo.

 Layout e Estilo Visual

Gerenciador de layout: grid()

Distribuição:

Linha 0: Placar dos jogadores

Linha 1–3: Tabuleiro (3x3 botões)

Linha 4: Botões de controle (Reiniciar, Zerar Placar, Créditos, Mudar Tema)

Paleta de cores: tons suaves de cinza, azul e branco, garantindo um visual limpo e agradável.

Fonte padrão: ("Helvetica", 32) para o tabuleiro e ("Helvetica", 14) para o placar e botões.

Lógica Interna

Controle do jogador atual via variável jogador_atual.

Prevenção de jogadas duplicadas com if button["text"] == "":.

Verificação automática de vitória após cada jogada.

Detecção de empate quando todas as casas são preenchidas sem vencedor.

Atualização automática do placar.

Funções separadas para:

Jogar

Checar vitória/empate

Reiniciar tabuleiro

Zerar placar

Mudar tema

Mostrar créditos

## Como executar
Para rodar o projeto, execute o arquivo principal dentro da pasta `src`:

```bash
python src/main.py
