# Superstore-Sales
Dashboard ejecutivo en Power BI para el análisis de ventas y rentabilidad. Incluye modelado de datos, métricas DAX avanzadas y visualización estratégica de KPIs financieros

Dashboard de Control de Ventas y Rentabilidad (Superstore)
Este proyecto integra el uso de Python para el procesamiento de datos y Power BI para la visualización estratégica. El objetivo es monitorear el desempeño comercial y la salud financiera de una operación de retail, analizando la relación entre volumen de ventas y margen de utilidad.

## Herramientas y Tecnologías
 
* Python (Pandas & NumPy): Utilizado para la fase de ETL y limpieza de datos. Se estandarizaron formatos, se manejaron valores nulos y se preparó el dataset para asegurar la integridad de la información.

* Power BI: Diseño de interfaz de usuario (UX/UI) y visualización interactiva.

* DAX: Implementación de medidas de inteligencia de tiempo (YoY), variaciones porcentuales y formato condicional.

## Visualización del Proyecto
![Dashboard Principal](Imagenes/Dashboard%20general.png)
![Dashboard Principal filtros ](Imagenes/Dashboard%20general%20filtros.png)

## Hallazgos y Análisis de Negocio (Insights)

### Hallazgos y Análisis de Negocio (Insights)

* La compañía mantiene un Margen Neto del 12.47%. Financieramente, esto indica una operación estable donde, por cada $100 USD de ingresos, se retienen $12.47 USD de utilidad neta.

* Al cierre de 2014, la facturación alcanzó $733,947 USD, reflejando un crecimiento interanual del 21%. Este desempeño no solo confirma la tracción del modelo de negocio, sino que también evidencia una consolidación en el mercado y abre oportunidades para escalar operaciones en el corto plazo.

### Análisis de Desempeño Regional

* Se identificó un desempeño crítico en la Región Central, la cual registró la utilidad más baja ($39,706 USD) y una contracción del -0.22% frente al año anterior, siendo la única región con crecimiento negativo.
   [Ver detalle de región central](Imagenes/KPI%20centra.png)

* El producto líder global, Canon imageCLASS 2200, no figura dentro del Top 5 en la Región Sur. Este comportamiento atípico sugiere posibles dinámicas locales como mayor competitividad en la categoría o limitaciones de inventario, lo que podría estar afectando su desempeño y representando una oportunidad de mejora en la estrategia comercial.
  [Ver detalle de región south](Imagenes/kpi%20south.png)

### Segmentación y Materialidad

* El segmento Consumer concentra la mayor parte de los ingresos, mientras que Home Office tiene una presencia mucho más baja. Esto deja ver una oportunidad clara para impulsar este segmento con una estrategia más enfocada.

* Mediante un filtro de materialidad (pérdidas > $1,000 USD), se aislaron los productos con mayor impacto negativo en el flujo de caja. Destaca el producto  la Cubify CubeX 3D Printer Double Head Print, que con ventas de $11,100 USD genera una pérdida directa de -$8,880 USD (-80% de margen). Se recomienda la renegociación inmediata de costos con proveedores para estos productos
 [Ver detalle de KPI](Imagenes/KPI%20Margen.png)

* El District of Columbia (36.98%) y los estados de Delaware (36.35%) y Minnesota (36.24%) concentran los mayores porcentajes de utilidad neta, posicionándose como las principales contribuciones al resultado total.








