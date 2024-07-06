# Excel 📅 ![alt text](image.png)

### 📌Funções básicas:

#### SOMA(num1;num2) podendo usar um intervalo de células
#### MULT(num1;num2) podendo usar um intervalo de células
#### MÉDIA(intervalo)
#### MÁXIMO(intervalo)
#### MÍNIMO(intervalo)
#### QUOCIENTE(numerador;denominador)

OBS👉 SUBTRAÇÃO não existe como função no Excel: subtração se faz através da fórmula.

### 📌Funções relativas ou absolutas:

👉 É quando você precisa travar o valor de uma célula - pressione F4 - (absoluta: $A$2) ou travar apenas valores da linha ou coluna (relativas: $A2  ou  A$2).

### 📌SOMASE

👉 Soma se uma condição acontecer, ou seja, em um intervalo, atendido um critério, se faz a soma de outro intervalo selecionado.

### 📌CONT.SE

👉 Contar se uma condição acontecer, logo, usa intervalo que será analisado e o critério que será procurado e contado.

### 📌CONT.VALORES

👉 Conta a quantidade de linhas da coluna que está em uso, como exemplo podemos contar a quantidade de chamados ou a quantidade de pedidos, pois o resultado não será o gerado em relação aos valores contidos nas células e sim, a quantidade de linhas que foi utilizado na coluna em que foi selecionado o intervalo a ser analisado. CONT.VALORES(valor1; valor2)

### 📌CONT.VAZIO

👉 Vai contar os espaços em branco do intervalo selecionado.

### 📌CONCAT

👉 Serve para concatenar células (texto1; texto2)... basta referenciar as células que serão concatenadas em uma nova e única célula ou células mescladas.

 OBS👉 quando usa a função concat os valores ficam juntos (sem espaços), então, para resolver esse problema, no lugar de usar concat, use o operador lógico & para concatenar e para dar espaço use " ".

### 📌PROCV

👉 (valor procurado; matriz tabela ---> é quando vc seleciona a coluna onde está o valor que se procura e arrasta até a coluna que dará o resultado esperado; num_indice_coluna ---> é quando aponta o número da posição da coluna que dará o resultado dentro da seleção (matriz); procurar intervalo ---> aqui é para saber se vai querer que o resultado seja exato ou um valor aproximado)

👉 Nada mais é do que procurar na vertical, ou seja, através de uma referência você procura um valor. O valor procurado vai ser encontrado através da sua referência, aí você vai começar a seleção pela coluna onde está o valor que você está usando como referência para encontrar o resultado e vai arrastar a seleção até toda a área (formando uma matriz) onde você quer procurar o dado que você quer obter. Observação importante é que a função PROCV vai fazer a varredura apenas nas colunas a direita da coluna de referência. A coluna índice será a coluna onde se encontra o dado procurado. Você pode escolher ter um dado resposta de um valor aproximado ou a correspondência exata a sua referência.

### 📌SE

👉 Essa função utiliza o teste lógico para verificar se a condição foi atendida ou não. 

### 📌PROCX

👉 Quando precisar fazer busca sem que seja a direita da referência (PROCV), use a função PROCX que não tem essa limitação de direção, logo, não vai ter problema. 

👉 (pesquisa valor ---> clica na célula onde está o valor que vai ser procurado; pesquisa matriz ---> seleciona a coluna onde o valor será pesquisado; matriz retorno ---> seleciona a coluna que será onde o valor que será o retorno/resultado está; só isso basta para usar a função ENTER)

### 📌ALEATORIOENTRE

👉 (ALEATORIOENTRE(inferior, superior)) função para gerar números aleatórios dentro de um intervalo definido. Serve para gerar dados para testes, serve para gerar senhas, etc

## Alguns atalhos importantes:

#### CTRL + E
Preenchimento relâmpago ---> pode ser usado para adiantar o preenchimento de dados das colunas que estamos particionando de outra coluna com os dados separados apenas por separador (várias informações na mesma coluna).

#### CTRL + X
Serve para recortar uma coluna para trocá-la de lugar.

#### CTRL +
Apenas com o sinal de mais, ao clicar na posição que vai inserir a coluna, você cola a coluna recortada para trocar de lugar.

