# Productos-Alimenticios
# README - Proyecto de Análisis del Embudo de Ventas y Test A/A/B

## Descripción del proyecto

Este proyecto se centra en el análisis del comportamiento de los usuarios dentro de una aplicación de productos alimenticios. El objetivo principal fue estudiar cómo interactúan los usuarios con la aplicación, identificar en qué etapas del embudo de ventas abandonan el proceso y evaluar el impacto de cambios de diseño mediante un experimento A/A/B.

A través del análisis de eventos y pruebas estadísticas, se buscó obtener información útil para optimizar la experiencia de usuario y mejorar la conversión dentro de la aplicación.

---

# Problema que resuelve el proyecto

La empresa necesitaba comprender por qué muchos usuarios no llegaban hasta la etapa final de compra dentro de la aplicación.

El proyecto buscó responder preguntas importantes como:

* ¿Qué porcentaje de usuarios completa el proceso de compra?
* ¿En qué etapa del embudo se pierden más usuarios?
* ¿El nuevo diseño de la aplicación mejora la conversión?
* ¿Existen diferencias significativas entre los grupos del experimento?

Para resolver estas preguntas se analizó el comportamiento de navegación de los usuarios y se aplicaron pruebas estadísticas sobre un experimento A/A/B.

---

# Metodología utilizada

## 1. Carga y exploración inicial de datos

Se realizó la carga del conjunto de datos que contiene registros de eventos generados por los usuarios dentro de la aplicación.

Durante esta etapa se revisaron:

* Nombres de columnas.
* Tipos de datos.
* Valores ausentes.
* Registros duplicados.
* Estructura general del dataset.

Esto permitió comprender la calidad de la información antes de comenzar el análisis.

---

## 2. Limpieza y preparación de datos

Se realizaron procesos de limpieza para asegurar que los datos estuvieran listos para el análisis.

### Actividades realizadas

* Conversión de nombres de columnas.
* Transformación de fechas al formato datetime.
* Verificación de duplicados.
* Revisión de valores faltantes.
* Ordenamiento cronológico de eventos.

La preparación correcta de los datos permitió trabajar de manera confiable en las siguientes etapas.

---

## 3. Análisis exploratorio de datos

Se estudiaron los eventos registrados por los usuarios para comprender cómo interactúan con la aplicación.

### Aspectos analizados

* Número total de usuarios.
* Eventos más frecuentes.
* Distribución temporal de los datos.
* Actividad diaria de usuarios.
* Inicio del periodo con datos completos.

Este análisis permitió validar que los datos fueran consistentes y representativos.

---

## 4. Análisis del embudo de ventas

Se construyó un embudo de conversión para identificar cómo avanzan los usuarios dentro de la aplicación.

### Se analizaron etapas como:

* Apertura de la aplicación.
* Visualización de productos.
* Agregado al carrito.
* Pago o compra final.

El objetivo fue detectar:

* Qué porcentaje de usuarios llega a cada etapa.
* En qué parte ocurre la mayor pérdida de usuarios.
* Qué tan eficiente es el proceso de conversión.

---

## 5. Análisis del experimento A/A/B

Se evaluó un experimento diseñado para medir el impacto de cambios en la interfaz de usuario.

### Grupos analizados

* Grupo A/A: utilizado para validar la consistencia del experimento.
* Grupo B: usuarios expuestos al nuevo diseño.

### Técnicas utilizadas

* Comparación de proporciones.
* Análisis estadístico.
* Pruebas de hipótesis.
* Comparación de conversiones entre grupos.

El objetivo fue determinar si los cambios de diseño generaban diferencias significativas en el comportamiento de los usuarios.

---

# Principales conclusiones

## 1. El embudo de ventas presenta pérdida de usuarios

El análisis mostró que una parte importante de los usuarios abandona el proceso antes de completar la compra.

Las mayores pérdidas se detectaron en las etapas intermedias del embudo.

---

## 2. No todos los eventos tienen el mismo impacto

Se identificaron eventos con mayor frecuencia de interacción, mientras que otros reflejan etapas críticas relacionadas con la conversión.

Esto permitió entender mejor el recorrido de los usuarios dentro de la aplicación.

---

## 3. Los datos completos comienzan a partir de agosto

Durante el análisis temporal se observó que los registros comienzan a ser consistentes y completos a partir del 1 de agosto.

Por ello, el análisis principal se enfocó en ese periodo.

---

## 4. El experimento A/A validó la calidad de los grupos

Los grupos de control mostraron comportamientos similares, lo cual indicó que la división de usuarios fue correcta y el experimento era confiable.

---

## 5. El nuevo diseño no mostró diferencias significativas

Tras aplicar pruebas estadísticas, no se encontraron diferencias suficientemente significativas entre el grupo con el nuevo diseño y los grupos de control.

Esto indica que el cambio visual no tuvo un impacto considerable en la conversión de usuarios.

---

# Herramientas utilizadas

Durante el proyecto se utilizaron principalmente:

* Python
* Pandas
* NumPy
* Matplotlib
* SciPy
* Análisis estadístico
* Visualización de datos

---

# Resultados esperados del proyecto

Gracias al análisis realizado, la empresa puede:

* Comprender mejor el comportamiento de los usuarios.
* Detectar etapas críticas del embudo de ventas.
* Optimizar la experiencia de usuario.
* Tomar decisiones basadas en datos.
* Evaluar cambios de diseño antes de implementarlos.

---

# Conclusión general

Este proyecto permitió analizar el comportamiento de los usuarios dentro de una aplicación mediante técnicas de análisis exploratorio, construcción de embudos de conversión y pruebas estadísticas.

Los resultados ayudaron a identificar puntos de abandono dentro del proceso de compra y evaluar objetivamente el impacto de cambios en la interfaz.

El análisis demuestra la importancia del uso de datos y experimentos controlados para mejorar productos digitales y optimizar la experiencia de usuario.
