# Proyecto Colaborativo: Guía de Buenas Prácticas

## Organización del Proyecto

¡Holitaaa gente! ☀️☀️

En un proyecto colaborativo, la organización es clave para garantizar la eficiencia y la calidad del código. Aquí hay algunas recomendaciones para mantener el proyecto en orden:

1. **Explicación Detallada de Commits**: Cada commit debe ir acompañado de una explicación clara y detallada de los cambios realizados. Esto ayuda a que todos los miembros del equipo comprendan el progreso del proyecto y facilita la colaboración.

2. **Branches Específicos para Funcionalidades**: Utiliza branches separados para cada funcionalidad o sección del proyecto. Esto permite trabajar en paralelo sin interferir en el trabajo de otros y facilita la revisión del código.

3. **Pull Requests y Revisión de Código**: Antes de fusionar un branch con la rama principal (main), asegúrate de realizar un pull request y someter el código a revisión por parte de otros miembros del equipo. Esto ayuda a identificar posibles errores y a mantener la calidad del código.


## Organización del código

El CSS es una parte fundamental de cualquier proyecto web. Aquí te dejamos algunas recomendaciones para mantener el código CSS ordenado y fácil de mantener:

1. **Estructura Lógica y Ordenada**: Mantén una estructura coherente y organizada en tus archivos CSS. Esto facilita la navegación y la comprensión del código para ti y para otros desarrolladores.

2. **Comentarios Descriptivos**: Utiliza comentarios para explicar secciones de código que puedan resultar confusas o complejas. Esto ayuda a que otros miembros del equipo comprendan tu razonamiento y facilita futuras modificaciones.

3. **Limita el Alcance del CSS**: Evita afectar áreas del proyecto que no están relacionadas con la funcionalidad que estás desarrollando. Mantén tus estilos CSS específicos y enfocados en el contenido de tu branch.

4. **Reutiliza Código y Mantén la Consistencia**: Revisa el código de otros branches para evitar la repetición de estilos o valores similares. Mantener una estructura consistente en todo el proyecto facilita la mantenibilidad a largo plazo.

5. **Contextualiza y Organiza Selectores**: Proporciona contexto y organiza tus selectores CSS por jerarquía. Esto ayuda a comprender cómo se aplican los estilos y a mantener una estructura clara en todo el proyecto.

Un ejemplo:

```CSS
nav .container li{
    /*de esta manera se ve que estas atacando a un li que está dentro de un container en el nav*/
}

/*Si luego vas a seguir atacando solo los elementos de ese container no hace falta volver
a poner el nav si el nombre de la clase no se repite, en el caso de que se repita, añadir otra vez nav*/

.container .decoracion{
    /*código*/
}

/*Cuanto más específico sea mejor para que el resto entienda qué es lo que estas haciendo*/
```
6. **Seguir un órden lógico en cuanto a propiedades**. Recordando la metodología de cajas, podemos utilizar las propiedades siguiendo un órden, por ejemplo:

```CSS
nav ul{
    /*position, display y elementos de los displays*/
    display: flex;
    justify-content: center;
    /*tamaños*/
    width: fit-content;
    height:auto;
    /*margenes, bordes, paddings...*/
    margin: 100px auto;
    padding: 20px 10%;
    /*fuentes*/
    font-family: Comic Sans, sans-serif;
    font-size: 2em;
    color: red;
    /* Otros como background, opacidades, colores, filtros ...*
}
```

No teneis que seguir esta receta, solo que tengais la vuestra propia y que la repitais en vuestro desarrollo para crear consistencia.

--------


**Esto son recomendaciones y no hace falta que seais super estrictos y seguirlas a rajatabla** que estamos para aprender. Pero cuanto más tiempo nos esforcemos en escribir mejor código, más legible y escalable mejor para nuestra carrera y para nuestra salud mental.


Nota: recordad que la aplicación está desplegada en Vercel para que la podais consultar cuando querais. Este es el enlace que además encontrareis en el sidebar de la derecha de la repo, debajo del About.
https://colaboracion-web.vercel.app/

¡Manos a la obra!
