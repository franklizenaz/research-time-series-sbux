# ANEXO B: Diccionario de Shock Externos 
**Proyecto:** Análisis Predictivo y Caracterización de Serie de Tiempo mediante Modelo SARIMA aplicado a Starbucks Corporation (SBUX)
**Investigador:** Frankli Zeña Zeña
**Institución:** Universidad Nacional de Ingeniería (UNI) - FIEECS

---
## 1. LISTADO DE DUMMIES (para SARIMAX)

### Estructurales (intervención permanente)
- choque_estructural → cambios de CEO
- restructuracion → cambios estratégicos corporativos
- plan_estrategico

### Mercado financiero
- earnings
- revision_analistas
- riesgo_credito
- politica_capital
- politica_accionista
- activismo

### Competencia
- competencia_global
- competencia_qsr
- competencia_precio
- competencia_retail
- competencia_b2b
- guerra_precios

### Macroeconómicos / costos
- shock_costos
- riesgo_pais
- shock_operativo

### Demanda y reputación
- shock_laboral
- shock_reputacional
- confianza_institucional

### Estacionalidad
- estacionalidad_verano
- estacionalidad_navidad

### Innovación
- innovacion_operativa

### Eventos extremos
- shock_extremo


## 2. Análisis de Uso

5 variables exógenas (óptimo empírico)

- choque_estructural
- shock_extremo
- earnings
- riesgo_pais
- shock_costos