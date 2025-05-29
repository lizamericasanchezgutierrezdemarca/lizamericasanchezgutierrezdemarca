
# 🧼📊 Proyecto Titanic: Limpieza y Modelado de Datos

Este proyecto muestra un flujo básico pero completo de análisis de datos usando Python, desde la limpieza hasta la creación de un modelo predictivo simple.

---

## 📁 Archivos

- `limpieza_datos_titanic.ipynb`: Notebook donde se realiza la limpieza del dataset Titanic.
- `modelado_titanic.ipynb`: Notebook con el modelado predictivo para predecir la supervivencia de los pasajeros.

---

## 🧽 Limpieza de Datos

En este notebook se realizó:

- Revisión de valores nulos
- Imputación de valores faltantes (`age`, `embarked`)
- Eliminación de columnas con demasiados valores nulos (`deck`)
- Codificación de variables categóricas con `pd.get_dummies`

---

## 🎯 Modelado Predictivo

Después de la limpieza, se utilizó un modelo de **Regresión Logística** para predecir si un pasajero sobrevivió o no. Se dividieron los datos en entrenamiento y prueba usando `train_test_split`.

### Evaluación:
Se utilizaron métricas como:

- Accuracy
- Matriz de confusión
- Reporte de clasificación

---

## ⚙️ Librerías Usadas

- `pandas`
- `seaborn`
- `missingno`
- `scikit-learn`

---

## 🌱 Próximos pasos

- Probar con otros modelos (Random Forest, SVM, etc.)
- Visualizar importancia de variables
- Aplicar escalado y normalización
- Publicar resultados y visualizaciones

---

Proyecto realizado como parte del portafolio de Ciencia de Datos de Liz ✨
