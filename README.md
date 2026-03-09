# ConnectaTel
Evaluacion del comportamiento de los clientes de ConnectaTel en latinoamerica.

Análisis de Comportamiento del Cliente: ConnectaTel 📊📞


Este proyecto desempeña el rol de un Analista de Datos para evaluar el comportamiento de los clientes de ConnectaTel, una empresa de telecomunicaciones en Latinoamérica. El objetivo es transformar datos brutos en insights estratégicos para mejorar la retención y optimizar la oferta comercial.


🎯 Objetivo del Proyecto

Analizar los patrones de consumo de los clientes registrados hasta el año 2024 para:
Construir un perfil estadístico detallado de los usuarios.
Detectar anomalías y problemas de calidad en los datos.
Segmentar a los clientes según su uso y demografía.
Proponer mejoras en los planes actuales basadas en datos reales.


📂 Datasets Utilizados

El análisis se basa en tres fuentes de datos principales:
plans.csv: Detalles de la oferta comercial (precios, límites de minutos/GB y costos por excedentes).
users.csv: Información demográfica (edad, ciudad, fecha de registro y estatus de abandono).
usage.csv: Registro transaccional del uso real de servicios (duración de llamadas y longitud de mensajes).


🛠️ Etapas del Análisis

El flujo de trabajo seguido en el notebook se divide en:
Exploración Inicial (EDA): Identificación de estructuras, tipos de datos y primeras estadísticas descriptivas.
Limpieza de Datos: * Tratamiento de valores "sentinel" (ej. edades de -999).
Corrección de errores de sistema (fechas de registro en el futuro).
Gestión de valores nulos estructurales (datos faltantes por tipo de servicio).
Análisis Estadístico: Evaluación de promedios de consumo, distribución por ciudades y perfil de edad.
Segmentación: Agrupación de usuarios por plan y niveles de excedentes.
Generación de Insights: Conclusiones estratégicas y recomendaciones de negocio.


🚀 Cómo ejecutar el Notebook

Puedes ejecutar este análisis de forma interactiva siguiendo estos pasos:

Opción A: Google Colab (Recomendado)
Ve a Google Colab.

Haz clic en Archivo > Subir bloc de notas y selecciona el archivo .ipynb.

Asegúrate de subir los archivos .csv a la sección de "Archivos" (ícono de carpeta a la izquierda) para que el código pueda leerlos.

📋 Guía de Reproducción
Para obtener los mismos resultados presentados en el informe ejecutivo:

Carga los datos: Asegúrate de que los nombres de los archivos coincidan exactamente con las llamadas en el código (users.csv, plans.csv, usage.csv).

Ejecución Secuencial: No saltes las celdas de limpieza de datos, ya que los cálculos posteriores dependen de la eliminación de los valores atípicos (como el año 2026 o la edad -999).

Visualizaciones: Las gráficas de distribución (histogramas y boxplots) se generarán automáticamente para validar visualmente la limpieza realizada.
