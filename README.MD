# Version del curso
Version actual: v1.2.2

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

- Formato *italica* de la primera forma.
- Formato _italica_ de la segunda forma.
- Formato **bold o strong** de la primera forma.
- Formato __bold o strong__ de la segunda forma.
- Formato ~~tachado~~.
- Aquí podemos usar *formato italico*, pero también **bold** y ~~tachado~~.

# Listas
1. Esto es un  item de lista ordenada
2. Esto es un  item de lista ordenada
3. Esto es un  item de lista ordenada
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada

# Links
- <a href="http://www.google.com">Esto es un link html</a>
- [Esto es un link en Markdown](http://www.google.com)
- [Esto es un link al index](index.html)

# Imagenes
![Logo Github](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

# Code Snipets
Codigo en JSON
```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```
Codigo en Javascript
```Javascript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```

# Tablas
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Richi  | Calvo    | 16642     |
| Juan   | Juancho  | 14542     |

# Citas
Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita.

Esto es otro texto que no se relaciona con  la cita anterior:
> Esto es otra cita.

# Lineas Divisoras
Es un texto que sera dividido por guiones.

---

Esto es otro texto dividido por asteriscos.

***

Esto es otro texto dividido por guiones bajos.

___

# Saltos de linea
Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.

Esto es nuestro tercer parrafo.

- Lista


