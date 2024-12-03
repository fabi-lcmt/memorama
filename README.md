Este proyecto esta conformado por tres archivos html, css y js.
En html se define la estructura del programa el cual es un juego de memoramas, en el se define la estructura del tablero el cual esta conformado
por botones en una cuadricula de 6x6, tambien se define la estructura de las estadisticas la cual muestra el nuemro de aciertos y tambien el tiempo restante.
En el css se establece el diseño del tablero, se utiliza un fondo degradado, con tipografia clara y con cada uno de los elemnetos con bordes redondeados,
ademas que tanto el tablero de juego, las estadisticas y un boton de reinicio cunetan con un fondo semitransparente.
En el código de JavaScript: se barajean las tarjetas al azar y permite al jugador destaparlas para encontrar los pares. Se usa un temporizador 
que decrece desde 180 segundos y bloquea el juego si llega a 0. Al destapar dos tarjetas, se verifica si coinciden, si es así, suma un acierto,
si no, las oculta. Se lleva el conteo de movimientos y aciertos, y reproduce sonidos según las acciones. La función de reinicio restablece el estado del juego para comenzar una nueva partida.
