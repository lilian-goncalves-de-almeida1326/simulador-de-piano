# simulador-de-piano


Este é um **Simulador de Piano Virtual** que permite ao usuário tocar músicas usando um teclado virtual. O piano contém teclas brancas e pretas, e o usuário pode interagir com ele tanto clicando nas teclas quanto pressionando as teclas correspondentes do teclado do computador.

## Funcionalidades

- **Teclas interativas**: O usuário pode clicar nas teclas do piano ou usar as teclas do teclado do computador para tocar as notas.
- **Controle de volume**: Um controle deslizante permite ajustar o volume do som do piano.
- **Exibição de teclas**: É possível ocultar ou exibir as teclas do piano com uma caixa de seleção.
- **Animação das teclas**: As teclas que são pressionadas recebem uma animação de destaque para indicar que foram acionadas.

## Como usar

1. Clone o repositório para sua máquina:
    ```bash
    git clone https://github.com/seu-usuario/piano-simulator.git
    ```

2. Abra o arquivo `index.html` em seu navegador para começar a usar o simulador de piano.

## Estrutura de arquivos

O projeto possui os seguintes arquivos principais:

- `index.html`: A estrutura HTML da página.
- `src/styles/main.css`: O estilo principal do piano, incluindo o layout e o design das teclas.
- `src/styles/reset.css`: O estilo de reset para garantir uma aparência consistente entre navegadores.
- `src/scripts/engine.js`: A lógica JavaScript que implementa a funcionalidade do piano, incluindo a reprodução das notas e a interação com o teclado.

## Tecnologias utilizadas

- **HTML**: Estrutura da página.
- **CSS**: Estilos do piano, incluindo a animação das teclas e o layout do controle de volume.
- **JavaScript**: Lógica do piano, que gerencia a reprodução das notas e interações com o teclado e a interface do usuário.

## Como funciona

### HTML
O HTML define a estrutura básica da página, com um cabeçalho que inclui o título, um controle deslizante de volume, uma caixa de seleção para mostrar ou ocultar as teclas e a lista de teclas do piano.

### CSS
O CSS aplica estilos ao layout das teclas do piano, incluindo animações para as teclas pressionadas e a estrutura geral da interface.

### JavaScript
O JavaScript controla a funcionalidade do piano, incluindo a reprodução de notas sonoras (em formato `.wav`), a interação com as teclas do teclado e a manipulação de volume e visibilidade das teclas.

#### Funções principais:
- `playTune`: Toca o som correspondente à tecla pressionada.
- `handleVolume`: Controla o volume do áudio conforme o valor do controle deslizante.
- `showHideKeys`: Mostra ou oculta as teclas do piano, com base na interação com a caixa de seleção.
- `keydown` event: Permite tocar notas usando o teclado do computador.

## Exemplo de uso

1. Clique em qualquer tecla do piano ou pressione a tecla correspondente do teclado (por exemplo, 'a', 's', 'd', etc.) para tocar uma nota.
2. Use o controle deslizante para ajustar o volume do som.
3. Marque ou desmarque a caixa de seleção para mostrar ou ocultar as teclas.

## Contribuição

Sinta-se à vontade para contribuir com melhorias no projeto, correções ou novos recursos! Basta abrir uma **issue** ou enviar um **pull request**.
