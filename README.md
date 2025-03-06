Que hace document.querySelector(".display");?
document.querySelector() es un método que permite seleccionar un elemento de la página web, utilizando un selector CSS, ".display" es el selector de clase, lo que significa que seleccionará el primer elemento que tenga la clase display.

Que hace const buttons = document.querySelectorAll("button");?
document.querySelectorAll("button") es un método que selecciona todos los elementos <button> del HTML que se encuentren en el documento y devuelve una NodeList, que es una colección de nodos de esos botones, const buttons crea una constante que almacena esa colección.

Que hace buttonText = button.textContent;?
Toma el texto que está dentro de un botón y lo guarda en la variable buttonText.

Que hace y como funciona buttons.forEach((button) => { ...}?
Es un método que se usa para recorrer todos los elementos dentro de la lista buttons y ejecutar una función en cada uno de esos elementos.

Que hace y como funciona button.addEventListener("click", () => { } )
Se usa para agregar un evento a un botón, de forma que cuando se haga clic en el botón, se ejecute una acción (lo que esté dentro de las llaves {}).
