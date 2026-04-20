# Kaggle-Repo

## Resumen de los que debo hacer

1. Entender el problema 📌

¿Es clasificación, regresión, series temporales?
¿Cuál es la variable objetivo (target)?
¿Cómo se evalúa (accuracy, RMSE, AUC)?

2. Cargar y explorar lo básico
Ver dimensiones (shape)
Tipos de datos (dtypes)
Primeras filas (head())

Variables numéricas vs categóricas
IDs irrelevantes
Datos raros a simple vista

3. Calidad de datos 🧹

Valores nulos (isnull().sum())
Duplicados
Valores inconsistentes (ej: edades negativas)

¿Los nulos son muchos?
¿Son aleatorios o tienen patrón?

4. Análisis univariado

Analizar cada variable por separado:

Numéricas
Histogramas
Boxplots
Media, mediana, desviación

Buscar:

Outliers
Distribuciones raras (sesgadas)
Categóricas
Conteo de categorías (value_counts)
Frecuencias

Buscar:

Categorías raras o dominantes

5. Relación con el target 🎯

Numéricas vs target → scatterplots, boxplots
Categóricas vs target → barplots

Buscar:

Variables que separen bien el target
Patrones claros

6. Análisis bivariado/multivariado
Correlación (corr())
Heatmaps
Pairplots

Buscar:

Variables altamente correlacionadas (redundantes)
Relaciones interesantes entre variables

7. Feature engineering inicial ⚙️

Basado en el EDA:

Crear nuevas variables
Transformaciones (log, binning)
Encoding de categóricas

8. Detectar leakage 🚨

Variables que “filtran” el resultado
Datos futuros en problemas temporales

Si algo parece “demasiado perfecto”, sospecha.

9. Visualización clara 📊

No hagas 100 gráficos inútiles, prioriza los que aportan insight
Usa títulos claros
Explica qué significa cada gráfico

10. Conclusiones accionables

Al final del EDA deberías poder decir:

Qué variables usar
Qué limpiar o transformar
Qué modelo podría funcionar
Comenta tus hallazgos

Usa librerías como:
pandas
matplotlib
seaborn
Resumen corto

Un buen EDA en Kaggle:

Entiende el problema
Limpia datos
Explora variables
Relación con el target
Genera features
Saca conclusiones
