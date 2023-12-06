# Análisis de Datos de Marketing

Este proyecto de análisis de datos utiliza pandas y posiblemente otras bibliotecas para explorar un conjunto de datos relacionados con datos de marketing.

## Introducción

El conjunto de datos (`datos_marketing.csv`) consta de 2240 filas (clientes) con 28 columnas relacionadas con datos de marketing. Las columnas incluyen información sobre el cliente, sus compras, campañas de marketing y más.

## Tareas

### Limpieza de Datos

1. **Lea el dataset:**
   - Utilice la función `pd.read_csv` para cargar el conjunto de datos.

2. **Verificación de la información del dataset:**
   - Use el comando `.info()` para obtener información sobre las columnas y tipos de datos.

3. **Visualización de las primeras filas:**
   - Utilice el comando `.head()` para examinar las primeras filas del conjunto de datos.

4. **Tratamiento de la columna 'income':**
   - Elimine espacios en el nombre de la columna y elimine el símbolo del dólar.
   - Cambie la columna al tipo float.

5. **Identificación de valores nulos:**
   - Utilice el comando `.isnull()` y `.sum()` para identificar el número de valores nulos en cada columna.

6. **Relleno de valores nulos en 'Income':**
   - Rellene los valores nulos con la mediana de la columna 'Income'.

7. **Transformación de la columna 'Dt_Customer':**
   - Cambie el tipo de la columna a tipo datetime.

### Ingeniería de Datos

8. **Creación de nuevas columnas:**
   - Crea nuevas columnas como 'Dependents', 'Year_Customer', 'TotalMnt', 'TotalPurchases', y 'TotalCampaignsAcc' según las necesidades del análisis.



