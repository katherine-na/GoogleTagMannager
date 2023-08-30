<h1 align="center">Google Analytics 4</h1>

## ¿Qué es Google Tag Mannager?
Google Tag Manager es una plataforma que permite gestionar y desplegar etiquetas de seguimiento en un sitio web sin necesidad de modificar el código fuente de manera directa. Estás etiquetas son frágmentos de código que se utilizan para recopilar datos sobre la interacción de los usuarios con el sitio web y para enviar esa información a diversas herramientas de análisis.

### Ventajas de GTM:

- Facilita la gestión y organización de etiquetas sin necesidad de modificar el código del sitio constantemente.
- Permite implementar y modificar etiquetas de manera rápida, lo que agiliza los procesos de seguimiento.
- Proporciona un entorno de prueba para asegurarse de que las etiquetas funcionen correctamente antes de implementarlas en el sitio en vivo.
- Reduce la dependencia de los equipos de desarrollo para realizar cambios en las etiquetas de seguimiento.

## ¿Qué es Google Analytics?
Google Analytics es una plataforma de análisis que permite recopilar, medir y analizar datos sobre el comportamiento de los usuarios en un sitio web.
GA4 está orientado a medir sitios web, aplicaciones moviles y juegos para movil

En GA4 todo son eventos (hits) que llevan asociada información (parametros) que son los que definen y ayudan a construir conceptos como Usuario, sesión, etc.

## Qué son los Eventos(hits)
Los hits son eventos discretos que representan acciones específicas que los usuarios realizan en un sitio web. Cada vez que un usuario interactúa con el sitio, se genera un hit que contiene información sobre esa interacción.

Cada tipo de hit recopila datos específicos sobre la interacción de los usuarios con el sitio, y estos datos se envían a Google Analytics para su análisis. 

## Etiquetas, variables y activadores
Con GTM lanzamos etiquetas en los momentos adecuados (activadores) con la información adecuada capturada de forma dinamica (variables)
## Variables
En GTM las variables contienen valores. Estos valores pueden ser rellenados de forma dinamica.

¿Cómo se utilizan las variables?  
Se pueden utilizar en activadores o etiquetas. En el caso de los activadores las podemos utilizar para filtrar cuando debe activarse una etiqueta concreta.  
```
ej. "Para accionar un activador de página vista cuando la variable URL sea https://example.com"
```

En el caso de las etiquetas las podemos utilizar para capturar valores como el de una transacción y los productos comprados y enviar estos datos.

Existen dos tipos de variables  
### Variables Integradas
Tenemos disponibles una serie de variables que vienen "por defecto". La diferencia aquí es que si queremos utilizarlas tendremos que activarlas
### Variables definidas por el usuario
Podemos crear varibales para guardar datos, en GTM existen tipos de variables, por ejemplo de navegación, variables de la página, elementos de página, etc

## Etiquetas
Las etiquetas son los frágmentos de código que utiliza herramientas como Google Analytics, Google Ads, pixeles y otras. Para muchas de ellas GTM ofrece etiquetas integradas que facilicitan mucho la tarea o etiquetas personalizadas utilizando HTML

## Activadores
Se encargan de tomar la desición de activar una etiqueta o no.  
Toda etiqueta debe tener un activador para poder funcionar. Sin activador una etiqueta no sirve de nada, no hace nada.

### Diferencia entre GTM y GA4
Diferencias clave entre GTM y GA:

- Función principal: GTM se centra en la gestión y el despliegue de etiquetas de seguimiento en el sitio web. GA se enfoca en recopilar y analizar datos sobre el comportamiento de los usuarios en el sitio.
- Uso de código: GTM no requiere modificar directamente el código del sitio web para implementar etiquetas, mientras que GA generalmente requiere la inserción de un fragmento de código en cada página que se desea rastrear.
- Capacidad de análisis: GTM no realiza análisis por sí mismo; su función es administrar las etiquetas. GA proporciona herramientas y paneles de control para el análisis detallado de los datos recopilados.
- Roles en el proceso: GTM es una herramienta de implementación, mientras que GA es una herramienta de análisis. Ambas trabajan juntas para recopilar datos y luego analizarlos.
- Usuarios objetivos: Los equipos de marketing y rastreo suelen utilizar GTM para implementar etiquetas, mientras que los analistas y especialistas en marketing utilizan GA para extraer información valiosa de los datos recopilados.
