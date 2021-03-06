# Exercícios de PHP

## Exercício 01
Criar **variáveis** e/ou **constantes** para:

- Data de hoje
- Nome de uma pessoa
- Nome de um curso que esta pessoa faz
- Carga horária deste curso
- Limite de faltas

Coloque dados nestas variáveis e faça com que o script mostre no HTML uma mensagem apresentando o nome da pessoa, o nome do curso, a carga horária do curso e o limite de faltas.
 


## Exercício 02 - Arrays
Crie **dois arrays** para armazenar os dados fictícios de duas pessoas diferentes: nome de usuario, email, senha, idade, sexo e cidade.

Em seguida, mostre os valores de **nome de usuario**, **email**, **idade** e **sexo** de cada pessoa dentro de tags HTML de conteúdo (como article, section, h2, p etc).

**Desafio:** destaque estes blocos de conteúdo usando CSS.


## Exercício 03 - Condicionais
Crie um script PHP que permita avaliar o valor de um salário e calcular um novo valor de salário baseado nos seguintes critérios:

- Se salário menor que 500, calcule um aumento de 15%
- Senão, se salário menor ou igual a 1000, calcule um aumento de 10%
- Senão calcule um aumento de 5%

Mostre no HTML uma mensagem informando o valor do salário antigo (antes do reajuste) e do novo salário (após o reajuste).

**DESAFIO:** existe uma função nativa do PHP que permite mudar a forma como números são exibidos na tela. Descubra qual é esta função e a utilize para exibir os salários com o sinal de "." para separador de milhar e "," para separador de casa decimal com duas casas decimais.


## Exercício 04 - Loop e Array
Crie um array associativo com 4 nomes de linguagens e uma pequena descrição para cada.

Exemplo: 

- HTML: Estruturação
- CSS: Estilos
- JS: Comportamentos
- PHP: Back-End

Em seguida, use loop para iterar sobre este array e exibir todos os dados em linhas de uma tabela HTML conforme exemplo abaixo:

ID  | Linguagem   |   Descrição
--- | ---------   |   --------
1   | HTML        |   Estruturação
2   | CSS         |   Estilos
3   | JS          |   Comportamentos
4   | PHP         |   Back-End

**Desafio:** pense em uma maneira de exibir um ID (fictício) para cada curso.


## Exercício 05 - Funções
- Crie duas variáveis para representar as notas de um aluno.
- Calcule a média destas notas e verifique a situação do aluno (aprovado ou reprovado).

**Desafio:** use funções para isolar a lógica de cálculo da média e verificação da situação do aluno.


## Exercício 06 (na pasta site)

1. Adicione uma página de Contato ao site
2. Mostre no rodapé a data e hora atual

**Desafio**: programe um script PHP que permita identificar qual página está aberta no momento, e partir disso personalize o título de acordo com a página. 

Exemplos:
- Está na index.php? Então mostre no `title`: Página Inicial - Site PHP
- Está na produtos.php?	Então mostre no `title`: Produtos - Site PHP
- Está na servicos.php?	Então mostre no `title`: Serviços - Site PHP

## Exercício 07
No HTML, crie um formulário para cadastro (simulação) de produtos com os campos:

- Nome do produto (campo de texto)
- Fabricante (`select` de opções com pelo menos 4 nomes de fabricantes) - ***Obs.: as opções desta lista devem ser carregadas a partir dos dados de um array PHP com os nomes dos fabricantes.*** 
- Preço (campo de número com valor mínimo de 100 e máximo de 10000, além de suporte à 2 casas decimais para os centavos)
- Descrição (área de texto)

Faça a programação de processamento do formulário considerando o envio/recebimento via POST, filtros de sanitização e validação de campos obrigatórios. 
