# UT1-A2 - Introducción a Markdown
## Steven Díaz Torres


### Preguntas:
**1 ¿Qué es Markdown y para que se utiliza?**

Markdown es un lenguaje de marca que fué creado como herramienta como herramienta de conversión de texto plano a HTML, que a su vez se emplea para crear contenido mediante un fácil manejo y que presente un diseño legible.

**2 ¿Cuáles son las características principales de Markdown que lo hacen diferente de otros lenguajes de marcas de presentación?**

La diferencia radica en que el onbjetivo de Markdown consiste en proporcionar una forma de hacer el texto fácil de editar, escribir y editar. Mientras que HTML es un formato más complejo con una gran cantidad de etiquetas que permiten más opciones a la hora de crear un documento.

**3 ¿Qué apliciaciones o plataformas utilizan Markdown?**



**4 ¿Cuáles son las etiquetas o símbolos más comunes que se utilizan en Markdown para dar formato a un texto?**

* **Párrafos:** para generar un nuevo párrafo se debe separar el texto mediante una línea en blanco (pulsando intro dos veces)

    Este texto está escrito en un párrafo aparte.

* **Encabezados:** para generar un texto con encabezado se debera introducir el cáracter almohadilla "#" antes del texto, dependiendo del número de almohadillas hasta un máximo número de 6 el texto tendrá diferenctes grados de encabezado.

    # Encabezado 1
    ## Encabezado 2
    ### Encabezado 3
    #### Encabezado 4
    ##### Encabezado 5
    ###### Encabezado 6

* **Enlaces externos:** para crear un enlace externo se debe índicar el nombre del enlace entre corchetes "[]" y el propio enlace entre paréntesis "()".

    [sintaxis markdown](https://markdown.es/sintaxis-markdown/)

* **Imágenes:** el método a utilizar para insertar una imagen es similar al utilizado para la inserción de enlaces con la diferencia de se debe insterar un símbolo de exclamación "!" al principio.

    ![imagen insertada](https://markdown.es/wp-content/uploads/2015/08/Guia-Markdown-en-espanol.jpg)

* **Texto en negrita:** para poner un texto en negrita se debe escribir el texto entre dos pares de asteriscos `**texto que se quiere en negrita**`.

- **Bloques o líneas de código:** para crear un bloque que contenga código, únicamente es necesario insertar el texto entre dos líneas formadas por tres virguilillas "~". 

    Por otro lado para insertar código en una línea se debe introducir el texto entre dos comillas sencillas "`"
    ~~~
    Texto dentro de un bloque de código
    ~~~
    `Texto en línea de código`.

* **Listas:** las listas pueden ser ordenadas o desordenadas y estas a su vez pueden estar anidadas unas dentro de otras.

    * **Listas ordenanadas:** para generar una lista ordenada se debera empezear la línea con un número con un punto "1."

        1. primer elemento
        2. segundo elemento
        3. tercer elemento
    
    * **Listas desordenadas:** para generar una lista desordenada se debera empezar la línea con un asterisco "*", guión "-" o símbolo de suma "+".

        * primer elemento
        - segundo elemento
        + tercer elemento
    
    * **Anidar listas:** para anidar listas unas dentro de otras, únicamente habrá que añadir cuatro espacios en blanco antes de índicador del lista.

        1. primer elemento
            * Segundo elemento
                - Tercer elemento
    
    * **Tablas:** Para generar una tabla se deberá utilizar la barra vertical "|" para separa celdas y el guión "-" para hacer una línea de encabezado.

    ~~~
    |Columna 1|Columna 2|Columna 3|
    |---------|---------|---------|
    | Fila 1  | Celda 2 | Celda 3 |
    | Fila 2  | Celda 5 | Celda 6 |
    | Fila 3  | Celda 8 | Celda 9 |

    Código de una tabla
    ~~~

    |Columna 1|Columna 2|Columna 3|
    |---------|---------|---------|
    | Fila 1  | Celda 2 | Celda 3 |
    | Fila 2  | Celda 5 | Celda 6 |
    | Fila 3  | Celda 8 | Celda 9 |

    Visualización de la tabla

* **Enlace hacia otro documento:** Para crear un enlace hacia un documento dentro del equipo, la estructura es igual a la empleada en la creación de enlaces externos, pero especificado el documento en su lugar.

    [Documento enlazado](documento-de-enlace.txt)

**5 ¿Cómo se puede visualizar y convertir un archivo escrito en Markdown a otros formatos, como HTML o PDF?**

La forma más sencilla de convertir un archivo en Markdown a otros formatos como HTML o PDF es mediante el uso de conversores en línea, que permiten adjuntar el documento Markdown y descargarlo rápidamente convertido en otros formatos. También se puede utilizar software como Pandoc que permite la conversión a gran variedad de formatos.

**6 ¿Qué ventajas tiene escribir documentación o notas en Markdown frente a usar procesadores de texto como Microsoft Word o Google Docs?**

Markdown presenta varias ventajas frente a otros procesadores de texto como son:

* **Sencillez:** Markdown es un lenguage que se puede aprender muy rápidamente debido a la sencillez de su sintaxis, ya que solo requiere el conocimiento de unos pocos símbolos para la estructuración del texto (#, *, [ ], ( ), etc).

* **Ligereza:** Los archivos Markdown son muy ligeros, haciendolos fácil de compartir y almacenar.

* **Facilidad de conversión:** La sencillez de la sintaxis de Markdown permite que sea muy fácil de convertir a otros formatos como HTML o PDF, mediante conversores online o software de conversión de archivos.

* **Compatibilidad de uso:** La sencillez de Markdown permite que cualquier dispositivo o sistema operativo sea capaz de escribir o visualizar un archivo Markdown sin necesidad de software especializado.

**7 ¿Existen diferentes "sabores" o variaciones de Markdown?**

Las diferentes versiones de Markdown pueden agregar nuevas funcionalidades en función de cual se eliga. Algunas de estas son las siguientes:

* Common Mark
* Editor Markdown
* Ulysses
* GitHub Flavored Markdown
* Discord Markdown

**8 ¿Cómo puede ser útil Markdown en el trabajo colaborativo en projectos de software?**

La cualidades de Markdown hace que su uso en entornos como GitHub esté muy exntendido, debido a que permite a un equipo colaborar fácilmente en la creación de proyectos, la manipulación de la información de forma conjunta, la revisión de cambios y la implementación de los cambios ralizados.