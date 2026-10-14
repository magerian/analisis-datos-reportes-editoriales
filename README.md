# [Proyecto Estrella] Análisis Predictivo de Demanda, Reducción de Costos y Planificación de Impresión para la Dirección General

## 📌 Descripción del Proyecto
Este es el proyecto de mayor impacto financiero y estratégico de mi portafolio. Desarrolle un modelo predictivo de planificación de demanda (*Demand Planning*) para la Dirección General del sector editorial. El sistema consolida datos en tiempo real de múltiples subsistemas de ventas e inventarios físicos para proyectar con exactitud las tiradas de impresión necesarias a futuro. Esto permitió cumplir con las ventas presupuestadas eliminando por completo la sobreimpresión, optimizando la rentabilidad y evitando la saturación inútil del espacio volumétrico en los almacenes.

---

## 🚀 1. El Desafío del Negocio e Impacto Directivo
La Dirección operaba con una desconexión crítica entre los departamentos de Ventas, Producción y Logística. Las decisiones de impresión se tomaban bajo intuición o promedios simples, lo que generaba:
*   **Sobreimpresión masiva:** Capital de trabajo inmovilizado en libros de baja rotación.
*   **Costos de almacenamiento ocultos:** Ocupación inútil de espacio volumétrico (m³) preciado en el almacén.
*   **Fricción con las metas financieras:** Riesgo constante de no cubrir las ventas presupuestadas por falta de stock de títulos con alta demanda espontánea.

Este proyecto unificó los sistemas de la compañía, convirtiéndose en la herramienta principal de control presupuestario y operativo para la Alta Gerencia.

---

## 🛠️ 2. Arquitectura de Datos y Enfoque Técnico
*   **Integración de Subsistemas Complejos:** Consolidación de flujos de "datos vivos" con diferentes granularidades temporales (métricas de ventas semanales para tendencias cortas, mensuales para estacionalidad y anuales para comportamiento histórico).
*   **Análisis de Inventario Real:** Cruce automatizado de existencias físicas actuales para calcular el stock neto necesario antes de mandar a producción.
*   **Modelado Predictivo de Tiradas:** Algoritmo lógico de proyección enfocado en la optimización del suministro (*Supply Chain Forecasting*) ajustado a las metas comerciales de la empresa.

---

## 📊 3. Metodología Analítica Implementada

### Fase 1: Sincronización e Ingesta de Datos Vivos
*   Extracción y normalización de datos procedentes de los subsistemas de facturación y puntos de venta.
*   Tratamiento de series temporales para identificar picos de demanda según épocas del año (estacionalidad editorial).

### Fase 2: Desarrollo del Algoritmo de Proyección
*   Diseño de la matriz de decisión: `[Venta Presupuestada Futura] - [Stock Real Neto] + [Margen de Seguridad de Seguridad Volumétrica] = [Tirada de Impresión Óptima]`.
*   Monitoreo del espacio físico: Restricción del modelo analítico basada en el volumen físico disponible en almacén para asegurar que la producción fuera sustentable en el espacio físico.

### Fase 3: Reportes de Control Directivo
*   Visualización de los escenarios de producción idóneos frente a los costos de impresión para que la Dirección General aprobara presupuestos con base científica.

---

## 📈 4. Resultados Financieros y Operativos Logrados
*   **Cero Sobreimpresión:** Eliminación total del gasto innecesario en papel, tinta y talleres de impresión por títulos excedentes.
*   **Eficiencia de Almacenamiento Sostenible:** Liberación y optimización del espacio volumétrico, asegurando que el almacén nunca se quede sin capacidad de maniobra.
*   **Cumplimiento del Presupuesto Comercial:** Garantía absoluta de disponibilidad de stock para alcanzar las metas de ventas proyectadas por la Dirección, maximizando la rentabilidad neta del catálogo.
*   **Transformación Cultural:** Migración de una gestión basada en corazonadas a una cultura corporativa 100% impulsada por datos (*Data-Driven*).

