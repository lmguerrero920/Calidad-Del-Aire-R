# Calidad-Del-Aire-R
En este simulador se analiza la calidad del aire en un salón-oficina teniendo en cuenta una serie de variables


La ecuación de balance de masa
Para una compartimento simple, dónde al aire interior está bien mezclado, la ecuación de balance de masa para un contaminante interior establece lo siguiente:

Acumulación de masa=flujo de masa que entra−flujo de masa que sale+fuente−sumidero

Cada término de la ecuación de balance tiene una forma matemática:

1 La acumulación de masa es la derivada de la masa del contaminante en el interior con respecto al tiempo, dm/dt
. Si V representa el volumen del compartimento y C  la concentración en un momento dado, entonces la masa m del contaminante en el aire interior se obtiene como C⋅V y dm/dt=V⋅dC/dt si el volumen V es constante.

2 El flujo de masa que entra es igual al producto del flujo de aire que entra al compartimento Q
 por la concentración entrante Ce , esto es, Q⋅Ce

3 El flujo de masa que sale es el producto de Q y la concentración C en el aire interior, esto es Q⋅C

4 El flujo volumétrico de aire que entra y sale del compartimento se puede estimar como Q=ACH⋅V, dónde ACH se conoce como la Tasa de Intercambio de Aire y tiene dimensiones de t−1

5 La fuente es cualquier proceso que emita al aire interior el contaminante de interés a una tasa o flujo de masa E ,con dimensiones de mt−1

6 Si el contaminante es conservativo y no existen filtros que eliminen el contaminante de interés, el sumidero es igual a cero

Con estas definiciones, la ecuación queda como:

V dC/dt=QCe+E−QC        (ecuacion 1)

La ecuación 1, es una ecuación diferencial lineal de primer orden. Su solución se puede consultar en cualquier libro de ecuaciones diferenciales ordinarias. Si se supone que la concentración inicial del contaminante en el interior del compartimento es Co, las soluciones son:



C(t)=Co+(EV)∗t         (ecuacion 2)


La ecuación 2 es la solución cuando el compartimento esta cerrado, es decir, Q=0. La ecuación 3 es la solución cuando el compartimento esta abierto al exterior (puertas y/o ventanas abiertas) o esta cerrado pero tiene una tasa de infiltración de aire (por las rendijas en puertas y ventanas) significativa. En ambas ecuaciones, Co y Ce pueden estar en ppm o μg/m3 , V en m3 , E en L/h o mg/h , ACH en 1/h  y t en horas.


Cuando el “contaminante” es el dióxido de carbono, CO2 , y el espacio está ocupado por N personas, la tasa de emisión se puede estimar como N⋅E
, dónde E es ahora la tasa de generación de CO2  por persona, ya que el CO2  es un producto de la exhalación en el proceso de la respiración humana. En términos generales, se estima que un adulto realizando actividades de oficina genera 20 litros de CO2  por hora.![download](https://user-images.githubusercontent.com/52765474/216083828-05edd4b6-1f0a-4848-a114-81d30ece9ec6.png)

Figura 1. Esquema de entradas y salidas de un contaminante de interiores en un compartimento simple



Referencia:

Ramos, H.S.;Magaña, V.E. & Carrera, V.J.M. (2015). Introducción a la Modelación del Agua, del Aire y del Transporte de Contaminantes en el Suelo. Universidad Juárez Autónoma de Tabasco. Villahermosa, Tabasco, México. 128 p.
