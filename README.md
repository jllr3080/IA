# Proyecto IA

Repositorio académico de aprendizaje automático e inteligencia artificial.

## Contenido

- `AprendizajeAutomatico/ClaseSemana3`: notebooks de clasificación, clustering y PCA.
- `AprendizajeAutomatico/TallerPractico1`: ejercicios iniciales de construcción de datasets.
- `AprendizajeAutomatico/TallerPractico2`: taller práctico de riesgo crediticio.
- `AprendizajeAutomatico/TallerPractico3`: sistema analítico responsable de retención estudiantil con OULAD.

## Taller Práctico 3

El notebook principal es:

```text
AprendizajeAutomatico/TallerPractico3/maestro.ipynb
```

Incluye:

- descarga automática del dataset OULAD desde Kaggle;
- construcción del maestro estudiante–módulo–presentación;
- controles de calidad basados en DAMA;
- análisis exploratorio y clustering;
- PCA y t-SNE;
- Árbol de Decisión y XGBoost con validación temporal;
- regularización, subsampling y early stopping;
- importancia de variables y SHAP global/local;
- recomendaciones ejecutivas por visualización.

## Datos

Las carpetas `data/` y `datos/` están excluidas de Git. El notebook de Taller Práctico 3 crea `data/` y descarga automáticamente los archivos públicos de OULAD cuando no existen.

Fuente:

```text
https://www.kaggle.com/datasets/anlgrbz/student-demographics-online-education-dataoulad
```

## Ejecución

1. Crear un entorno virtual.
2. Instalar las dependencias:

```bash
pip install -r requirements.txt
```

3. Abrir Jupyter y ejecutar el notebook deseado desde el principio.

## Privacidad y uso responsable

Las predicciones académicas son señales de apoyo y no decisiones automáticas. Deben mantenerse supervisión humana, minimización de datos, auditoría de equidad y validación temporal con información local.

