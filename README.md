# PROYECTO EDA  
## Deportes de Montaña y Seguridad en Madrid

---

### Aclaración: acordamos previamente con Soraya Malpica que los datasets no se subirán al repositorio público por contener datos sensibles. Por lo que la carpeta Datasets esta vacía. Los datasets, crudos y curados se entregaron de froma privada para que los códigos de los notebooks funcionen.

## Descripción del proyecto

Este proyecto realiza un **Análisis Exploratorio de Datos (EDA)** sobre federados de deportes de montaña en la Comunidad de Madrid, con el objetivo de analizar la **relación entre el perfil del federado, el tipo de seguro contratado y la siniestralidad asociada**.

El estudio busca identificar patrones en la **frecuencia y gravedad de los siniestros**, aportando información útil para la toma de decisiones en el ámbito de la **gestión del riesgo y seguros deportivos**.

---

## Hipótesis planteadas

**Hipótesis A**  
Los federados con seguros de mayor cobertura presentan una tasa de siniestralidad superior al promedio del total de federados.

**Hipótesis B**  
Los federados mayores de 35 años presentan siniestros de mayor gravedad media que los asociados a seguros básicos.

---

## Tecnologías utilizadas

- **Lenguaje:** Python  
- **Librerías:**  
  - pandas  
  - numpy  
  - matplotlib  
  - seaborn  
- **Herramientas:**  
  - Jupyter Notebook  
  - Git / GitHub  

---

## Instrucciones de reproducción

1. Clonar el repositorio:
   ```bash
   git clone <https://github.com/jorgemd2698/EDA_Jorge_Martinez_Kelly_Escalante_Danilo_Castillo.git>
   
2. Abrir los notebooks en Jupyter Notebook o Jupyter Lab.

3. Ejecutar los notebooks en orden:

Notebook 1 → Limpieza licencias

Notebook 2 → Limpieza siniestros

Notebook 3 → Análisis exploratorio


## Estructura del repositorio
```
├── notebooks/
│ ├── notebook_1_limpieza_licencias.ipynb
│ ├── notebook_2_limpieza_siniestros.ipynb
│ └── notebook_3_eda.ipynb
├── datasets/
│ ├── licencias_limpio.csv
│ └── siniestros_limpio.csv
├── README.md
└── memoria_tecnica.pdf
```

## Principales conclusiones

Existen diferencias relevantes en la tasa de siniestralidad según la modalidad de seguro.

Los federados mayores de 35 años concentran una mayor proporción de siniestros de mayor gravedad.

La tasa global de siniestralidad se sitúa en torno a 33 siniestros por cada 1.000 federados.

Las hipótesis planteadas quedan respaldadas por el análisis exploratorio realizado.

## Autores

Kelly Escalante
GitHub: https://github.com/Kelly481


Danilo Castillo
GitHub: https://github.com/Danilomcastillo


Jorge Martínez Delgado
GitHub: https://github.com/jorgemd2698


