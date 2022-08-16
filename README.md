UNIVERSIDAD DE LAS FUERZAS ARMADAS - ESPE

- NOMBRE: JUAN HURTADO
- NRC: 7318
- FECHA: 8 JULIO 2022

# InformeCorreccionExamLab

***1.-OBJETIVOS***

I) Realizar la correcion del examen de labratorio numero 2

**OBJETIVO ESPECÍFICO**

II) Aprender a usar los sistemas de lectura de voltaje mediante un multímetro, aplicando los conocimientos adquiridos.

III) Determinar lo que pida cada uno de los enunciados de cada ejercicios (total 3).

2. MARCO TEÓRICO (RESUMEN)

SUPERPOSICION: 

El principio de superposición establece que la tensión entre los extremos (o corriente a través) de un elemento de un circuito lineal es la suma algebraica de las tensiones (o corrientes) a través de ese elemento debidas a cada una de las fuentes independientes cuando actúa sola.

El principio de superposición ayuda a analizar un circuito lineal con más de una fuente independiente mediante el cálculo de la contribución de cada fuente independiente por separado.

La aplicación del principio de superposición tiene los siguientes pasos:

-- 1. Apagar todas las fuentes independientes excepto una.
Encontrar la salida (tensión o corriente) debido a la fuente activa.

-- 2. Repetir el paso anterior para cada una de las fuentes
independientes presentes en el circuito.

-- 3. La contribución total vendrá dada por la suma algebraica de las
contribuciones de cada una de las fuentes independientes.

Algunas observaciones:

-- Apagar una fuente independiente de tensión implica reemplazarla
por una fuente de tensión de 0V (cortocircuito).

-- Apagar una fuente independiente de corriente implica reemplazarla
por una fuente de corriente de 0A (circuito abierto).

-- Las fuentes dependientes no se modifican.

THEVENIN: 

En la teoría de circuitos eléctricos, el teorema de Thévenin establece que si una parte de un circuito eléctrico lineal está comprendida entre dos terminales A y B, esta parte en cuestión puede sustituirse por un circuito equivalente que esté constituido únicamente por un generador de tensión en serie con una resistencia, de forma que al conectar un elemento entre los dos terminales A y B, la tensión que queda en él y la intensidad que circula son las mismas tanto en el circuito real como en el equivalente.

Para calcular la tensión de Thévenin, Vth, se desconecta la carga (es decir, la resistencia de la carga) y se calcula VAB. Al desconectar la carga, la intensidad que atraviesa Rth en el circuito equivalente es nula y por tanto la tensión de Rth también es nula, por lo que ahora VAB = Vth por la segunda ley de Kirchhoff.

Debido a que la tensión de Thévenin se define como la tensión que aparece entre los terminales de la carga cuando se desconecta la resistencia de la carga también se puede denominar tensión en circuito abierto.

Para calcular la resistencia de Thévenin, se desconecta la resistencia de carga, se cortocircuitan las fuentes de tensión y se abren las fuentes de corriente. Se calcula la resistencia que se ve desde los terminales AB y esa resistencia RAB es la resistencia de Thevenin buscada Rth = RAB

MAXIMA TRANSFERENCIA DE POTENCIA:

En ingeniería eléctrica, electricidad y electrónica, el teorema de máxima transferencia de potencia establece que, dada una fuente, con una resistencia de fuente fijada de antemano, la resistencia de carga que maximiza la transferencia de potencia es aquella con un valor óhmico igual a la resistencia de fuente. También este ayuda a encontrar el teorema de Thevenin y Norton.

El teorema establece cómo escoger (para maximizar la transferencia de potencia) la resistencia de carga, una vez que la resistencia de fuente ha sido fijada, no lo contrario. No dice cómo escoger la resistencia de fuente, una vez que la resistencia de carga ha sido fijada. Dada una cierta resistencia de carga, la resistencia de fuente que maximiza la transferencia de potencia es siempre cero, independientemente del valor de la resistencia de carga.

Se dice que Moritz von Jacobi fue el primero en descubrir este resultado, también conocido como Ley de Jacobi.

Transferencia de potencia máxima Teorema establece que: una carga resistiva, al estar conectada a una red de CC, recibe la máxima potencia cuando la resistencia de la carga es igual a la resistencia interna conocida como (resistencia equivalente de Thevenin) de la red fuente vista desde los terminales de carga. El teorema de transferencia de potencia máxima se usa para encontrar la resistencia de carga para la cual habría la cantidad máxima de transferencia de potencia de la fuente a la carga.

El teorema de máxima transferencia de potencia se aplica tanto al circuito de CC como al de CA. La única diferencia es que en el circuito AC la resistencia se sustituye por la impedancia.

El teorema de transferencia de máxima potencia encuentra sus aplicaciones en sistemas de comunicación que reciben señales de baja intensidad. También se utiliza en altavoz para transferir la potencia máxima de un amplificador al altavoz.

Una resistencia variable RL está conectada a una red de fuente de CC como se muestra en el diagrama de circuito de la figura A a continuación y la figura B representa el voltaje de Thevenin VTH y la resistencia de Thevenin RTH de la red de fuente.

El objetivo del teorema de transferencia de máxima potencia es determinar el valor de la resistencia de carga RL, de modo que reciba la máxima potencia de la fuente de CC.

3. EXPLICACIÓN Y RESOLUCIÓN DE EJERCICIOS O PROBLEMAS

**EJERCICIOS**

EJERCICIO NUMERO 1:

![alt text](https://github.com/jlhurtado4/InformeCorreccionExamLab/blob/main/deber%20extra/Ejercicio%201.jpg) 

Primero vemos cuanta corriente pasa por la resistencia de 5 ohm:

![alt text](https://github.com/jlhurtado4/InformeCorreccionExamLab/blob/main/deber%20extra/Ejercicio%201_1.jpg)

Luego calculamos el voltaje de thevenin:

![alt text](https://github.com/jlhurtado4/InformeCorreccionExamLab/blob/main/deber%20extra/Ejercicio%201_2%20VTH.jpg)

Luego calculamos la resistencia de thevenin:

![alt text](https://github.com/jlhurtado4/InformeCorreccionExamLab/blob/main/deber%20extra/Ejercicio%201_3%20RTH.jpg)

Una vez que obtenemos la resistencia de thevenin y el voltaje de thevenin, conectamos la resistencia RL:

![alt text](https://github.com/jlhurtado4/InformeCorreccionExamLab/blob/main/deber%20extra/Ejercicio%201_4%20TH.jpg)

Podemos ver que la cifra esta cerca de la corriente obtenida cuando calculamos con el circuito completo.

EJERCICIO NUMERO 2:

![alt text](https://github.com/jlhurtado4/InformeCorreccionExamLab/blob/main/deber%20extra/Ejercicio%202.jpg)

Primero hacemos_ Cuando E1 = 0 obtenemos:

![alt text](https://github.com/jlhurtado4/InformeCorreccionExamLab/blob/main/deber%20extra/Ejercicio%202_2%20E1_0%20.jpg)

Luego hacemos_ Cuando E2 = 0 obtenemos:

![alt text](https://github.com/jlhurtado4/InformeCorreccionExamLab/blob/main/deber%20extra/Ejercicio%202_3%20E2_0%20.jpg)

Finalmente comprobamos haciendo I_total = I_E1 + I_E2 entonces:

![alt text](https://github.com/jlhurtado4/InformeCorreccionExamLab/blob/main/deber%20extra/Ejercicio%202_1%20.jpg)

EJERCICIO NUMERO 3:

![alt text](https://github.com/jlhurtado4/InformeCorreccionExamLab/blob/main/deber%20extra/Ejercicio%203.jpg)

Primero calculamos el voltaje de thevenin:

![alt text](https://github.com/jlhurtado4/InformeCorreccionExamLab/blob/main/deber%20extra/Ejercicio%203_1%20VTH.jpg)

Luego calculamos la resistencia de thevenin:

![alt text](https://github.com/jlhurtado4/InformeCorreccionExamLab/blob/main/deber%20extra/Ejercicio%203_2%20RTH.jpg)

Por ultimo calculamos thevenin conectando la resistencia RL, y usamos la formula para calcular la potencia la cual es P = I*V

![alt text](https://github.com/jlhurtado4/InformeCorreccionExamLab/blob/main/deber%20extra/Ejercicio%203_3%20TH.jpg)

4. CONCLUSIONES

- Algunos circuitos requieren la instalación de más de una fuente de voltaje o de corriente. Por ejemplo, la mayoría de los amplificadores operan con dos fuentes de voltaje: una fuente de cd y una de ca. Adicionalmente, algunos amplificadores requieren tanto una fuente de voltaje de cd positiva como una negativa para operar apropiadamente. Cuando en un circuito se utilizan múltiples fuentes, el teorema de superposición proporciona un método de análisis.

- El teorema de Thevenin proporciona un método para simplificar un circuito a una forma equivalente estándar. Se utiliza para hacer más sencillo el análisis de circuitos complejos.

-El teorema de transferencia de potencia máxima es importante cuando se tiene que conocer el valor de la carga con la cual la fuente suministra la máxima potencia. El teorema de transferencia de potencia máxima se fórmula como sigue: Para una fuente de voltaje dada, la potencia máxima se transfiere desde una fuente hasta una carga cuando la resistencia de la carga es igual a la resistencia interna de la fuente. La resistencia de la fuente, RS, de un circuito es la resistencia equivalente vista desde la terminal de salida utilizando el teorema de Thevenin.

5. BIBLIOGRAFÍA

Floyd, T. L, (2007). _PRINCIPIOS DE CIRCUITOS ELECTRICOS_. México: PEARSON EDUCACIÓN.

6. RUBRICA

![alt text](https://github.com/jlhurtado4/InformeCorreccionExamLab/blob/main/deber%20extra/RubicasTarea.png)
