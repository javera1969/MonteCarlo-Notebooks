# MonteCarlo-Notebooks

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/javera1969/MonteCarlo-Notebooks/HEAD)

[![Voilà](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/javera1969/MonteCarlo-Notebooks/HEAD?urlpath=voila/render/Simulacion_Balistica_MonteCarlo_Interactivo_SinCodigo.ipynb)

Colección de notebooks educativos sobre el Método de Monte Carlo y aplicaciones balísticas.

## Contenido

1. Estimación de pi mediante el método de Monte Carlo.
2. Integración de Monte Carlo en una región triangular.
3. Probabilidad en una baraja española.
4. Aplicación balística con incertidumbre.
5. Aplicación interactiva con Voilà.

## Ejecución online

### Abrir JupyterLab en Binder

Pulse el botón **Binder** situado al comienzo de este documento.

### Abrir la aplicación Voilà

Pulse el botón **Voilà** situado al comienzo de este documento.

Voilà muestra el cuaderno como una aplicación interactiva, ocultando las celdas de código.

## Ejecución local

Instalar dependencias:

```bash
pip install -r requirements.txt
```

Lanzar JupyterLab:

```bash
jupyter lab
```

Lanzar Voilà localmente:

```bash
voila Simulacion_Balistica_MonteCarlo_Interactivo_SinCodigo.ipynb
```

## Archivos principales

- `Simulacion_Balistica_MonteCarlo.ipynb`: notebook principal.
- `Simulacion_Balistica_MonteCarlo_mathjax_fixed.ipynb`: versión con ecuaciones corregidas para MathJax.
- `Simulacion_Balistica_MonteCarlo_Interactivo_SinCodigo.ipynb`: versión interactiva preparada para Voilà.
- `environment.yml`: entorno Conda para Binder.
- `requirements.txt`: dependencias para instalación local con pip.
- `runtime.txt`: versión de Python para Binder.

## Autor

Juan Antonio Vera López  
Centro Universitario de la Defensa  
Academia General del Aire y del Espacio
