# PI_Henry_Urteaga
<h1 align="center"> Proyecto Individual Nº 2  </h1>
<h3 align="center"> Siniestros Viales </h3>
<h3 align="center"> Autor: Bioing. Facundo Urteaga  </h3>

<p align="left">
   <img src="https://img.shields.io/badge/ESTADO-EN%20DESAROLLO-green">
   </p>

## Índice

*[Descripción del proyecto](#descripción-del-proyecto)

*[Rol del Analista de Datos](#rol-del-analista-de-datos)

*[Exploratory Data Analysis](#exploratory-data-analysis)

*[Dashboard: Introducción](#dashboard:-introducción)

*[Dashboard: KPIs](#dashboard:-kpis)

*[Conclusiones Finales](#conclusiones-finales)

## Descripción del proyecto

<p align="justify">
Los siniestros viales, que incluyen colisiones entre vehículos, atropellos y choques con objetos fijos, son una preocupación importante en ciudades con alto volumen de tráfico y densidad poblacional, como Buenos Aires. Estos accidentes pueden causar desde daños materiales hasta lesiones graves o fatales, afectando significativamente la seguridad de los residentes y la infraestructura vial. Las tasas de mortalidad por siniestros viales, calculadas como el número de muertes por habitantes o vehículos registrados, son un indicador crucial de la seguridad vial. Reducir estas tasas es esencial para proteger vidas, y esto requiere la implementación de medidas preventivas como educación vial, cumplimiento de normas de tráfico, mejoras en la infraestructura y promoción de vehículos seguros.

En Argentina, los siniestros viales son la principal causa de muertes violentas, con cerca de 4.000 muertes anuales. Entre 2018 y 2022, se registraron 19.630 muertes en el país, lo que equivale a 11 personas fallecidas por día. En 2022, hubo 3.828 muertes fatales por accidentes de tránsito, y la probabilidad de morir en un siniestro vial es significativamente mayor que en un acto de inseguridad delictiva. En respuesta a esta problemática, el Observatorio de Movilidad y Seguridad Vial (OMSV) de Buenos Aires ha solicitado la elaboración de un proyecto de análisis de datos para ayudar a las autoridades locales a tomar medidas para reducir las víctimas fatales de los siniestros viales. Para este propósito, se ha proporcionado un dataset sobre homicidios en siniestros viales en Buenos Aires entre 2016 y 2021, que incluye información detallada en formato xlsx con hojas de datos y diccionarios.
</p>

## Rol del Analista de Datos

</p>
Desde el año 2017 formo parte del equipo de trabajo del OMSV de la Ciudad Autónoma de Buenos Aires como Data Analytics. Ya pasaron 4 años, elecciones de por medio y ganó un partido político distinto al que nos designo en su momento para este trabajo. Si bien no son las mejores noticias, las nuevas autoridades nos dieron la posibilidad de defender el trabajo hecho hasta ahora y, en caso de mostrar resultados satisfactorios, tenemos la oportunidad de seguir en el cargo con estas nuevas autoridades. Para esto, debemos demostrar que producto de nuestro monitoreo y medidas tomada a lo largo de estos años, la Ciudad Autónoma de Buenos Aires se encuentra significativamente mejor en relación a víctimas fatales en siniestros viales.
</p>

## Exploratory Data Analysis

</p>
Herramientas utilizadas: Lenguaje Python en IDE Microsoft Visual Studio Code
Con los datos recolectados durante estos años de siniestros que involucran homicidios, se realizó un análisis exploratorio de los datos. Inicialmente se realizó un control de la existencia de datos nulos y outliers o información incompleta en las columnas. No se detectaron outliers, pero se detectaron datos faltantes bajo la codificaciòn "SD" lo cual facilitó el procesamiento.
La segunda parte consistió en explorar por primera vez los datos en búsqueda de patrones que puedan facilitar posteriormente las conclusiones, la creación de nuevos KPIs y a su vez detectar variables que no muestran ningun tipo de variación o comportamiento para no perder tiempo luego. De esta etapa se destaca que se encontraron comportamientos interesantes en el la distribución de los hechos por tipo de calle (Figura 1), y cantidad de hechos por franja horaria (Figura 2).
En una tercera parte, se procesaron las columnas de "cruce" y "altura" y se sintetizaron en una sola variable que categorizaba si el siniestro ocurrió en una esquina, en la cuadra o directamente en una autopista (Figura 3).
</p>

<p align="center">
   <img src="Imagenes/1_dens_2_weeks.jpg" width="400">
</p>
<p align="center">
   <em>Figura 1: Distribución de tiempo jugado las últimas dos semanas por usuario </em>
</p>

<p align="center">
   <img src="Imagenes/2_dens_op_pos.jpg" width="400">
</p>
<p align="center">
   <em>Figura 2: Densidad de opiniones positivas totales (de 0 a 100 %) </em>
</p>

## Dashboard: Introducción

</p>
Herramientas utilizadas: POWER BI DESKTOP
La introducción del dashboard corresponde a la primera página "INTRO" del proyecto de POWER BI (Figura 4). El propósito de este primer lienzo, es interiorizar al espectador con el contexto inicial en el cual nos encontramos al tomar posesión del cargo en el año 2017, y los aspectos relevantes que osbervamos como "Puntos clave" a tener en cuenta en las políticas de seguridad vial en los años próximos para mitigar los problemas que detectamos.

PUNTOS CLAVES:

* Alto número de víctimas viales totales
* Accidentes en motocicleta significativos
* La COMUNA 1 es la que tiene la mayor tasa de homicidios
* COMUNA 1: Franja Horaria de madrugada con gran tasa de homicidios
* COMUNA 1: Homicidios viales preponderantemente de PEATONES
* La mayor cantidad de homicidios ocurre en las ESQUINAS de calles y avenidas

ACCIONES DE MITIGACIÓN:

* Mejorar los cursos de educación vial al momento de solicitar o renovar el carnet
* Mayores controles a motociclistas y aumento de penalización por el NO uso de CASCO
* En la COMUNA 1 mayor cantidad de controles de alcoholemia en las horas claves de la madrugada
* En Discotecas de la COMUNA 1 aumento de campañas y estrategias para la promoción de "conductores designados"
* Para la reducción de PEATONES circulando durante la madrugada se establecieron precios promocionales subsidiados de servicios de TAXIS durante horas clave
* Mejora de la señalización en esquinas y se agregaron lomos de burro estratégicos

</p>

<p align="center">
   <img src="Imagenes/3_violin_precios.jpg" width="400">
</p>
<p align="center">
   <em>Figura 3: Violin Plot de precio de venta de los juegos por año de lanzamiento </em>
</p>

<p align="center">
   <img src="Imagenes/4_cantidad_juegos.jpg" width="400">
</p>
<p align="center">
   <em>Figura 4: Cantidad de juegos lanzados a la plataforma por año </em>
</p>

<p align="center">
   <img src="Imagenes/6_proporcion_tag.jpg" width="400">
</p>
<p align="center">
   <em>Figura 5: Proporciones de tags </em>
</p>

<p align="center">
   <img src="Imagenes/7_proporcion_spec.jpg" width="400">
</p>
<p align="center">
   <em>Figura 6: Proporciones de specs </em>
</p>

<p align="center">
   <img src="Imagenes/8_proporcion_genres.jpg" width="400">
</p>
<p align="center">
   <em>Figura 7: Proporciones de genres </em>
</p>

## Dashboard: KPIs

</p>
Herramientas utilizadas: POWER BI DESKTOP
Los KPIs se detallaron en los lienzos "KPIs 1" (Figura x) y "KPIs 2" (Figura x). A continuación se detalla cada uno de los 4 KPIs diseñados.

KPI 1:  Reducción de un 10% de la tasa de homicidios respecto al semestre anterior
</p>

<p align="center">
   <img src="Imagenes/9_nube_palabras.jpg" width="400">
</p>
<p align="center">
   <em>Figura 9: Nube de palabras </em>
</p>

<p align="center">
   <img src="Imagenes/10_barras_sa.jpg" width="400">
</p>
<p align="center">
   <em>Figura 10: Comparación entre reseñas y análisis de sentimiento </em>
</p>

## 5 Sistema de Recomendación

</p>
Se realiza un sistema de recomendación basado en Videojuego. El algoritmo recibe un videojuego y recomienda otros cinco de similares características. Se desarrolló un modelo basado en el algoritmo K Vecinos mas Cercanos y utilizando como métrica la similitud del coseno. Se detallan a continuación las distintas versiones del modelo con sus características y modificaciones respecto a las versiones previas. El desempeño de los modelos se evaluó a partir de una selección de videojuegos clásicos y variados en cuanto a género, época y características. Se utiliza como modelo final la cuarta versión (V4) (Figura 11).

<p align="center">
   <img src="Imagenes/11_sist_reco.JPG" width="400">
</p>
<p align="center">
   <em>Figura 11: Sistema de Recomendación. Versiones </em>
</p>

* V1: Modelo inicial. Se utilizan las etiquetas de "genres", "tags" y "specs" como variables dummies (1 presencia, 0 ausencia) y se entrena el modelo. El desempeño de este modelo es regular
* V2: Segunda Versión. Se eliminan algunas etiquetas, principalmente de "tags" y "specs" que, a criterio del científico de datos, no aportan información y pueden generar confusión al momento de clasificar. Esto se debe a que son etiquetas extrañas y que no suelen discriminar la preferencia o no de un Usuario al momento de elegir un videojuego. Además se pondera genres*2 debido a que las etiquetas en general son pocas pero mas concretas en relación al estilo del videojuego. Ocurre lo contrario con tags que es penalizado en un factor de 0.5 debido a la cantidad de etiquetas que poseen en general los videojuegos, y además, por un estudio mas metódico, se descubre que estas etiquetas son definidas por usuarios y en muchos casos no corresponden a las carecterísticas del videojuego. Un ejemplo sencillo es el juego de fútbol PES 2018 que posee la etiqueta de "Gore" y "Heist". El desempeño de este modelo es aceptable
* V3: Tercera Versión. Se elimina el contenido descargable, DLCs y expansiones, ya que en general no deseamos que se recomiende ese tipo de producto. Además, se agrega como variable la fecha de lanzamiento (agrupada en lustros) ya que en general los usuarios suelen desear conocer videojuegos de una misma época. De todas maneras esto no es exclusivo, por lo que se agrega como una variable mas que afecte moderadamente al sistema de recomendación. El desempeño de este modelo es muy bueno
* V4: Cuarta Versión. Al observar que en general los videojuegos tienen pocas etiquetas "genres" y muchas etiquetas "specs" y "tags", entendiendo que las etiquetas "genres" son las mas valiosas y representativas del videojuego y, por último, sabiendo que al valer todas las etiquetas lo mismo, la influencia de pocas etiquetas "genres" se vería diluída por muchas etiquetas "specs" o "tags" se procede a penalizar la influencia de estas últimas a partir de dividir cada etiqueta por el total de etiquetas en su categoría. Entonces, por ejemplo, si el videojuego posee 10 etiquetas "tags", cada una pasaría a valer 1/10 o 0.1 en lugar de 1. El desempeño de este modelo es excelente.
</p>

### Desempeño del modelo

Indices de prueba. Juegos de diferentes características (Los simbolos ++ o -- indican un cambio positivo o negativo respecto al desempeño del modelo anterior)

------- JUEGO ---------|---id---|-------Desempeño--------
-----------------------|--------|------------------------
Counter Strike         |     10 | muy bien
PES 2018               | 592580 | muy bien ++
AGE III                | 105450 | muy bien
Simcity 4              |  24780 | muy bien
Tennis Elbow 2013      | 346470 | regular (falta que recomiende otros juegos de tennis)
Civilization IV        |  16810 | excelente
Darksiders             |  50620 | excelente
Fallout NV             |  22380 | muy bien ++ (pueden faltar juegos de la franquicia)
Dragon Age Origins     |  47810 | excelente
Star Wars Jedi Knight  |   6020 | excelente ++
NFS Shift              |  24870 | excelente ++
Final DOOM             |   2290 | excelente
Earthworm Jim          | 901147 | muy bien   


## 6 Funciones y deploying

</p>
Se realizan una serie de funciones de búsqueda de estadísticas relevantes de la base de datos, detalladas en el archivo funciones.py. Se implementan las mismas en una API mediante la interfaz fastAPI y el deploying en el servidor de RENDER. El mismo está disponible en la página: https://pi-henry-urteaga.onrender.com/docs
</p>
