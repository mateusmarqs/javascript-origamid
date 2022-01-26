#  :computer: JavaScript Origamid

Exercícios e anotações sobre o curso de JavaScript da Origamid.

## Variáveis

Tem duas formas de definir uma variável, são elas:
 
~~~javascript
var nome = 'Matues'
var idade = 22
var altura = 1.75
~~~ 
ou
~~~javascript
var nome = 'Matues',
    idade = 22,
    altura = 1.75

// Pode-se também crair variáveis "vazias", por exemplo:

var peso
~~~ 

#### Informações importantes sobre variáveis:

- Os nomes podem iniciar com $, _, ou letras
- Case sensitive (nome é diferente de Nome)
- Cuidado com palavras reservadas
- É mais comum usar camel case (minhaVariavel)
- Hoisting (a varável é movida para o topo do código, mas seu atributo não)

## Tipos de dados

Todos esses são os tipos de dados primitivos (imutáveis), exceto os objetos:

~~~javascript
var nome = 'André'; // String
var idade = 28; // Number
var possuiFaculdade = true; // Boolean
var time; // Undefined
var comida = null; // Null
var simbolo = Symbol() // Symbol
var novoObjeto = {} // Object
~~~ 

Para saber o tipo de derterminada variável, pode-se usar:

~~~javascript
console.log(typeof nome)
~~~ 


