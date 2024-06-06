# type conversion (conversão de tipo) / type coercion (coerção de tipo)

```js
var x = Number("0") // Type conversion, nessa linha é feita uma conversão de tipo explicíta

var y = "2"+3 // Type coercion, nessa linha é feita uma var x = Number("0") // Type conversion, nessa linha é feita uma conversão implicito do valor 3 que é número(number)para texto(string)

//onde usa expressões condicional e repetição, faz necessário um valor boolean (verdadeiro ou falso)
//Ex.
if(true){

}
// caso não fpr informado uma expressão ou um valor boolean diretamente, ele fará um Type coercion(coerção de tipo)
//Ex.
if(0){ // Nessa linha ele ira fazer uma conversâo do 0 para um boolean (verdadeiro ou falso), nesse caso 0 serà falso
}
```


