## import.python : Un código en Python para importar archivos de texto y graficar en 1D y 2D 
Para ver el funcionamiento del código y su análisis respectivo, ir al artículo: [nepy.pe/es/import.python.](http://www.nepy.pe/es/programacion/importar-y-graficar-datos-en-el-lenguaje-python/) 

Existen 3 archivos: 

1. rouletteDeterministic.m : Se determina una apuesta fija, e.g., apostar solo al color rojo.
2. rouletteStochastic.m : En cada ronda se apuesta aleatoriamente a distintos números.
3. rouletteMartingale.m : Se usa la estrategia de Martingale.

Todos los archivos requieren un valor de entrada. Los detalles aparecen explicados en el mismo código.
Para los parámetros dados (laps = 1000000), cada archivo toma menos de 5 minutos en Matlab y entre 15 y 60 minutos en Octave. Para reducir el tiempo considerar valores más pequeños para "laps".
