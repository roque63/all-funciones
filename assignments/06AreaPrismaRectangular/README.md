![Tec de Monterrey](../../images/logotecmty.png)
# Área total de un prisma rectangular
Funciones-AreaPrismaRectangular

Modifica el programa que se encuentra en la carpeta `src` que se llama `exercise.py` y que contiene el siguiente código:

```python
def main():
  #escribe tu código abajo de esta línea

if __name__ == '__main__':
    main()
```

La línea `#escribe tu código abajo de esta línea` es un comentario, el programa la va a ignorar al ejecutarse.

Modifica el programa para que haga lo siguiente:

Realiza una **función** que obtenga el área de un rectángulo. La función debe recibir dos parámetros (números decimales) que representan la base y la altura del rectángulo y debe regresar el área calculada (número decimal).

Realiza una segunda **función** que obtenga el área total de un prisma rectangular con base rectangular. El área total de un prisma de este tipo es igual a la suma de las áreas de cada una de sus caras. *Utiliza llamadas a la función anterior para este cálculo*.
    area(base,altura) * 2 + area(altura,profundidad) * 2 + area(base,profundidad) * 2


Manda a llamar a esta última función en el main con datos del usuario. 

Ejemplo de ejecución

```
Dame la base: 21.3
Dame la altura: 10
Dame la profundidad: 2.0
El área total del prisma es: 551.2
```

Una vez que termines tu actividad y la hayas probado con `pytest`, subela a tu repositorio en GitHub, con el proceso de commit + push.

**Nota:** No te preocupes por esta parte del código `if __name__ == '__main__':` por el momento. No la vamos a necesitar para este programa, pero es una buena práctica incluirla y quedará más claro para que sirve en los siguientes ejercicios.

[//]: # (Autor: Gil Huesca - ghjuarez at tec.mx)
