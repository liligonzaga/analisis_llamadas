# analisis_llamadas
Análisis predictivo de satisfacción del cliente mediante Big Data y modelos de Markov
1. Descripción del proyecto
La propuesta consiste en implementar una solución de Big Data para analizar, predecir y mejorar la satisfacción de los clientes a partir de los datos generados en las interacciones de atención y soporte. A diferencia de un enfoque tradicional centrado únicamente en tiempos de gestión, esta iniciativa incorpora análisis de satisfacción, identificación de factores que generan insatisfacción y modelos predictivos de comportamiento del cliente. 
Mediante el procesamiento de solicitudes, consultas, reclamaciones, tiempos de atención, niveles de satisfacción, sentimientos expresados por los clientes y factores asociados a cada interacción, se pretende identificar los elementos que incrementan la probabilidad de insatisfacción y priorizar acciones de mejora
________________________________________
2. Problema identificado
Actualmente, los procesos de atención al cliente generan una gran cantidad de información relacionada con solicitudes, quejas, reclamaciones y respuestas brindadas a los usuarios. Sin embargo, esa información suele utilizarse principalmente para fines operativos y no para comprender el comportamiento futuro de los clientes.  
El análisis desarrollado en el modelo de satisfacción evidenció que:
•	Las llamadas con drivers negativos están asociadas al 100 % con estados de insatisfacción. [
•	Los factores más frecuentes que generan insatisfacción son: 
o	calidad del producto,
o	soporte técnico,
o	tiempo de entrega,
o	comunicación con el cliente. 
•	La insatisfacción tiende a persistir entre interacciones sucesivas cuando los problemas de fondo no son corregidos. 
•	Las reclamaciones con alta urgencia presentan mayor riesgo de permanencia en estados de inconformidad. 
Esta situación puede ocasionar:
•	Aumento de reclamaciones repetitivas.
•	Mayor probabilidad de fuga de clientes.
•	Menor confianza en la organización.
•	Incremento de costos operativos por reprocesos.
•	Disminución de indicadores de experiencia del cliente. 
________________________________________
3. Objetivo general
Diseñar una solución analítica basada en Big Data que permita identificar los factores que impactan la satisfacción del cliente de EPM, predecir riesgos de insatisfacción futura y apoyar la toma de decisiones orientadas a mejorar la experiencia del usuario, reducir reclamaciones recurrentes y aumentar los niveles de satisfacción. 
________________________________________
4. Solución propuesta
Fase 1. Integración y preparación de datos
Consolidar información proveniente de:
•	Solicitudes y reclamaciones.
•	Históricos de atención.
•	Canales de contacto.
•	Tiempos de respuesta.
•	Resultados de gestión.
•	Encuestas de satisfacción.
•	Sentimientos identificados en la interacción. 
Fase 2. Identificación de drivers de satisfacción
Aplicar modelos analíticos para determinar cuáles factores tienen mayor impacto en satisfacción o insatisfacción.
Se identificaron como principales drivers negativos:
•	Calidad del producto.
•	Soporte técnico.
•	Tiempo de entrega.
•	Comunicación. 
•	Fase 3. Modelos predictivos de comportamiento
Implementar modelos de cadenas de Markov y probabilidades de transición para estimar cómo evolucionará el nivel de satisfacción de los clientes después de cada interacción. 
El análisis muestra que:
•	La insatisfacción posee una alta probabilidad de mantenerse cuando existen factores negativos persistentes.
•	Los escenarios con varios drivers negativos aumentan significativamente el porcentaje de clientes insatisfechos en el largo plazo. 
Fase 4. Visualización y toma de decisiones
Desarrollar tableros en Power BI para visualizar:
•	Nivel de satisfacción.
•	Principales causas de insatisfacción.
•	Riesgo de fuga.
•	Evolución del cliente entre estados de satisfacción.
•	Tendencias de comportamiento.
•	Indicadores de experiencia del cliente. 
________________________________________
5. Beneficios esperados
Beneficios cuantitativos
Beneficio	Meta estimada
Reducción de reclamaciones recurrentes	15 %
Disminución de casos asociados a drivers negativos	20 %
Incremento en satisfacción del cliente	10 %
Reducción de riesgo de abandono	10 %
Disminución de reprocesos operativos	10 %
Metas académicas sujetas a validación con datos reales. 
Beneficios cualitativos
•	Mayor comprensión de las expectativas del cliente.
•	Toma de decisiones basada en evidencia.
•	Mejor experiencia de usuario.
•	Identificación temprana de clientes en riesgo.
•	Fortalecimiento de la cultura de analítica de datos.
•	Priorización de acciones correctivas sobre causas reales de insatisfacción. 
________________________________________
6. Ejemplo del valor generado
El modelo identificó que los escenarios con múltiples factores negativos generan una concentración de clientes insatisfechos cercana al 36 % en el largo plazo, mientras que escenarios favorables reducen significativamente esa proporción. 
Esto significa que actuar sobre los principales drivers negativos puede evitar que los clientes permanezcan en estados de inconformidad y reducir el volumen de reclamaciones futuras.
Por ejemplo:
•	Mejorar soporte técnico.
•	Reducir tiempos de solución.
•	Optimizar comunicación.
•	Actuar rápidamente sobre reclamaciones críticas.
Estas acciones disminuyen la probabilidad de que un cliente insatisfecho continúe en ese estado durante futuras interacciones.  
________________________________________
7. Indicadores de éxito
Indicador	Cómo se mide	Meta
Nivel de satisfacción	% clientes satisfechos	Incrementar 10 %
Tasa de insatisfacción	% clientes insatisfechos	Reducir 10 %
Reclamaciones recurrentes	Casos repetidos	Reducir 15 %
Drivers negativos identificados y corregidos	Casos solucionados	Reducir 20 %
Riesgo de fuga	Clientes clasificados en riesgo	Reducir 10 %
Tiempo promedio de atención	Minutos por solicitud	Reducir 15 %
________________________________________
8. Recursos necesarios
Información requerida
•	Históricos de solicitudes.
•	Encuestas de satisfacción.
•	Tipología de contactos.
•	Información de tiempos de gestión.
•	Resultados de atención.
•	Factores o drivers asociados a cada interacción. 
Herramientas
•	Databricks para procesamiento Big Data.
•	Python para modelamiento.
•	Power BI para visualización.
•	Algoritmos de cadenas de Markov y análisis predictivo. 
________________________________________
9. Conclusión
La propuesta permite evolucionar desde un modelo reactivo de atención al cliente hacia un modelo predictivo basado en datos. Mientras el caso inicial se enfocaba en reducir tiempos de gestión, esta versión incorpora un análisis avanzado de satisfacción capaz de identificar las causas reales de insatisfacción, anticipar comportamientos futuros y priorizar acciones de mejora que incrementen la experiencia del cliente. 
El principal valor para EPM es que podrá utilizar la información generada por la operación para prevenir la insatisfacción y no solamente reaccionar ante ella, mejorando simultáneamente productividad, calidad del servicio y fidelización de clientes. 
A continuación, se relaciona el Dashboards
https://dbc-f2045280-f5ce.cloud.databricks.com/dashboardsv3/01f1e2098e711a5da16391e184f98c99/published?o=7474652144134355
