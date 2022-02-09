# cartas-magicas
Ejercicio cartas Mágicas.

La empresa Magos de la Costa se ha puesto en contacto contigo para que les implementes su nuevo juego de cartas “Magia”. 
El juego estará compuesto por distintos tipos de cartas, todas ellas identificadas por un nombre, un número de colección, una rareza (común, poco común, rara y mítica). Los distintos tipos de cartas son: 
-	Tierras: principal fuente de energía que tiene el jugador. Cada tierra añade un punto de energía. Cada tierra solo puede ser de un tipo: roja, verde, azul, blanca o negra. 
-	Criaturas: estas cartas tendrán un coste de tierras variable (por ahora solo pueden costar tierras del mismo color), la vida que tiene la criatura, el poder de ataque que tiene la carta, una descripción de su efecto, y el tipo de habilidad que tiene. Por ahora solo crearemos cartas con las habilidades: 
o	Vuela
o	Vigilancia
o	Golpea dos veces
o	Prisa
-	Hechizos: tendrán un nombre y un coste de tierras (de nuevo de solo un tipo), una descripción de su efecto. Además, los hechizos pueden ser de dos tipos: conjuros o instantáneos. 

Lo que nos pide en esta primera iteración es: 
-	Implementar las clases necesarias.
-	Crear mazos de entre 20 y 30 cartas (aleatoriamente decidido).
-	Limitar el número de copias de cartas míticas a una por mazo. 
-	Todas las cartas se tienen que poder jugar.
-	Una criatura puede atacar a otra criatura haciéndole daño equivalente a su valor de daño directamente a su vida.
-	Cuando se juega una tierra aumenta la energía del jugador en 1 punto.
-	Cuando se juega un hechizo se muestra su nombre por pantalla en azul.
-	Cuando se juega una criatura se muestra su nombre por pantalla en verde.
Después de jugar una carta se elimina del mazo.
No hace falta que las cartas se ataquen entre ellas. No hace falta que el jugador tenga una mano de cartas. 


 
