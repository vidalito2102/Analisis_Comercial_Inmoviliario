# Analisis_Comercial_Inmoviliario

Este repositorio contiene el análisis del desempeño comercial para comprender su crecimiento, rentabilidad y comportamiento de los clientes
Se construyo un **dashboard ejecutivo** que permite analizar ventas, clientes y propiedades para apoyar decisiones estratégicas basadas en datos.

Los Datasets analizados son los siguientes:

🔹 **hecho_ventas_propiedades**  
Tabla de hechos con las transacciones de venta (precio, cliente, propiedad, canal, fecha).

🔹 **dim_clientes**  
Información y segmentación de clientes.

🔹 **dim_propiedades**  
Características de las propiedades (tipo, tamaño, ubicación, etc).

De genera en DAX Dim_fecha para facilitar los calculos de las fechas relevantes

🔹 **dim_fecha**  
Tabla calendario que deberá ser creada como parte del modelado.



## 📂 Contenido del repositorio

- `notebooks/Analisis_Comercial_Inmoviliario.pbix`

## 📘 Cómo reproducir el análisis

1. Abre `notebooks/Analisis_Comercial_Inmoviliario.pbix`
2. Visualiza la información analizada

  
## 🧠 Objetivo del análisis

**Desempeño general**

- ¿Cuál es el **ingreso total** generado por la empresa?
- ¿Cuántas **propiedades se han vendido**?
- ¿Cuál es el **precio promedio de venta**?
- ¿Cuál es la **comisión total** generada por la empresa?

**Análisis comercial**

- ¿Qué **tipo de propiedad genera más ingresos**?
- ¿Qué **segmento de clientes compra más propiedades**?
- ¿Qué canal de venta **genera mayor ingresos**?


**Análisis temporal**

- ¿Cómo evolucionan las **ventas en el tiempo**?
- ¿El negocio está **creciendo año contra año**?
- ¿Cómo va el desempeño **acumulado del año actual (YTD)**?

**Cohortes de clientes**

- ¿Los clientes **vuelven a comprar** después de su primera compra?
- ¿Qué **cohortes de clientes generan más compras/ingresos con el tiempo**?
