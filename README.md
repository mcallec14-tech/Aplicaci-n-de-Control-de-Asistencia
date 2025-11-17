# Aplicaci-n-de-Control-de-Asistencia
Documentación De Aplicación de Control de Asistencia En GITHUB
Documento de requerimientos funcionales y no funcionales.
 
 1.Documento de requerimientos funcionales y no funcionales

 2.Tabla o plan de pruebas funcionales (minimo 3 casos de prueba con resultado esperado y validacion).
 
 3.Propuesta de mantenimiento correctivo,adaptativo o perfectivo.

## Descripción del Sistema
La *Aplicación de Control de Asistencia* es un sistema diseñado para registrar, gestionar y monitorear la presencia de usuarios (empleados, estudiantes u otros) dentro de una institución. Su propósito es automatizar el proceso de asistencia, reducir errores manuales y generar reportes confiables en tiempo real.  

### Funcionalidades principales
- Registro de entrada/salida mediante credenciales, códigos QR, huella digital o geolocalización.  
- Panel administrativo para estadísticas, reportes y configuración de horarios.  
- Alertas por ausencias, retardos o incumplimientos.  
- Integración con nómina o sistemas académicos.  
- Acceso multiusuario con diferentes roles.  

### Beneficios
- Mejora la puntualidad.  
- Reduce procesos manuales.  
- Facilita auditorías internas.  
- Aumenta la transparencia del registro de tiempo.  

---

## Objetivos del Proyecto

### Objetivo General
Desarrollar y analizar un sistema digital de control de asistencia que permita optimizar la gestión institucional mediante registros confiables, automatización y mejora continua.

### Objetivos Específicos
- Identificar problemas de los sistemas manuales actuales.  
- Definir requerimientos funcionales y no funcionales.  
- Evaluar riesgos y necesidades del sistema.  
- Aplicar conceptos de mantenimiento de software.  
- Proponer un cambio funcional innovador.  

---

##  Requerimientos del Sistema

### Requerimientos Funcionales
| Código | Funcionalidad | Propósito |
|--------|---------------|-----------|
| *RF01* | Registro de asistencia | Facilitar el control diario del docente. |
| *RF02* | Consulta de historial | Brindar seguimiento y transparencia. |
| *RF03* | Generación de reportes | Automatizar informes mensuales. |
| *RF04* | Autenticación de usuarios | Control de accesos y seguridad. |
| *RF05* | Notificaciones por inasistencias | Alertar sobre ausencias repetidas. |

###  Requerimientos No Funcionales
- Tiempo de respuesta < 5 segundos.  
- Disponibilidad 100%.  
- Cumplimiento con protección de datos.  
- Accesibilidad para usuarios con discapacidad visual.  

---

##  Análisis del Problema

### Problemas del sistema actual
- Procesos manuales propensos a errores.  
- Falta de trazabilidad y reportes confiables.  
- Dificultad en detectar inasistencias recurrentes.  

### Necesidad del sistema
- Registro rápido y seguro.  
- Historial accesible por estudiantes y docentes.  
- Alertas automáticas ante patrones de falta.  

### Actores involucrados
- Docentes  
- Estudiantes  
- Administradores académicos  

---

##  Tabla de Pruebas (Plan de Verificación)

| ID | Prueba | Requerimiento | Resultado Esperado |
|----|--------|----------------|--------------------|
| TP01 | Registro diario | RF01 | Entrada y salida registradas correctamente |
| TP02 | Consulta histórica | RF02 | Historial accesible sin errores |
| TP03 | Reportes mensuales | RF03 | Generación automática de informes |
| TP04 | Autenticación | RF04 | Acceso seguro con credenciales válidas |
| TP05 | Notificaciones | RF05 | Alerta solo cuando corresponde |

---

## Tipos de Mantenimiento Aplicables

###  *Mantenimiento Correctivo*
Corregir fallos de programación, diseño o funcionamiento.  
*Ejemplo:* error al registrar la hora de entrada o cálculo incorrecto de horas.  

###  *Mantenimiento Preventivo*
Evitar errores futuros mediante optimización del código y rendimiento.  
*Ejemplo:* refactorización y mejoras antes de fallos críticos.  

###  *Mantenimiento Perfectivo*
Agregar funciones o mejorar características actuales.  
*Ejemplo:* nuevo módulo de reportes automáticos.  

###  *Mantenimiento Adaptativo*
Ajustar el sistema a cambios de entorno, normas o plataformas.  
*Ejemplo:* compatibilidad con nuevas versiones de Android o Windows.  

---

##  Cambio Funcional Propuesto  
### *RF06 — Implementación de Reconocimiento Facial para Registro de Asistencia*

### Descripción Técnica
Integración de un módulo de reconocimiento facial mediante algoritmos de visión por computadora, permitiendo registro automático de asistencia mediante la cámara frontal.  

### Objetivos
- Aumentar precisión y velocidad.  
- Evitar suplantación de identidad.  
- Modernizar los métodos de marcación.

### Impacto Técnico y Operativo
- Requiere optimización para mantener tiempos < 5 segundos.  
- Implica gestión segura de datos biométricos.  
- Puede necesitar infraestructura adicional (nube / GPU).  
- Mejora la experiencia del usuario con registro sin contacto.  

---

##  Reflexión Final
La implementación de un sistema de control de asistencia representa una mejora significativa en la gestión institucional, permitiendo mayor eficiencia, precisión y transparencia. La propuesta de reconocimiento facial no solo moderniza el sistema, sino que refuerza la seguridad y simplifica el proceso para los usuarios.  
La clave del éxito está en acompañar estas innovaciones con pruebas rigurosas, una arquitectura sólida y una política adecuada de protección de datos.
