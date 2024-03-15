# Projeto Implementando JavaScript

# Introdução
### Neste projeto foi escolhido dois códigos JavaScript para desfragmentá-los e descorrer sobre o que cada elemento faz, sendo assim os códigos escolhidos são:

 - ![Pegar URL](imagem)
 - ![Adicionar Caracteres](imagem)

### Obs: Os códigos estão embutidos no html, portanto é necessário utilizar a estrutura HTML.

# Desenvolvimento

## O que cada elemento do código significa:

## Código 1

### <script>document.write(window.location.href);</script>

- "<script>", tag HTML que indica que o conteúdo é um script.
![Script-print](imagem)

- "Document.write()", método JavaScript que escreve conteúdo na página HTML.
![Document-print](Imagem)

- "window.location.href", acessa a prioridade "href" do objeto "location" do navegador, que contém o URL atual da página.
![window-print](imagem)

## Código 2 

### <script> var str = 'Terminal Root'; var str = str.slice(0, -5)+' Bash'; document.write(str); </script>

- "<script>", Tag HTML que indica que o conteúdo é um script.
![Script-print](imagem)

- "var str ='Terminal Root'", define uma variável chamada "str" e atribui a ela o valor "Terminal Root".
![varStr-print](imagem)

- "var str = str.slice(0, -5)+"bash"; ", corta os últimos 5 caracteres da string "str" utilizando o método "slice" e concatena "bash" ao resultado, atribuindo esse novo valor á variável "str".
![varSlice-print](imagem)

- "document.write(str);", escreve o valor da variável "str" na página HTML. Nesse caso, "Terminal Bash" será escrito na página.
![documentWrite-print](imagem)

# Conclusão 

### A implementação de JavaScript em website é importante pois desempenha um papel fundamental na criação de websites interativos, dinâmicos e funcionais, melhorando a experiência do usuário e permitindo uma maior interação e personalização.

# Tecnologias Utilizadas

[MDN Web Docs](https://developer.mozilla.org/pt-BR/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

[Markdown e Pandoc](http://cursos.leg.ufpr.br/prr/capMarkdown.html#:~:text=Para%20inserir%20uma%20imagem%2C%20a,texto%5D(imagem)%20.)

[Pipz](https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open)

[Free Code Camp](https://www.freecodecamp.org/portuguese/news/como-formatar-codigo-em-markdown/)

[DevMedia](https://www.google.com/amp/s/www.devmedia.com.br/amp/javascript-tutorial/37257)
