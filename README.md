# Client Segmentation Insights (K-Means)

Segmentación de clientes con *clustering* (K-Means) para identificar perfiles diferenciados y convertirlos en **insights accionables** (enfoque negocio).

## Objetivo
Encontrar grupos de clientes con características similares para:
- orientar campañas / ofertas por segmento
- priorizar segmentos con mayor potencial
- entender diferencias demográficas/financieras entre perfiles

## Enfoque y metodología
1. Preprocesamiento (encoding + escalado)
2. K-Means evaluando distintos K
3. Selección de K (Elbow + Silhouette)
4. Evaluación (Silhouette, Calinski–Harabasz, Davies–Bouldin)
5. Interpretación de perfiles por cluster

## Estructura del repositorio
- `notebooks/` → Notebook principal
- `docs/` → Documento explicativo

## Cómo ejecutar
```bash
python -m venv .venv
# Windows:
.venv\Scripts\activate
# Mac/Linux:
source .venv/bin/activate

pip install -r requirements.txt
jupyter notebook


## Author
Kevin Trujillo Mora
