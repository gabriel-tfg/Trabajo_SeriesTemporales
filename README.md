# Trabajo\_SeriesTemporales



# Trabajo Series Temporales — Demanda eléctrica (2015)

Repositorio con el trabajo de series temporales sobre demanda eléctrica (muestreo cada 10 minutos, año 2015).  
Incluye el informe completo, el apartado 4 (predicción SARIMA a 4 horas), datos y resultados exportados.

---

## Estructura del repositorio

- **Trabajo_SeriesTemporales.pdf**  
  Informe completo del trabajo.

- **Trabajo_SeriesTemporales.html**  
  Versión HTML del informe completo (generada desde RMarkdown).

- **Apartado4_SeriesTemporales_V2.pdf**  
  Informe del Apartado 4 (predicción a 4 horas con SARIMA).

- **Apartado4_SeriesTemporales_V2.html**  
  Versión HTML del Apartado 4 (generada desde RMarkdown).

- **Apartado4_SeriesTemporales_V2.Rmd**  
  Código fuente reproducible del Apartado 4.

- **Demanda_2015.txt**  
  Dataset de demanda eléctrica 2015 (10 min).

- **Resultados_Prediccion_Apartado4.xlsx**  
  Resultados exportados del Apartado 4 (predicciones y métricas).

- **README.md**  
  Este documento.

---

## Reproducibilidad (Apartado 4)

### Requisitos
- R (recomendado R >= 4.0)
- Paquetes: `tidyverse`, `lubridate`, `zoo`, `forecast`, `openxlsx`, `knitr`

### Ejecución
1. Abrir `Apartado4_SeriesTemporales_V2.Rmd`
2. Asegurarse de que `Demanda_2015.txt` está en la misma carpeta
3. Compilar (Knit) a PDF o HTML

El Excel `Resultados_Prediccion_Apartado4.xlsx` se genera automáticamente al ejecutar el RMarkdown.

\## Autor



Gabriel Losada Arias  

Máster en Energía – Universidad Complutense de Madrid  

Curso 2025–2026

