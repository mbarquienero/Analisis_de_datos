# Análisis de Datos - TP Final

Este repositorio contiene el material utilizado para el trabajo práctico final para la materia *Análisis de Datos* de la Carrera de Especialización en Inteligencia Artificial (CEIA) de FIUBA.

Integrantes:

* Mauro Barquinero
* Martín Errázquin

## Temática elegida

El dataset seleccionado es el reporte de crímenes del Departamento de Policía de Chicago, restringido al año 2024.

## Referencias

* [Fuente de dataset principal](https://data.cityofchicago.org/Public-Safety/Crimes-2024/dqcy-ctma/about_data)


## Integración con `uv`

Para gestión de dependencias se provee un archivo `pyproject.toml` y se prefiere el uso de [uv](https://docs.astral.sh/uv/).

Actualizar las dependencias requiere una simple linea

```bash
$ uv sync
```

Y levantar una instancia local de Jupyter Lab, con un kernel con las dependencias del proyecto, también:

```bash
$ uv run --with jupyter jupyter lab
```
