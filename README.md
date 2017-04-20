#Este es un Markdown hecho con latino

La idea es escribir un texto de una forma simple y que el sistema lo transforme en un formato 
adecuado ya sea para la web, pdf u otro.



Requiere
* Latino 0.8.11


Reglas

```
#header 1
##header 2
###header 3
####header 4
#####header 5
######header 6
```



Parrafo: es una linea de texto sin ningun caso 


```
Esto es un parrafo normal
```



```
*italico*
**graso**
--tachado--
__subrayado__
```

Una cita 

```
> Una cita 
```

Listas no numericas
```
Lista sin numeros 
*item1
*item2
*item3
*item4
```

Lista numerica
```
1.item
2.item
3.item
```



Una tabla (dos lineas y dos culumnas
```
| 0:0 | 1:0 |
| -- | -- |
| 0:2 | 1:2 |
```

En la segunda linea hay ```|--|--|``` al interior debe haber dos o mas guiones (no hay limite superior de guines)


Para crear una linea horizonta horizotal, tres guiones
```
---
```



Un enlace

```
url
[mande.ec](http://www.mande.ec)
o basta con poner la direccion del sitio web
http://www.mande.ec

```




Una imagen, se puede poner enn dos opciones: 

```
![Texto alternativo](http://www;mande.ec/imagen.jpg)
```

También o basta con poner la url de la imagen 

```
http://www;mande.ec/imagen.jpg
```


Si se trata de un video suficiente con la direccio del video (youtube), suficiente con poner la direccion 

```
https://www.youtube.com/watch?v=NLPO-0rtD-o&feature=youtu.be
```



##Instrucciones
Escribir tu documentación en ```libro.lat``` (por el momento solo funciona textos de una sola linea

Después ejecuta lo siguiente: 

```
latino crear.lat
```



Y se creara un archivo doc.html 

##Modelos

Puedes editar los ficheros modelos para tener un aspecto diferente para tu documentación

* modelo.css
* modelo_cabeza.html
* modelo_pie.html


