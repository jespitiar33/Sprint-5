# Sprint-5
Sprint 5 Análisis Estadístico de Datos

Instrucciones para completar el proyecto
Se te facilita una plantilla del cuaderno. El cuaderno te orientará sobre qué código escribir y te pedirá que expliques tus resultados a lo largo del proceso. Para completar el proyecto, tienes que rellenar cada celda de código en la plantilla y editar las celdas Markdown donde la plantilla te pide que expliques tus resultados.

Asegúrate también de incluir una introducción que describa brevemente cuáles son tus objetivos y una conclusión que resuma brevemente tus resultados.

Paso 1. Abre el archivo de datos y estudia la información general

A continuación encontrarás las rutas de los archivos que hay que leer, junto con los enlaces para descargarlos si es necesario:

/datasets/megaline_calls.csv Descargar conjunto de datos

/datasets/megaline_internet.csv Descargar conjunto de datos

/datasets/megaline_messages.csv Descargar conjunto de datos

/datasets/megaline_plans.csv Descargar conjunto de datos

/datasets/megaline_users.csv Descargar conjunto de datos

Paso 2. Prepara los datos

Convierte los datos en los tipos necesarios.
Encuentra y elimina errores en los datos. Asegúrate de explicar qué errores encontraste y cómo los eliminaste.
Para cada usuario, busca:

El número de llamadas realizadas y minutos utilizados al mes.
La cantidad de los SMS enviados por mes.
El volumen de datos por mes.
Los ingresos mensuales por cada usuario. Para ello, necesitas:
Restar el límite del paquete gratuito del número total de llamadas, mensajes de texto y datos.
Multiplicar el resultado por el valor de la tarifa de llamadas.
Añadir la cuota mensual en función del plan de llamadas.
Paso 3. Analiza los datos

Describe el comportamiento de la clientela:

Encuentra los minutos, SMS y volumen de datos que requieren los usuarios de cada tarifa por mes.
Calcula la media, la varianza y la desviación estándar.
Traza histogramas. Describe las distribuciones.
Paso 4. Prueba las hipótesis

El ingreso promedio de los usuarios de las tarifas Ultimate y Surf difiere.
El ingreso promedio de los usuarios en el área de estados Nueva York-Nueva Jersey es diferente al de los usuarios de otras regiones.
Tú decides qué valor alfa usar. Además, tienes que explicar:

Cómo formulaste las hipótesis nula y alternativa.
Qué criterio utilizaste para probar las hipótesis y por qué.
Paso 5. Escribe una conclusión general

Formato. Completa todas las tareas en un Jupyter Notebook. Almacena todo el código en las celdas code y las explicaciones de texto en las celdas markdown. Añade títulos y el formato adecuado si es necesario.

¿Cómo será evaluado mi proyecto?
Hemos recopilado los criterios de evaluación del proyecto. Léelos atentamente antes de empezar a trabajar.

Esto es lo que buscan los revisores de proyecto cuando evalúan tu proyecto:

Cómo explicas los problemas identificados en los datos.
Cómo preparas los datos para el análisis.
Qué gráficos trazas para las distribuciones.
Cómo interpretas los gráficos resultantes.
Cómo calculas la desviación estándar y la varianza.
Si formulas las hipótesis nula y alternativa.
Qué métodos utilizas para probar tus hipótesis.
Si interpretas los resultados de tus pruebas de hipótesis.
Si sigues la estructura del proyecto y mantienes el código ordenado.
Las conclusiones a las que llegas.
Si dejas comentarios en cada paso.
