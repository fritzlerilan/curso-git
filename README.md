# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline 1
-----------

Underline 2
===========

# Formatos de enfasis
- formato *italica* de la primer forma.
- formato _italica_ de la segunda forma.
- formato **bold o strong** de la primer forma.
- formato __bold o strong__ de la primer forma.
- formato ~~tachado~~, formato normal.
- aqui podemos usar *formato italico*, pero tambien **bold** y ~~tachado~~.

# Listas
1. Esto es un item de lista ordenada.
2. Esto es un item de lista ordenada.
3. Esto es un item de lista ordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.

# Links
- <a href="https://www.google.com/"> Esto es un link HTML</a>
- [Esto es un link en MarkDown](http://www.google.com/)
- [Esto es un link al index](index.html)

# Imagenes
![Logo Git](https://3.bp.blogspot.com/-xhNpNJJyQhk/XIe4GY78RQI/AAAAAAAAItc/ouueFUj2Hqo5dntmnKqEaBJR4KQ4Q2K3ACK4BGAYYCw/s1600/logo%2Bgit%2Bicon.png)

# Code Snippets
Codigo en JSON
```JSON
[
    {
        "title": "apples",
        "count": [12000, 20000],
        "description": {"text": "...", "sensitive": false}
    },
    {
        "title": "Oranges",
        "count": [17500, null],
        "description": {"text": "...", "sensitive": false}
    }
]
```

Codigo en JavaScript
```Javascript
    function ShowArray(){
        var s = CreateArray();
        let x = document.getElementById("p1");
        let str1 = x.innerHTML;
        let str = "<br/>Array Elements: ";
        str += "<br/>" + s;
        str1 += "<br/>" + str;
        x.innerHTML = str1;
    }
```

# Tablas
| Nombre | Apellido | Documento |
|--------|----------|-----------|
| Maxi | Burgos | 12354677      |
| Tomas | Thompson | 12312312   |

# Citas
Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita.

Esto es otro texto que no se relaciona con la cita anterior.
> Esto es otra cita

# Lineas Divisoras
Esto es un texto que sera dividido por guiones medios.

---
Esto es otro texto dividido por asteriscos.

***
Esto es otro texto dividido por guiones bajos.

___
