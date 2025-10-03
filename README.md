# Proyecto de Análisis de Ventas

Este proyecto analiza los datos de ventas de la empresa Aurelion.

## Configuración del Entorno

Para ejecutar este proyecto, es necesario configurar un entorno virtual de Python. Esto aísla las dependencias del proyecto y evita conflictos con otros proyectos de Python.

### 1. Crear el Entorno Virtual

Ejecuta el siguiente comando en la raíz del proyecto para crear un entorno virtual llamado `venv`:

```bash
python -m venv venv
```

### 2. Activar el Entorno Virtual

**En Windows:**

```bash
venv\Scripts\activate
```

**En macOS y Linux:**

```bash
source venv/bin/activate
```

## Instalación de Dependencias

Una vez que el entorno virtual está activado, instala las dependencias del proyecto ejecutando el siguiente comando:

```bash
pip install -r requirements.txt
```

## Ejecución del Proyecto

El fichero principal del proyecto es `reporte-1.py`. Este fichero genera un reporte de ventas y utiliza el módulo `graficos.py` para crear visualizaciones de los datos.

Para ejecutar el proyecto, asegúrate de que el entorno virtual esté activado y luego ejecuta el siguiente comando:

```bash
python reporte-1.py
```
