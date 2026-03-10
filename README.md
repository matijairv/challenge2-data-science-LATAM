# 📊 Telecom X — Análisis de evasión de clientes (Churn)

Proyecto de análisis de datos realizado en el marco del programa **Oracle Next Education — Data Science LATAM**.

El objetivo de este proyecto es analizar el fenómeno de **evasión de clientes (Churn)** en una empresa ficticia de telecomunicaciones llamada **Telecom X**, identificando los factores que influyen en la cancelación del servicio.

A través de un proceso de **extracción, transformación y análisis exploratorio de datos**, se busca comprender el comportamiento de los clientes y generar insights que permitan mejorar las estrategias de retención.

---

# 🎯 Objetivo del proyecto

El objetivo principal es:

- Analizar los factores que influyen en el **abandono de clientes**.
- Identificar **patrones de comportamiento** asociados al churn.
- Generar **insights estratégicos** que puedan ayudar a reducir la pérdida de clientes.

---

# 🧩 Proceso de análisis

El proyecto se desarrolló siguiendo un flujo típico de análisis de datos.

## 📥 Extracción de datos

Los datos fueron proporcionados en formato **JSON** con una estructura anidada.

## 🔧 Transformación de datos

Se realizó el proceso de **normalización (flattening)** para convertir el dataset en una estructura tabular adecuada para el análisis.

También se realizaron tareas de:

- limpieza de datos  
- conversión de tipos de variables  
- eliminación de inconsistencias  
- creación de nuevas variables  

## 📊 Análisis exploratorio de datos (EDA)

Se realizaron visualizaciones para analizar la relación entre el abandono de clientes y variables como:

- tipo de contrato  
- antigüedad del cliente  
- costo del servicio  
- servicios adicionales  

---

# 📈 Principales insights

El análisis permitió identificar varios factores asociados al abandono de clientes:

- ⚠️ Los clientes con **contratos mensuales** presentan mayor tasa de cancelación.  
- ⏳ Los clientes con **poca antigüedad** tienen mayor probabilidad de abandonar el servicio.  
- 💰 Los clientes con **cargos mensuales más altos** tienden a cancelar con mayor frecuencia.  
- 🛠 Los clientes que cuentan con **soporte técnico** presentan menor tasa de abandono.  

---

# 📁 Estructura del repositorio

    challenge2-data-science-LATAM
    │
    └── images/
      └── Abandonos.png
      └── Dsitribucion_gastos.png
      └── Distribucion_meses_abandonos.png
      └── Proporcion_clientes.png
      └── Relaciones_abandonos.png
    ├── TelecomX_LATAM.ipynb
    ├── TelecomX_Data.json
    ├── TelecomX_diccionario.md
    └── README.md

- **images** → Imágenes extraidas del análisis desarrollado
- **TelecomX_LATAM.ipynb** → Notebook con el análisis completo  
- **TelecomX_Data.json** → Dataset utilizado en el proyecto  
- **TelecomX_diccionario.md** → Diccionario de datos del dataset  
- **README.md** → Descripción del proyecto  

---

# 🛠 Tecnologías utilizadas

- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

# 🔗 Repositorio del proyecto

Puedes ver el proyecto completo en GitHub:

https://github.com/matijairv/challenge2-data-science-LATAM

---

# 📚 Programa

Proyecto desarrollado dentro del programa:

**Oracle Next Education (ONE) — Data Science LATAM**
