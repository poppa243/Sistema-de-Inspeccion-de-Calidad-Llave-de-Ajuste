# Sistema de Inspección de Calidad: Llave de Ajuste 

[cite_start]Este proyecto implementa un sistema de **visión artificial** automatizado para el control de calidad de herramientas industriales, basado en el análisis geométrico y dimensional de la pieza.

## Descripción del Proyecto
El software procesa imágenes de llaves de ajuste para clasificar cada unidad como **APTA** o **NO APTA**  bajo los siguientes criterios de calidad:
* **Integridad:** La pieza debe presentar una silueta completa.
* **Control Dimensional:** El área debe ser $\ge 95\%$ del valor nominal (25,000 píxeles).
* **Ausencia de Defectos:** Detección de grietas, rebabas o roturas parciales .

## Requisitos del Sistema
El sistema requiere el siguiente entorno para su ejecución:
* **Python:** 3.11.9
* **Librerías principales:**
    * `opencv-python` (Procesamiento de imagen) 
    * `numpy` (Manejo de matrices) 

Instalación de dependencias:
```bash
pip install opencv-python numpy
