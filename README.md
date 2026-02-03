# 📊 Predicción de Churn en Telecomunicaciones

> ⚠️ **Proyecto en desarrollo** - Versión preliminar. Trabajo en progreso.

## 🎯 Objetivo del Proyecto

Este proyecto tiene como objetivo predecir el **abandono de clientes (churn)** en una empresa de telecomunicaciones mediante técnicas de Machine Learning. El análisis permite identificar clientes en riesgo de cancelar sus servicios y tomar medidas preventivas.

## 📁 Estructura del Proyecto

```
ML-Churn/
│
├── 01_Exploracion_inicial.ipynb    # Análisis exploratorio de datos
├── 02_Limpieza.ipynb               # Preprocesamiento y limpieza
├── 03_Modelado.ipynb               # Entrenamiento de modelos (En progreso 🚧)
├── df_clean.csv                    # Dataset procesado
└── README.md
```

## 🔍 Notebooks

### 1️⃣ Exploración Inicial
- Análisis descriptivo del dataset
- Visualización de distribuciones
- Identificación de patrones y relaciones

### 2️⃣ Limpieza de Datos
- Tratamiento de valores nulos
- Codificación de variables categóricas
- Normalización de features numéricas

### 3️⃣ Modelado (🚧 En desarrollo)
Modelos implementados hasta ahora:
- ✅ Regresión Logística
- ✅ Árbol de Decisión
- ✅ Random Forest
- ⏳ Optimización de hiperparámetros (Pendiente)
- ⏳ Evaluación final en test set (Pendiente)

## 🛠️ Tecnologías Utilizadas

- **Python 3.13**
- **pandas** - Manipulación de datos
- **numpy** - Operaciones numéricas
- **scikit-learn** - Modelos de Machine Learning
- **matplotlib / seaborn** - Visualización

## 📊 Dataset

El dataset contiene información de clientes de telecomunicaciones con las siguientes características:
- Variables demográficas (género, dependientes, pareja)
- Información de servicios contratados
- Datos de facturación y tenure
- Variable objetivo: **Churn** (Yes/No)

## 🚀 Cómo Ejecutar

1. Clona el repositorio:
```bash
git clone https://github.com/luis24lopez/ML-Churn.git
cd ML-Churn
```

2. Crea un entorno virtual:
```bash
python -m venv envpy313
source envpy313/bin/activate  # En Windows: envpy313\Scripts\activate
```

3. Instala las dependencias:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

4. Ejecuta los notebooks en orden:
```bash
jupyter notebook
```

## 📈 Estado Actual

🟢 **Completado:**
- Análisis exploratorio de datos
- Limpieza y preprocesamiento (con posibilidad de mejorarlo)
- Implementación de modelos base

🟡 **En progreso:**
- Optimización de hiperparámetros
- Feature engineering avanzado
- Comparación exhaustiva de modelos

🔴 **Pendiente:**
- Evaluación final en conjunto de test
- Interpretabilidad del modelo (SHAP values)
- Deployment del modelo

## 📝 Próximos Pasos

- [ ] GridSearch para optimización de hiperparámetros
- [ ] Implementar modelos adicionales (XGBoost, LightGBM)
- [ ] Análisis de feature importance
- [ ] Crear pipeline de predicción
- [ ] Documentar conclusiones y recomendaciones

## 👤 Autor

**Luis López**
- GitHub: [@luis24lopez](https://github.com/luis24lopez)

## 📄 Licencia

Este proyecto es de código abierto y está disponible bajo la licencia MIT.

---

⭐ Si este proyecto te resulta útil, ¡no olvides darle una estrella!

*Última actualización: Febrero 2026*
