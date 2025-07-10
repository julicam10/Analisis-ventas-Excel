# 📊 Resumen de Fundamentos del Proyecto de Análisis de Datos

## 🎯 Objetivo del proyecto
Analizar las ventas realizadas por un supermercado con presencia global durante los años 2011 a 2014, con el fin de identificar los KPI's relacionados con la venta de productos, ingresos, clientes y sucursales. El análisis será representado por medio de tablas dinámicas y gráficos dinámicos en Excel.

## 🗂️ Descripción del conjunto de datos
- **Total de registros:** 51.290 registros
- **Año:** 2014
- **Columnas principales:** 
  - Número Venta
  - ID Venta
  - Fecha Salida
  - Fecha Entrega
  - Días Transcurridos
  - Días Laborales Transcurridos
  - Método Envio
  - ID Cliente
  - Número Cliente
  - Nombre Cliente
  - Segmento
  - Ciudad
  - Estado
  - País
  - ID Producto
  - Ventas
  - Cantidad
  - Descuento
  - Utilidad
  - Costo Envío
  - Prioridad Envio
- **Fuente:** Curso: Experto en Análisis y Visualización de Datos - Udemy

## 🧹 Limpieza y preparación de los datos
- Se detectaron fechas mal formateadas y fueron convertidas al formato `DD/MM/AAAA`
- Se aplicaron fórmulas para validar tipos de datos y corregir errores en fechas
- Se normalizó el formato numérico en las columnas requeridas
- Se realizó la creación de columnas a partir de registros sin valor

## 📈 Métricas analizadas
1. **Clientes únicos**
2. **Ticket promedio**
3. **Total facturado**
4. **Volumen de compras**
5. **Ventas totales por mes**
6. **Clientes con más compras**
7. **Países con más ventas**
8. **Envios por día de la semana vs la cantidad de ventas**
9. **Ventas por región vs la utilidad generada**
10. **Ventas por cada método de envio**
11. **Ventas por cada segmento**

## 🧮 Herramientas y funciones utilizadas
- **Fórmulas de Excel:**
  - `SUM()`
  - `COUNT()`
  - `TEXT()`
  - `DATE()`
  - `CANCAT()`
  - `LEFT()`
  - `DATE()`
  - `FIND()`
  - `RIGHT()`
  - `MID()`
  - `DAYS()`
  - `NETWORKDAYS()`
  - `VLOOCKUP()`
- **Tablas dinámicas** para el resumen de métricas (KPI's)
- **Segmentación por filtros** 
- **Gráficos dinámicos**