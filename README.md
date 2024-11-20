# Proyecto: Análisis de Datos de Instacart

## Contexto
Este proyecto se basa en un conjunto de datos modificado de **Instacart**, una plataforma de entregas de comestibles que permite a los usuarios realizar pedidos y recibirlos en casa, similar a servicios como Uber Eats o DoorDash. 
El conjunto de datos original fue publicado en 2017 como parte de una competición de Kaggle y ha sido adaptado para este proyecto con modificaciones que incluyen:

- Reducción del tamaño del dataset.
- Introducción de valores ausentes y datos duplicados.
- Mantenimiento de las distribuciones originales para preservar el realismo.

El objetivo es realizar una limpieza de los datos y generar un informe que ofrezca información clave sobre los hábitos de compra de los clientes de Instacart.

## Herramientas Utilizadas
- **Python:** para el procesamiento de datos.
- **Pandas:** para manipulación de datos.
- **Matplotlib / Seaborn:** para la visualización de datos.
- **Tableau:** para visualización interactiva y análisis adicional.
- **Jupyter Notebooks:** para documentar y ejecutar el código.

## Análisis de Resultados
### 1. **Limpieza de Datos**
- **Eliminación de Duplicados:** Se identificaron y eliminaron los registros duplicados para asegurar la integridad de los análisis.
- **Manejo de Valores Ausentes:** Se realizó la imputación de datos faltantes en ciertas columnas críticas para evitar sesgos en el análisis. Algunas columnas con demasiados valores faltantes fueron eliminadas.

### 2. **Análisis Exploratorio de Datos**
- **Distribuciones de Datos:** Se analizó la distribución de las compras por cliente y la frecuencia de las categorías de productos comprados. Los productos más comprados fueron aquellos de la categoría de alimentos frescos, seguidos por productos envasados.
- **Patrones de Compra:** Los clientes tienden a realizar compras más grandes en fines de semana, lo que indica una mayor demanda en esos días.

### 3. **Visualización de Resultados**
- **Gráficos de Frecuencia de Compras:** Utilizando **Seaborn** y **Matplotlib**, se generaron gráficos que muestran las categorías más populares y la relación entre la frecuencia de compra y el tipo de cliente.
- **Mapas de Calor:** Para mostrar la correlación entre variables, se usaron mapas de calor que ilustran cómo las compras se distribuyen entre diferentes horarios del día y días de la semana.

## Conclusiones
- **Patrones de Compras:** Los clientes de Instacart compran principalmente productos frescos y en mayor cantidad durante los fines de semana. Esta información es valiosa para ajustar las estrategias de marketing y promoción.
- **Optimización del Servicio:** La identificación de los productos más comprados y la preferencia por ciertos días de la semana puede ayudar a Instacart a mejorar la experiencia del usuario y optimizar la oferta de productos según la demanda.
- **Recomendaciones:** Se recomienda a Instacart que aproveche la mayor actividad de compras durante el fin de semana para lanzar promociones especiales o descuentos dirigidos a aumentar las ventas en esos días.

Este análisis de datos ha proporcionado una visión profunda sobre los hábitos de compra de los clientes, lo que permitirá a Instacart ajustar su estrategia para mejorar la eficiencia y experiencia del usuario en la plataforma.
