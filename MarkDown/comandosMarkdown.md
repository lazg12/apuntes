# GUÍA MARKDOWN

## ENCABEZADOS
### Tipos de encabezados
>El tamaño de los encabezados depende de la cantidad de almohadillas que se utilicen #.
# Encabezado 1
## Encabezado 2
### Encabezado 3
#### Encabezado 4
##### Encabezado 5
###### Encabezado 6

### Encabezados subrayados
>Se utiliza para el encabezado grande el símbolo =.  

Encabezado 1
=
>Se utiliza para el encabezado pequeño el símbolo -.  

Encabezado 2
-

## CITAS
### Cita única
>Esto es una cita. Yo.  

### Citas continuas
> Esto es una cita.  
> Esto es otra cita

### Citas anidadas
> Esto sería el inicio de una cita.
> 
>> Dentro de ella puedes anidar otra cita.
>>> Anidando otra cita
> 
> La cita principal llegaría hasta aquí. 

## LISTAS
### Listas desordenadas.
- Elemento 1.
    - Elemento 1.1
    - Elemento 1.2
* Elemento 2.
    - Elemento 2.1
+ Elemento 3.
> Se recomiendo utilizar el guion ya que el símbolo de multiplicación y más se lo utiliza en ciertas aplicaciones.

### Listas numeradas
1. Elemento 1.
    - Elemento 1.1
        - Elemento 1.1.1
2. Elemento 2.
    * Elemento 2.1
3. Elemento 3.

## SEPARACIONES 
### Separaciones entre secciones de texto.
Sección de texto 1
___
___
___
Sección de texto 2
___
___
Sección de texto 3
___
Sección de texto 4

## NEGRITAS Y CURSIVAS
> Para utilizar negritas o cursivas se recomienda utilizar asteriscos, ya que también se puede utilizar subguión.  

*Párrafo en cursiva*  
**Párrafo en negrita**  
***Párrafo en negrita cursiva***

## ENLACES
>Enlace con nombre.  
[Enlace](https://markdown.es/)  

>Enlace con nombre y título.  
[Enlace](https://markdown.es/ "Título del enlace")  

>Enlace solo.  
<https://markdown.es>  


## IMÁGENES
>Imagen desde una url de internet.  
![Símbolo de código](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRl-knzdPDg5BW21hJ0-h2b0wmmavScHY0EIYpiVYjSPw&s)

>Imagen 1 desde una url si está en la misma carpeta.  
![Sim](./img/simboloDeCodigo.png "Símbolo de código")  

>Imagen 2 desde una url si está en la misma carpeta.  
![Símbolo de código](img/simboloDeCodigo02.png)

>Links a imágenes.    
![Simbolo04](img.png)  

## CÓDIGO
>Para Escribir una línea de código se debe iniciar con 4 espacios en blanco.  

    Esto es un código.

>Para escribir varias línea de código se debe poner entre 3 virgulillas. 
~~~
Esto es un código
en varias líneas. 
~~~

>Para resaltar palabras se debe poner entre 2 acentos graves y así también utilizarlo como muestra de código.  

Voy a resaltar la siguiente frase:  `HOLA MUNDO.`. 

## ANULAR SÍMBOLOS DE MARKDOWN
>Para anular símbolos se utiliza la barra invertida \\

## LÍNEAS
>Para crear línea se utilizan preferiblemente 3 asteriscos, pero también pueden ser 3 guiones o subguión.

***
---
___

## TABLAS

| Primera columna | Segunda columna | Tercera columna |
| -- | -- | -- |
| dato 1 | dato 2 | dato 3|

### REFERENCIAS

>Para la referencia cruzada separar las líneas dando 2 enter.  


[img01]: img/simboloDeCodigo02.png "Imagen codigo02"
[img02]: img/simboloDeCodigo.png "Imagen codigo"

Hola este es [link][img01] para abrir la imagen 02 de referencia cruzada.


>Abre directamente el archivo en una nueva ventana.

[Abrir imagen](img/simboloDeCodigo02.png "Abre una nueva ventana para mostrar la imagen.")  


>Insertar imágenes utilice la etiqueta con el signo de !  

Aquí estoy insertando la imagen ![img02], separando el texto  e inserto esta otra imagen ![img01], y también por medio del link [imagen 01][img01] o también [imagen 02][img02], también están los link automáticos <https://www.google.com/>.

 











































































