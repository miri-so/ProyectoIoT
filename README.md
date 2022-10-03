# ProjectsIoT2022

## Integrantes
- Miriam Chávez Soto

## Objetivo general
Hoy en día es normal tratar a nuestra mascota como parte de la familia y por ello su comodidad es primordial. Es por ello que mi proyecto consiste en crear un comedor automatizado para mi Mascota, el cual tendrá un diseño diferente a los que existen y por lo tanto su mecanismo será distinto a esos. Esto pensando en la comodidad del usuario y sobre todo de su mascota. El diseño se basa en las necesidades del perrito, es decir tendrá la altura adecuada para que la alimentación del cachorro sea correcta ya que investigaciones afirman que es dañino que el perrito coma al nivel del suelo.
Un comedor automatizado es excelente ya que el dueño debe trabajar, salir de casa y para no preocuparse por la alimentación del cachorro se programa la hora y porción de comida desde una aplicación. Así mismo el bebedero tiene un filtro de movimiento para mantener el agua limpia y fresca. Finalmente, el diseño del prototipo es ideal para la decoración del hogar, ya que a simple vista no se ven los contenedores de agua y croquetas haciendo mas atractiva la vista en casas de lujo.

### Objetivos específicos
- Cuidar el bienestar de nuestra mascota con un comedor automatizado.
- Un diseño diferente al del mercado convencional, basado en     investigaciones caninas.
- Horas y porciones programas.
- Agua a temperatura ambiental y limpia.
- Todo se controla desde una app.


## Tabla de Software utilizado
| Id | Software | Version | Tipo |
|----|----------|---------|------|
|  1 | Fritzing | 0.9.10  |Escritorio     |
|  2 | Wokwi    | N/A     |Online|
|  3 |Android St|Chipmunk | 2021.2.1|      |

## Tabla con el hardware utilizado
| Id | Componente | Descripción | Imagen | Cantidad | Costo total |
|----|------------|-------------|--------|----------|-------------|
|  1 |   Esp32    |  El ESP32 es un procesador del fabricante chino Espressif que viene con unas especificaciones espectaculares: Procesador dual core Xtensa® LX6 de 32 bits. Es compatible Arduino con el pluggin adecuado (Enseguida vamos) Velocidad de reloj : Entre 160 Mhz y 240 Mhz|  ![esp32](https://user-images.githubusercontent.com/87047021/193485410-ffd5efe8-f976-4ef3-8f46-bf2dc1cc241d.png)|    1      |    165         |
|  2 |  Servomotor     |Un servomotor es un actuador rotativo o motor que permite un control preciso en términos de posición angular, aceleración y velocidad, capacidades que un motor normal no tiene. En definitiva, utiliza un motor normal y lo combina con un sensor para la retroalimentación de posición.        |  ![servo](https://user-images.githubusercontent.com/87047021/193485507-a4616527-6f7e-4304-b480-f289c51ad3cf.jpg)|  1        |     85        |
|  3 |  Sensor ultrasonico    | Como su nombre lo indica, los sensores ultrasónicos miden la distancia mediante el uso de ondas ultrasónicas. El cabezal emite una onda ultrasónica y recibe la onda reflejada que retorna desde el objeto. Los sensores ultrasónicos miden la distancia al objeto contando el tiempo entre la emisión y la recepción. |  ![sensor ultrasonico](https://user-images.githubusercontent.com/87047021/193485636-3154293e-d7bb-45c9-a275-a11ff5014a53.jpg)|     1     |      90       |
|  4 | Protoboard    | Una protoboard, o breadboard, es prácticamente una PCB temporal con una forma y tamaño generalizados. Utilizada comúnmente para pruebas y prototipos temporales de circuitos. Se usa insertando las terminales de los dispositivos electrónicos en los orificios de la protoboard de la forma en que tengan continuidad.  |   ![protoboard](https://user-images.githubusercontent.com/87047021/193485981-f3c3a68a-e0ff-4c5b-a6d7-223f22b82048.jpg)|     2     |     169        |
|  5 | LCD     |  Una pantalla de cristal líquido o LCD es una pantalla delgada y plana formada por un número de píxeles en color o monocromos colocados delante de una fuente de luz o reflectora.|  ![lcd](https://user-images.githubusercontent.com/87047021/193486150-cd7db1cb-b4c9-42ca-96e9-fd6bd81ac9d1.jpg)|  1     |   100      |
|  6 | Sensor de temperatura    | Los sensores temperatura son dispositivos utilizados en aplicaciones de edificación para medir la temperatura de un fluido, normalmente aire o agua. Habitualmente, se los conoce también por el nombre de sondas de temperatura.  | ![sensor temperatura](https://user-images.githubusercontent.com/87047021/193485898-c6ccf37d-dbe8-48a5-a42f-1a5fb58f3b45.jpg) |    1      |       70      |
|  7 |  resistencias     | La resistencia o resistor es un componente ubicado en prácticamente todos los circuitos eléctricos. Su misión es alterar o modificar el paso de la corriente y en otros casos para generar calor. |  ![resistencias](https://user-images.githubusercontent.com/87047021/193486274-9c4c857f-9555-45f1-b625-e312095dd0d8.jpg) |     varias     |   Indefinido|
      
## Epicas del proyecto 
- Hacer mas facil la resposabilidad de alimentar a nuestra mascota.
- Automatizar y cuidar el bienestar del perrito
- implementar IoT en el hogar.
- Considerar las funciones de la Esp32 para el proyecto.

## Tabla de historias de usuario
| Id | Historia de usuario | Prioridad | Estimación | Como probarlo | Responsable |
|----|---------------------|-----------|------------|---------------|-------------|
|  1 |  Definir el mejor entorno para simular el circuito            |  alta         | 2 d        | verificando que existan todos los componentes en el simulador.          |     Miriam        |
|  2 | Armar el circuito en el simulador seleccionado                   | media          | 3 d           |  realizando capturas del simulador, para evidencia.             |  Miriam           |
|  3 |  Realizar pruebas de programacion en el simulador                   |    media       |    3 d        |  Guardar pruebas , evidencia.             |       Miriam      |
|  4 |   Buscar material para el diseño del prototipo        |  baja         | 2 s        | investigando la resistencia y facilidad de adquirir el material   |     Miriam        |
|  5 |  Conseguir los componentes del hardware         |  media        | 2 s        | tomando fotos de los componentes ibtenidos para evidencia.  |     Miriam        |



## Prototipo en dibujo

![WhatsApp Image 2022-10-02 at 5 03 29 PM](https://user-images.githubusercontent.com/87047021/193478583-85b766da-0573-4d4c-b45c-6e306c593664.jpeg)



