# **TELECOM X - Análisis de Evasión de Clientes (Churn)**

## 📋 **Descripción del Proyecto**

Este proyecto analiza la alta tasa de cancelaciones (26.54%) que enfrenta **Telecom X**, una empresa de telecomunicaciones. Mediante técnicas de análisis exploratorio de datos (EDA), se identifican los factores que influyen en la evasión de clientes para desarrollar estrategias efectivas de retención.

El análisis procesa datos históricos de **7,038 clientes**, incluyendo información demográfica, contractual, de servicios y facturación.

---

## 🎯 **Objetivos**

- Identificar patrones y factores de riesgo asociados al abandono de clientes
- Analizar variables categóricas y numéricas para encontrar correlaciones con el Churn
- Proporcionar insights accionables para reducir la tasa de evasión
- Generar visualizaciones claras que faciliten la toma de decisiones

---

## 🔍 **Principales Insights**

### **Factores Críticos de Abandono:**

1. **Tipo de Contrato**: Los contratos mes a mes tienen **3.8 veces más abandono** (42.71%) que contratos de dos años (11.28%)

2. **Método de Pago**: Cheque electrónico genera **2.7 veces más abandono** (45.29%) comparado con débito automático (16.67%)

3. **Servicio de Internet**: Fiber optic presenta la mayor tasa de abandono (41.89%), sugiriendo problemas de relación precio-valor

4. **Antigüedad**: Clientes que abandonaron tienen en promedio **17.89 meses** vs **37.57 meses** de los que permanecen (-44.83%)

5. **Perfil Demográfico de Riesgo**:
   - Adultos mayores: 41.68% de abandono
   - Sin pareja: 32.96% de abandono
   - Sin dependientes: 31.28% de abandono

### **Segmentos de Alto Riesgo:**

- Clientes nuevos (< 12 meses) con contrato mensual
- Adultos mayores sin pareja ni dependientes
- Usuarios de Fiber optic con facturación online
- Clientes que pagan con cheque electrónico

---

## 🛠️ **Tecnologías Utilizadas**

- **Python 3.x**
- **Pandas**: Manipulación y análisis de datos
- **NumPy**: Operaciones numéricas
- **Matplotlib**: Visualizaciones básicas
- **Seaborn**: Visualizaciones estadísticas avanzadas
- **Jupyter Notebook**: Entorno de desarrollo interactivo

En caso de que quieras trabajar con mi mismo entorno de forma local o en línea (*ej: Google Colab*), revisa el [archivo de requerimientos](requerimientos.txt) para ver los detalles.

---
