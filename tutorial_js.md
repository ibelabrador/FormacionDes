# Tutorial Javascript

## Asignación de suma

```js
var a = 15; //definimos la variable
a += 2; //es lo mismo que: a = a + 2;
```

## Asignación de resta

```js
var m = 10; //definimos la variable
m -= 5; //es lo mismo que m = m - 5;
```

## Asignación de multiplicación

```js
var a = 4; 
a *= 2; // es lo mismo que a = a * 2;
```

## Asignación de división

```js
var a = 4; 
a /= 2; // es lo mismo que a = a / 2;
```

## Cadena de carateres

```js
var cadena = "Isa";
var cadena2 = 'Isa y sus perritos';
```
## Escapar comillas

```js
var cadena = "Soy un perrito \"rellenito\" de amor"
```

## Secuencia de escape

```js
var cadena = "Soy un perrito 'rellenito' de amor";

var cadena2 = 'Soy un perrito "rellenito" de amor';
```

## Unir cadena de caracteres

```js
var nombre = "Isabel" + " Cristina";
//Recordar agregar los espacios en los caracteres, dentro de las comillas
```

## Unir cadena con variables

```js
var edad = 3;
var cadena = " Hunter tiene " + edad + " años";
```

## Agregar variables a cadenas de caracteres

```js
var cadena1 = "Soy un perrito";
var complemento = " muy gonito";

cadena1 += complemento;
```
## Longitud de una cadena de caracteres

```js
var cadena = "Isa";
cadena.length // Tiene 3 caracteres

var cadena2 = "Isa ";
cadena2.length // Tiene 4 caracteres, porque los espacio cuentan, así como los simbolos.
```

## Notación de corchetes: primer carácter
```js
var corchetes = "Smoke";
corchetes[0] // La respuesta será S
```

## Inmutabilidad

```js
var cambio = "ola";
cambio = "hola";
```

## Notación de corchetes: enésimo carácter 

```js
var cadena = "Smoke"; 
cadena[0]; // S
cadena[1]; // m
cadena[2]; // o
cadena[3]; // k
cadena[4]; // e
cadena[5]; // undefined
```

## Notación de corchetes: último carácter

```js
var cadenaLarga = "Paralaculacocolaorestesicn";
cadenaLarga[cadenaLarga.length - 1] // La respuesta es n
```

## Notación de corchetes: de derecha a izquierda

```js
var penultimo = "Tierra";
penultimo[penultimo.length - 4] // La respuesta es e
penultimo[penultimo.length - 2] // La respuesta es r
var n;
n = 5;
penultimo[penultimo.length - n] // La respuesta es i
```

## Palabras en blanco

```js
var sustantivo = "perro";
var accion = "come";
var adverbio = "basura";
var palabrasEnBlanco = "El " + sustantivo + " " + accion + " " + adverbio + " en la calle";
palabrasEnBlanco // El perro come basura en la calle
```

## Arreglos

```js
var familia = [“Hunter”, “Tierra”, “ Smoke”, “Isa”];
var edades = [3, 7, 2, 30];
```

## Arreglos anidados

```js
var familia = [[“hunter”, 3], [“Tierra”, 7], [“somke”, 2], [“Isa”, 30]];
```

## Acceder a los elementos de un arreglo 

```js
var familia =  [“Hunter”, “Tierra”, “ Smoke”, “Isa”];
familia[1] // La respuesta será “Tierra” 
```

## Modificar los datos de un arreglo 

```js
var familia = [“Hunter”, “Tierra”, “ Smoke”, “Isa”];
familia[3] = “Isabel”;
//El arreglo queda:[“Hunter”, “Tierra”, “ Smoke”, “Isabel”]
```

## Acceder a arreglos multidimensionales

```js
var familia = [[“hunter”, 3], [“Tierra”, 7], [“somke”, 2], [“Isa”, 30]];
familia[3][0] // El resultado es “Isa”
```

## Método .push()

```js
var colores = [“rojo”, “negro”, “verde”, “morado”];
colores.push(“amarillo”);
colores = [“rojo”, “negro”, “verde”, “morado”, “amarillo”] // Sería el nuevo arreglo
```

## Método .pop()

```js
var colores = [“rojo”, “negro”, “verde”, “morado”];
colores.pop();
colores = [“rojo”, “negro”, “verde”] // Sería el nuevo arreglo
```

## Método .shift()

```js
var colores = [“rojo”, “negro”, “verde”, “morado”];
colores.shift();
colores =  [“negro”, “verde”, “morado”] // Sería el nuevo arreglo
```

## Método .unshift()

```js
var colores = [“rojo”, “negro”, “verde”, “morado”];
colores.unshift(“amarillo”);
colores =  [“amarillo”, “rojo”, “negro”, “verde”, “morado”] // Sería el nuevo arreglo
```

## Lista de compras 

```js
var lista = [[“Verduras”, 11], [“frutas”, 10], [“quesos”, 5]];

console.log(“voy a comprar ” + lista[1][0] + “ y algunos “ + lista[2][0]) // ‘Voy a comprar frutas y algunos quesos
```

## Funciones

```js
function tengoHambre() {
console.log(“Quiero un sanwichito”);
}

tengoHambre();
```

## Párametros y Argumentos

```js
function sumar(a, b) {
var suma = a + b;
console.log(“El resultado de ” + a + “+” + b + “ es: ”+ suma);
}

sumar(2, 8);