# Controle de Despesas

![Captura de tela 2023-06-28 - 21 00 32](https://github.com/vhasckel/controle-de-despesas/assets/85519759/92c7729a-e22b-46e3-94dc-2d8b80f7f754)


O app permite adicionar suas despesas, receitas e saldo total atualizado de acordo com suas movimentações.<br>

### Features usadas

**localStorage()**<br>
API do navegador que permite persistir dados. Na aplicação salva a lista e os valores das transações para nao serem perdidas ao recarregar a página.
<br>

**Math.abs()**<br>
Usado para retirar o operador do número.

**Math.round()**<br>
Retorna o valor arredondado do inteiro mais próximo. Foi usado junto ao Math.random() para gerar um ID para cada transação.

**Math.random()**<br>
Usado para gerar um número pseudoaleatório entre 0 e 1. Na aplicação foi usado para gerar uma ID para cada transação, junto do Math.round() para arredondar para o inteiro mais próximo.

**.filter()**<br>
Usado para manipulação de arrays. Recebe uma função como argumento e percorre cada item do array genradno um novo array com os dados que passaram no teste.

**.forEach()**<br>
Manipulação de arrays. Recebe uma função como parametro que será executada para cada item da array.

**.reduce()**<br>
Manipulação de dados, usado quando se há necessidade de reduzir um array em um único dado.
 
**.toFixed()**<br>
Usado para formatação de números decimais.


**.push()**<br>
Método para adicionar um ou mais elementos ao final de um array.


**.trim()**<br>
Método usado para remover espaços em branco encontrados no começo ou ao final de um texto.


**.prepend()**<br>
Método para inserir conteúdo no início de um elemento HTML, assim, sempre que alguma lista é atualizada esse conteúdo é sempre fixado no índice 0.
