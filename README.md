# Análisis de Rendimiento de Tiendas – Sr Juan

Este proyecto tiene como objetivo analizar el rendimiento de cuatro tiendas online de la empresa de **Sr Juan**, con el fin de determinar cuál de ellas presenta el peor desempeño y debería ser cerrada.

## Dataset

Se analizaron datos de cuatro tiendas disponibles públicamente en formato CSV, a través de enlaces directos en GitHub.

---

## Bibliotecas necesarias

Antes de ejecutar el notebook, asegúrate de tener instaladas las siguientes bibliotecas:

```
!pip install pandas matplotlib
```
## Ejecucion
* Clona este repositorio o descarga el notebook AluraStoreLatam.ipynb.
* Ejecuta cada celda en orden para realizar el análisis completo.
* Asegúrate de tener conexión a internet, ya que los datos se cargan desde URLs.

# Análisis realizados

1. Ingresos Totales por Tienda: Se suman los precios de todos los productos vendidos para evaluar qué tienda genera más ingresos.

2. Ventas por Categoría: Se analiza cuántos productos se vendieron por cada categoría en cada tienda, para ver la diversificación de ventas.

3. Calificación Promedio: Se calcula la media de las calificaciones de los productos en cada tienda, como medida de satisfacción del cliente.

4. Productos Más y Menos Vendidos : Se identifican los productos más populares y aquellos menos populares.

5. Costo de Envío Promedio: Se compara el promedio del costo de envío por tienda.


# Recomendacion
Lo mejor para Sr Juan seria eliminar la Tienda 4, ya que es la menos rentable en general. Su único punto fuerte es el bajo coste de envío, pero no compensa sus bajos ingresos, calificación mediocre y pobre desempeño en categorías clave. Además, si se mejora la logística en otra tienda (como en tienda 1), se puede compensar ese coste de envío más bajo.
