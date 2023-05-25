Plan de Erorres y Correcciones realizadas al proyecto, por: Jazmin Adelina Guzman Mejicanos

1. **let randomNumber = Math.floor((Math.random) * 100) + 1;** 
Se modifico esta linea de codigo, agregando el numero 100 en vez de 10 debido a que se requiere tomar un numero de 1 a 100, adicional a ello el "+ 1" es para que inicie del intento 1.

2. **const ATTEMPS = 10;**//Se cambio el numero 5 por 10 porque esto indica el numero de intentos

3. **const lowOrHi = document.querySelector('.lowOrHi');**//faltaba un punto para indicar que se trataba de la misma variable que es una clase en el codigo html

4. **let userGuess = Number (guessField.value);** //Faltaba la palabra Number para poder evaluar si lo que si introdujo es un numero o no.

5.  **lastResult.textContent = '!Felicitaciones! adivinaste el número!!!!';**//Se modifico el mensaje por el tipo de instruccion que esta indicando

6. **lastResult.style.backgroundColor = 'green';**//Se cambio el color de black a green para indicar que el usuario logro adivinar el numero

7. **lastResult.textContent = '!!!Pérdistes!!!';**//Se cambio el mensaje por el tipo de instruccion que decia que si llego al numero de intentos el usuario pierde y debe avisarsele

8. **lastResult.style.backgroundColor = 'black';**//Se modifico el color para mostrar que es incorrecto el numero

9. **lowOrHi.textContent = 'El número es menor!';**//Se cambio de mayor a menor porque la instruccion con el < asi lo indicaba.

10. **lowOrHi.textContent = 'El número es mayor!';**//Se cambio de menor a mayor debido al > que indicaba que el numero ingresado es mayor al numero aleatorio

11. **guessSubmit.addEventListener('click', checkGuess);**//Se modifico la palabra EventListener porque event estaba con minuscula y debido a esto el boton no funcionaba al hacer click

12. **resetButton.addEventListener('click', resetGame);**//addEventListener, event estaba en minuscula por lo que el juego no se reiniciaba

13. **randomNumber = Math.floor(Math.random()*100) + 1;**//faltaba el * 100 para que contabilizara correctamente los numeros
