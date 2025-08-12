# Sistemas de audio y accesorios


## Objetivos

- Comprender los fundamentos de la electrónica de potencia aplicados a propulsión eléctrica y audio.
- Fortalecer capacidades de instrumentación electrónica realizando ensayos de laboratorio.
- Fortalecer la autonomía del alumno en la resolución de problemas y desarrollo de prototipos electrónicos.

La idea es darles fundamentos de electrónica de potencia, señales analógicas y
digitales con un enfoque a temas que fortalezcan las bases sobre propulsión
eléctrica. Así mismo no debemos perder el objetivo original de la materia, y dar
temas sobre principios de transmisión acústica, diseño de cajones y demás temas
pertinentes.

Gran parte entre inversores/drivers de motores es análoga a la de un
amplificador de clase D, por lo que los temas a tratar como filtros, fuentes
de conmutación y semiconductores de potencia pueden tratarse en más profundidad.

## Temas a tratar

* Señales
  * Clasificación: Digital y analógica (variable continua y discreta)
  * Modulación
    * Digital -> Analógica y demás tipos
    * Modulaciones más conocidas
      * PWM
        * Utilización en amplificadores de potencia
      * FM
      * AM
* Medios de transmisión
  * Medio electromagéntico
  * Medio acústico (ondas de presión)
  * Atenuación, reflexión, distintos efectos y distorsiones
  * El decibel
  * Caracterización de un filtro, respuesta en frecuencia
  * Filtros eléctricos, filtros acústicos
* Amplificadores de audio
  * Tipos de amplificadores
  * Electrónica de potencia
    * Semiconductores de potencia
    * Modo conmutación vs modo lineal
* Drivers de motores
  * Sus similitudes con los amplificadores tipo D

### Completar

Agregar temas a tratar con respecto a sistemas de audio convencionales en
automóviles, topologías comunes.

Detallar la sección "Amplificadores de audio"

## Actividades prácticas

Propuestas:

* Puente H genérico, puede usarse para comandar motores tanto como altavoces
  * Debe tenerse en cuenta la frecuencia de conmutación, los drivers integrados
    para motores suelen usar frecuencias de conmutación cercanas al rango
    audible
* Amplificador integrado de clase D
  * Barato
  * Tener en cuenta que el motor a utilizar debe responder bien en la banda
    de frecuencia del amplificador, y poseer una impedancia similar a la de
    los altavoces recomendados, el frenado puede causar sobretensiones.
* Fuentes de PC
  * Abundantes
  * Tienen varios dispositivos de potencia y aplican principios como disipación
    de calor y diseño para altas corrientes/tensiones.
  * Si son flyback probablemente no sean tan análogas en la topología, pero si
    son con un medio puente H se podrían hacer analogías.

## Cronograma

### 08/11

Introducción a la materia, diagnóstico.

## Bibliografía

* Sistemas de Seguridad y Confortabilidad - macmillan education - 2016 (
  cap 1 https://www.macmillaneducation.es/wp-content/uploads/2018/09/sistema_seguridad_libroalumno_unidad1muestra.pdf)
* TODO: Alguno de los libros de electrónica de potencia
