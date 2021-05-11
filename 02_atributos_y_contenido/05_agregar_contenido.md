# Adición de nuevos elementos

Los métodos **append()**, **prepend()**, **before()** y **after()** también se pueden usar para agregar elementos recién creados. La forma más sencilla de crear un nuevo elemento HTML con jQuery es la siguiente:

```js
var txt = $("<p> </p>").text("Hola"); 
```

El código anterior crea un nuevo elemento <p> , que contiene el texto Hola y lo asigna a una variable llamada txt .
Ahora, podemos usar esa variable como parámetro de los métodos antes mencionados para agregarla a nuestro HTML, por ejemplo:
**HTML**:
