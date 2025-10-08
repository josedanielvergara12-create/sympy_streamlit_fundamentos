# Teoría de SymPy

## Visión general de SymPy
SymPy es una biblioteca de Python para matemáticas simbólicas. Permite realizar cálculos algebraicos, diferenciales y matriciales de manera exacta, facilitando la modelación y resolución de problemas ingenieriles.

## Álgebra simbólica
SymPy permite definir variables simbólicas y manipular expresiones algebraicas, simplificarlas, expandirlas y factorizar.

**Ejemplo ilustrativo:**
```
Definir variables simbólicas x, y
Expresión: x^2 + 2*x*y + y^2
Operaciones: expandir, factorizar, simplificar
```

## Cálculo: derivadas e integrales
SymPy realiza derivaciones e integraciones simbólicas, útiles para análisis matemático y físico.

**Ejemplo ilustrativo:**
```
Derivar f(x) = sin(x)*exp(x) respecto a x
Integrar g(x) = x^2*log(x) respecto a x
```

## Ecuaciones algebraicas y diferenciales
Permite resolver ecuaciones polinómicas y sistemas, así como ecuaciones diferenciales ordinarias.

**Ejemplo ilustrativo:**
```
Resolver x^2 - 4 = 0
Resolver sistema: x + y = 2, x - y = 0
Resolver ecuación diferencial: dy/dx + y = x
```

## Matrices
SymPy soporta operaciones matriciales simbólicas: suma, producto, determinante, inversa y autovalores.

**Ejemplo ilustrativo:**
```
Definir matriz simbólica A
Calcular determinante, inversa y autovalores de A
```

## Unidades y constantes
Incluye manejo de unidades físicas y constantes universales para cálculos científicos.

**Ejemplo ilustrativo:**
```
Expresar velocidad en m/s
Utilizar constante de gravitación universal G
```

## Buenas prácticas
- Definir variables simbólicas con nombres claros.
- Documentar cada paso matemático.
- Validar resultados simbólicos antes de evaluar numéricamente.
- Integrar SymPy con Streamlit para visualización interactiva.

## Ejemplos conceptuales para Streamlit
- Visualizar la gráfica de una función simbólica.
- Mostrar el paso a paso de una derivada o integral.
- Resolver y presentar sistemas de ecuaciones.
- Manipular matrices y mostrar resultados en tablas interactivas.
