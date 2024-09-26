# Poc-3

O código HTML acima cria uma página web responsiva que ajusta seu layout com base no tamanho da tela usando Media Queries. Ele contém um cabeçalho com um menu de navegação, uma galeria de imagens e uma seção de texto.

1 - @media print - Define estilos específicos para quando a página for impressa. Remove a navegação e o rodapé, altera o fundo para branco e ajusta as imagens para ficarem exibidas corretamente no papel.

2 - @media only screen and (max-width: 600px) - Aplica estilos específicos para telas de até 600px de largura, ou seja, smartphones. Aqui, os itens do menu de navegação ficam empilhados verticalmente, a galeria de imagens se ajusta para mostrar uma única coluna, e o texto é exibido em uma coluna.

3 - @media only screen and (orientation: landscape) - Aplica estilos quando o dispositivo está em modo paisagem (horizontal).

4 - @media only screen and (orientation: portrait) - Aplica estilos quando o dispositivo está em modo retrato (vertical).
