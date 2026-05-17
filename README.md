# TFG - Detección de anomalías en redes OT usando ML y DL

Repositorio con el código del Trabajo Fin de Grado de Fulgencio Vicente Ortega
(Ingeniería en Tecnologías de Telecomunicación, UCAM, 2026).

## Contenido

- `01_exploracion_limpieza.ipynb` — Exploración del dataset ICS-Flow,
  análisis de protocolos, decisiones de limpieza y selección de features
  (Mann-Whitney y correlación).
- `02_baseline_y_ml.ipynb` — Baseline Z-score y modelos de Machine Learning
  clásico: Random Forest, XGBoost, Isolation Forest y LOF.
- `03_deep_learning.ipynb` — Modelos de Deep Learning: MLP, Autoencoder
  denso y CNN 1D Autoencoder.

## Dataset

Se utiliza el dataset público **ICS-Flow** (Dehlaghi-Ghadim et al., 2023).

## Requisitos

- Python 3.10+
- pandas, numpy, scikit-learn, xgboost, tensorflow/keras, matplotlib, seaborn, scipy

## Ejecución

Abrir los notebooks en orden con Jupyter o Google Colab.
