# 🟢🔴🟡🔵 Jogo Estilo Genius (Gênesis)

## 📖 Sobre o Projeto

O **Jogo Estilo Genius (Gênesis)** é um jogo de memória e sequência de cores para navegador, desenvolvido como parte de um desafio prático da **[Digital Innovation One (DIO)](https://dio.me)**.

O objetivo principal da aplicação é colocar em prática conceitos fundamentais de desenvolvimento web front-end utilizando **HTML5**, **CSS3** (com CSS Grid) e **JavaScript puro (Vanilla JS)** para manipular eventos de clique, gerenciar temporizadores (`setTimeout`), comparar arrays de sequências e criar feedback visual dinâmico no navegador.

---

## ✨ Funcionalidades

- **Geração Aleatória de Sequências:** A cada nova rodada, o jogo sorteia uma nova cor e a adiciona ao final da sequência atual.
- **Feedback Visual de Acendimento:** As quatro áreas coloridas (Verde, Vermelho, Amarelo e Azul) acendem em ordem com intervalos temporizados para que o jogador memorize.
- **Validação em Tempo Real:** Verifica cada clique do jogador comparando com a ordem correta gerada pelo sistema.
- **Sistema de Pontuação:** Incrementa automaticamente a pontuação a cada nível concluído com sucesso.
- **Game Over e Reinício Automático:** Caso o jogador clique em uma cor errada, exibe um alerta com a pontuação final e reinicia uma nova partida.

---

## 🎮 Como Jogar

1. Ao abrir o jogo, um alerta de boas-vindas iniciará automaticamente o **Nível 1**.
2. Observe atentamente a ordem em que as cores (**Verde**, **Vermelho**, **Amarelo** ou **Azul**) piscam na tela.
3. Após a sequência terminar de piscar, clique nas cores exatamente na **mesma ordem** em que apareceram.
4. Se acertar toda a sequência, você avança para o próximo nível com uma cor adicional.
5. Se errar qualquer cor da sequência, o jogo exibe **Game Over** com sua pontuação e recomeça do zero.

---

## 🛠️ Tecnologias Utilizadas

Com base nos arquivos do repositório, o projeto foi desenvolvido utilizando apenas tecnologias nativas da web, sem bibliotecas ou frameworks externos:

- **HTML5 (`index.html`):** Estruturação do tabuleiro circular dividido nos quatro quadrantes coloridos.
- **CSS3 (`style.css`):** Uso de `display: grid` para formar o círculo dividido em 4 setores, definição das cores, bordas arredondadas e efeitos de opacidade/brilho ao selecionar uma cor.
- **JavaScript (`script.js`):** Lógica de sorteio aleatório (`Math.random`), controle assíncrono de acendimento com `setTimeout`, captura de cliques e comparação de arrays de sequência.

---

## 📂 Estrutura de Arquivos

```text
Jogo_Estilo_Genesis/
├── index.html        # Estrutura HTML do tabuleiro do jogo
├── style.css         # Estilos visuais, grid circular e classes de seleção de cor
├── script.js         # Lógica das rodadas, temporizadores, pontuação e validação
└── README.md         # Documentação do projeto
```

---

## 🚀 Como Executar o Projeto na Sua Máquina

Por se tratar de uma aplicação front-end estática (HTML, CSS e JavaScript puro), **não é necessário instalar Node.js, servidores ou pacotes adicionais** para rodar o projeto.

### Pré-requisitos

- Um navegador web atualizado (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari, etc.).
- **[Git](https://git-scm.com)** instalado (opcional, caso prefira clonar o repositório via terminal em vez de baixar o ZIP).

### Passo a passo

1. **Clone o repositório:**
   ```bash
   git clone https://github.com
   ```
   *(Alternativamente, clique no botão **Code > Download ZIP** no GitHub e extraia a pasta no seu computador).*

2. **Acesse a pasta do projeto:**
   ```bash
   cd Jogo_Estilo_Genesis
   ```

3. **Execute o jogo no navegador:**
   - **Opção 1 (Direto pelo arquivo):** Abra a pasta do projeto no explorador de arquivos do seu sistema e dê um **duplo clique** em `index.html` para abri-lo diretamente no seu navegador padrão.
   - **Opção 2 (Via Live Server no VS Code):** Abra a pasta no [Visual Studio Code](https://visualstudio.com), clique com o botão direito sobre o arquivo `index.html` e selecione **"Open with Live Server"**.

---

## 🤝 Contribuição

Contribuições são sempre bem-vindas! Se você quiser implementar melhorias (como efeitos sonoros para cada cor, placar visível na tela ou seleção de dificuldade):

1. Faça um **Fork** deste repositório.
2. Crie uma **Branch** para sua modificação (`git checkout -b feature/NovaFuncionalidade`).
3. Faça o **Commit** das suas alterações (`git commit -m 'Adiciona efeitos sonoros'`).
4. Faça o **Push** para a branch (`git push origin feature/NovaFuncionalidade`).
5. Abra um **Pull Request**.

---

## 👨‍💻 Autor

Desenvolvido por **[marceloxm](https://github.com/marceloxm)** durante os estudos na **Digital Innovation One (DIO)**.

