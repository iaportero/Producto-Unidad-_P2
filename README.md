# Producto Unidad_P2
Integrantes: Bryan Santiago Torres Reyes , Roger Steveen Armas Simbaña , Israel Alejandro Portero Cazares

Objetivos:

Objetivo general

Familiarizar e implementar la teorira de los diferentes teoremas presentados en el capitulo 19 para el analisis y resolucion de problemas de circuitos electricos.

Objetivos especificos

*  Analizar y resolver circuitos en ca con el teorema de superposicion.

*  Aplicar el teorema de Thevenin y Norton en el analisis y resolucion de circuitos en ca.

*  Aplicar el teorema de transferencia de potencia maxima en circuitos ca.

Marco Teorico / Diagramas

*  Teorema de superposicion en ca

El teorema de superposicion en corriente alterna expresa lo siguiente :

En un circuito con fuentes múltiples, la corriente en cualquier rama dada puede calcularse al determinar las corrientes producidas en esa rama en particular por cada fuente,con todas las demás fuentes siendo reemplazadas por sus impedancias internas. La corriente total en la rama dada es la suma fasorial de las corrientes individuales que haya en dicha rama.

Pasos para aplicar el toerema de superposicion en un circuito ca :

1.  Dejar una de las fuentes de voltaje (corriente) en el circuito y reemplazar todas las demás con su impedancia interna. En fuentes de voltaje ideales, la impedancia interna es de cero. En fuentes de corriente ideales, la impedancia interna es infinita. A esteprocedimiento se le llamará poner en cero la fuente.

2.  Determinar la corriente en la rama de interés producida por la fuente restante.


3.  Repetir los pasos anteriores en cada una de la fuentes presentes en el circuito . Al final se tendra igual el numero de valores de corriente con el de las fuentes presentes en el circuito.

4. Sumar los valores obtenidos de corriente individuales , en forma fasorial.


![](https://github.com/iaportero/Trabajo-de-Investigacion_P2/blob/main/Imagenes/imag%208.png)



*  Teorema de Thevenin en ca

El teorema de Thévenin establece que en un circuito de corriente alterna con dos terminales se puede sustituir por otro sencillo que consta de un generador de corriente alterna Vth y una impedancia en serie Zth.  Su utilidad consiste en que cuando se hacen cálculos repetitivos se ahorra mucho tiempo  y la ventaja es tanto mayor cuanto más complicado es el sistema eléctrico.

Equivalencia 

La forma de circuito equivalente de Thevenin establece que Sin importar cuán complejo sea el circuito original, siempre es posible reducirlo a esta forma equivalente. La fuente de voltaje equivalente se designa mediante Vth; la impedancia equivalente se designa con Zth.

![](https://github.com/iaportero/Trabajo-de-Investigacion_P2/blob/main/Imagenes/i%201.png)


El siguiente grafico muestra un diagrama de bloques que representa un circuito de ca de cualquier complejidad dada. Este circuito dispone de dos terminales de salida, A y B. Se conecta una impedancia de carga, ZL, a las terminales. El circuito produce cierto voltaje, VL, y cierta corriente,
IL,

![](https://github.com/iaportero/Trabajo-de-Investigacion_P2/blob/main/Imagenes/i%202.png)

Voltaje equivalente de Thevenin (Vth)

El voltaje equivalente de Thevenin se define como el voltaje de circuito abierto entre dos
terminales especificadas en un circuito.


![](https://github.com/iaportero/Trabajo-de-Investigacion_P2/blob/main/Imagenes/i%203.png)


Impedancia equivalente de Thevenin (Zth)

La impedancia equivalente de Thevenin es la impedancia total que aparece entre dos terminales
especificadas en un circuito dado con todas las fuentes siendo reemplazadas por
sus impedancias internas.



Pasos para aplicar el teorema de thevenin en ca  :

1.  Abrir las dos terminales entre las que se desea determinar el circuito de Thevenin. Esto
se logra retirando el componente desde donde se va a ver el circuito.

2.  Determinar el voltaje entre las dos terminales abiertas.

3.  Determinar la impedancia vista desde las dos terminales abiertas con las fuentes de
voltaje ideales habiendo sido reemplazadas por cortos y las fuentes de corriente ideales
reemplazadas con aberturas (ajustadas a cero).

4.  Conectar Vth y Zth en serie para producir el circuito equivalente de Thevenin completo.

![](https://mielectronicafacil.com/wp-content/uploads/2019/11/Thevenin-AC.png)


*  Teorema de Norton en ca

En términos prácticos, este teorema establece que se puede sustituir el circuito por una fuente de corriente y una impedancia o resistencia conectados en paralelo.

El teorema de Norton muestra cómo determinar In y Zn. Una vez que se determinan, simplemente
se les conecta en paralelo para obtener el circuito equivalente de Norton

![](https://github.com/iaportero/Trabajo-de-Investigacion_P2/blob/main/Imagenes/i%204.png)

Fuente de corriente equivalente de Norton (In)

La corriente equivalente de Norton se define como la corriente que aparece al poner en
cortocircuito las dos terminales específicas en un circuito dado.

![](https://github.com/iaportero/Trabajo-de-Investigacion_P2/blob/main/Imagenes/i%205.png)

Impedancia equivalente de Norton (Zn)

Zn se define igual que Zth: es la impedancia total que aparece entre dos terminales específicas de
un circuito dado visto desde las terminales abiertas y con todas las fuentes reemplazadas por sus
impedancias internas.

Pasos para aplicar el teorema de Norton en ca 

1.  Reemplazar la carga conectada a las dos terminales entre las cuales se va a determinar
el circuito de Norton con un corto.

2.  Determinar la corriente a través del corto. Ésta es In.

3.  Abrir las terminales y determinar la impedancia entre las dos terminales abiertas y
con todas las fuentes reemplazadas por sus impedancias internas. Ésta es Zn.

4.  Conectar In y Zn en paralelo.

![](https://mielectronicafacil.com/wp-content/uploads/2019/11/Norton-AC.png)

* Teorema de la maxima transferencia de potencia

Se transfiere potencia máxima a una carga conectada a un circuito cuando la impedancia
total es el complejo conjugado de la impedancia de salida del circuito.

Se considera lo siguiente :

1.  El complejo conjugado  y viceversa, donde las resistencias son iguales
en magnitud y las reactancias también iguales en magnitud pero de signo opuesto.

2.  La impedancia  es efectivamente la impedancia equivalente de Thevenin vista desde las terminales
de salida.

3.  Cuando ZL es el complejo conjugado de Zsal, se transfiere potencia máxima desde el
circuito hasta la carga con un factor de potencia de 1.

![](https://github.com/iaportero/Trabajo-de-Investigacion_P2/blob/main/Imagenes/i%206.png)

Expresado en formula se tiene :

![](https://github.com/iaportero/Trabajo-de-Investigacion_P2/blob/main/Imagenes/i%207.png)

![](https://github.com/iaportero/Trabajo-de-Investigacion_P2/blob/main/Imagenes/i%208.png)

Diagramas :

![](https://github.com/iaportero/Trabajo-de-Investigacion_P2/blob/main/Imagenes/i%209.png)


Desarrollo :

https://github.com/iaportero/Trabajo-de-Investigacion_P2/tree/main/Codigo%20Fuente


Aportaciones:




Conclusiones:

*  El teorema de superposicion es viable tanto para el analisis y resolucion en circuitos en cd como en ca.

*  Para cualquier circuito en ca el teorema de Thevenin proporciona una reduccion eficaz para la resolucion de  cualquier circuito que se presente y consta  de dos partes solamente  : voltaje equivalente y impedancia equivalente

*  Al igual que Thevenin el terema de Norton proporciona un método para reducir cualquier circuito de ca a una forma equivalente
compuesta , la diferencia es que  forma una fuente de corriente equivalente dispuesta en paralelo con una impedancia equivalente.

*  Se transfiere potencia máxima a una carga cuando la impedancia de carga es el complejo conjugado de
la impedancia del circuito

Anexos

Link del video



Link del articulo

https://github.com/iaportero/Trabajo-de-Investigacion_P2/blob/main/Articulo/articulo3.pdf

Bibliografia 

Principios de Circuitos Electricos, Floyd .L.Thomas,Mexico 2007,Recuperado : 17/02/2021. Cap 19 , Pag: 809-841



TRANSFERENCIA DE POTENCIA MÁXIMA EN CIRCUITOS AC. (n.d.). Retrieved February 17, 2021, from https://www.tina.com/maximum-power-transfer-in-ac-circuits/



▷ Teorema de Thévenin y Norton【 Definición y Ejemplos 】. (n.d.). Retrieved February 17, 2021, from https://mielectronicafacil.com/analisis-de-circuitos/teorema-de-thevenin-y-norton/#corriente-directa-dc1


Teorema de Thévenin - EcuRed. (n.d.). Retrieved February 17, 2021, from https://www.ecured.cu/Teorema_de_Thévenin


















