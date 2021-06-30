## ¿Utilizaste alguna librería externa para hacer la petición HTTP?¿Por qué?

No , utilice el objeto XMLHttpRequest de JS ya que me permite obtener los datos de la URL , reduciendo las solicitudes redundates y la carga por parte del servidor. Tambien sé utilizar FETCH de JS para acceder y manipular datos.                                                                                                                                                                                                                                                                                                      í

## ¿Qué estrategia utilizaste para la manipulación de datos?
La principal estrategia que utilice fue reconocer la informacion y el valor de los mismos , cual era el contexto al que se estaba asociando la informacion, en base a eso ver que valores tenia y como podria jugar con ellos para exponer informacion.


## ¿Qué ha sido lo más difícil de esta prueba para ti?
Se me dificulto la parte de realizar para los años la misma logica que para la grafica del genero, ya que la fecha estaba completa , entonces utilice la propiedad de JS split que me permite dividir la informacion en un caracter de partida , pero me generaba un error porque no encontraba al final una fecha de un array, y no lograba dividirlos para poder exponerlos en el label de la grafica.

## ¿Qué ha sido lo más fácil?

Realizar la peticion HTTP y consumir los datos , permitir que las graficas de la libreria fueran responsive y la informacion se acoplara al tamaño padre, tambien implementar clases de el framework de Boostrap para el diseño de las mismas.

## En base a los datos, ¿qué otro tipo de visualizaciones crees pertinentes para comunicar?

1. Identifique que el json no se encontraba agrupado con un nombre especifico , aunque no es algo que afecte en cierta manera los datos pero es una buena practica realizarlo.
    ejemplo: "data":[{}].
    
2. El ultimo array del json no tenia una fecha.
3. Habia un array vacio, el cual se visualizaba al momento de consultar los datos "{}"
