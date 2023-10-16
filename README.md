# Proyecto de Análisis Exploratorio de Datos (EDA) sobre la Seguridad en el estado de Jalisco
# Roberto Ramirez

El presente proyecto de Análisis Exploratorio de Datos (EDA) tiene como objetivo investigar y comprender en profundidad la dinámica delictiva en el estado de Jalisco, utilizando una base de datos detallada proveniente de la plataforma de seguridad del estado. Esta base de datos proporciona información valiosa sobre diversos delitos reportados, incluyendo la fecha, tipo de delito, ubicación geográfica, hora, bien afectado y otros atributos relevantes.

El análisis se centra en desentrañar patrones, tendencias y relaciones significativas dentro de los datos. A través del uso de técnicas estadísticas y visuales, se pretende identificar áreas geográficas con altos índices delictivos, períodos de tiempo críticos y posibles correlaciones entre ciertos tipos de delitos y variables como ubicación, hora del día o bienes afectados.

La base de datos contiene información detallada sobre una variedad de delitos, desde robos hasta homicidios, ocurridos en diferentes municipios y colonias de Jalisco. Cada entrada en la base de datos incluye información específica, como la fecha del incidente, tipo de delito, ubicación geográfica (coordenadas x y y), colonia, municipio, clave municipal, hora del día, bien afectado y zona geográfica.

Este análisis EDA no solo busca proporcionar una visión clara y comprensiva de la situación delictiva en Jalisco, sino también ofrecer valiosas perspectivas para informar políticas públicas, estrategias de seguridad y toma de decisiones basada en datos. Al examinar detenidamente estos datos, se espera generar conocimientos significativos que contribuyan a la mejora de la seguridad y calidad de vida de los habitantes del estado de Jalisco.

# Resultados

Las bases de datos fueron procesadas para abordar los valores NA según los requisitos del estudio. Se identificaron diversos problemas que impactaron en la estrategia de análisis y se corrigieron oportunamente. 

Al utilizar un mapa de calor, se evidenció una concentración significativa de delitos en la zona metropolitana de Guadalajara (AMG) durante el período 2017-2023. 

![Heatmap incidencia delictiva en el Estado de Jalisco](/results/heatmap.png)

Esto se corroboró mediante una gráfica adicional que detalla los delitos reportados en los municipios de Jalisco. Esta concentración era previsible debido a la densidad poblacional del AMG.

![Delitos reportados en el Estado de Jalisco por Municipio](/results/delitos_reportados_municipio.png)

Los delitos más frecuentes incluyeron robo a vehículos particulares, robo a personas, violencia familiar, robo a negocios y lesiones dolosas.

![Delitos más frecuentes en el Estado de Jalisco](/results/delitos_totales.png)

 La mayoría de las categorías delictivas mostraron una disminución a lo largo del tiempo, excepto por casos como violencia familiar, abuso sexual infantil, violación y feminicidio. Este último mostró una tendencia constante, aunque con un corte en septiembre de 2023, la diferencia podría ser mayor.

![Tendencia de delitos en el Estado de Jalisco (2017 - 2023)](/results/Tendencia_por_delito.png)

## Conclusiones:
El análisis exploratorio reveló las tendencias delictivas principales en el Estado, proporcionando una base para futuras propuestas de soluciones. Se sugiere un análisis adicional que normalice los diferentes tipos de delitos por municipio, considerando la población local, para evaluar las tasas de delincuencia. Esto permitiría a los responsables políticos implementar estrategias específicas en áreas problemáticas. Además, se planea desarrollar un modelo predictivo de delitos a largo plazo para mejorar la efectividad de la vigilancia y prevenir ciertos tipos de delitos.

Link al EDA: [EDA Seguridad en el estado de Jalisco - Jupyter Notebook](https://github.com/robrmz/EDA-Seguridad-en-el-estado-de-Jalisco/blob/main/src/Proyecto%20de%20An%C3%A1lisis%20Exploratorio%20de%20Datos%20(EDA)%20sobre%20la%20Seguridad%20en%20el%20estado%20de%20Jalisco.ipynb)


## Estructura de repositorio

    ├── LICENSE           <- Licencia MIT.
    |  
    ├── README.md         <- Archivo principal README con la descripción del proyecto.
    |  
    ├── CONTRIBUTING.md   <- Pasos para contribuir al proyecto.
    |  
    ├── CITATION.md       <- Forma de citar el proyecto.
    |  
    ├── data              <- Bases de datos originales.
    |  
    ├── doc               <- Archivos de texto.
    |  
    ├── results           <- Bases de datos limpias y analizadas.
    |  
    └── src               <- Archivos de código.



