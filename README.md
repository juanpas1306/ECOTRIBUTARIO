# ECOTRIBUTARIO

Este software permitirá a las empresas registrar y reportar sus acciones ambientales, otorgándoles una reducción en impuestos en función de sus contribuciones al medio ambiente.

# objetivos : 
Fomentar la adopción de prácticas ambientales sostenibles en las empresas.

agilizar el proceso para calcular valores fiscales basados en acciones ambientales.

Brindar un sistema seguro y escalable para la gestión de información empresarial.


# REQUISITOS FUNCIONALES 
Registro de Empresas: Las empresas deben poder registrarse con su información fiscal y ambiental.

Carga de Evidencias: Las empresas podrán subir documentos, imágenes o reportes sobre sus acciones ambientales.

Cálculo de Reducción Fiscal: El sistema calculará automáticamente el descuento de impuestos en función de criterios ambientales.

Generación de Reportes: Se generarán informes detallados sobre el impacto ambiental de las empresas y los incentivos obtenidos.

Panel de Administración: Un administrador podrá validar la información y aprobar los beneficios fiscales.

Historial de Acciones: Las empresas podrán ver el historial de acciones ambientales registradas.

Notificaciones: Se enviarán alertas sobre fechas de reporte y aprobaciones de incentivos.

# Requisitos No Funcionales

Escalabilidad: El sistema debe manejar múltiples empresas sin pérdida de rendimiento.

Seguridad: Los datos fiscales y ambientales deben estar protegidos.

Compatibilidad: Debe ser accesible desde navegadores modernos 

Usabilidad: La interfaz debe ser intuitiva y fácil de usar para empresas y administradores.

# Modelo de Base de Datos

Tablas principales:

Empresas (id, nombre, NIT, contacto, sector)

AccionesAmbientales (id, empresa_id, tipo, cantidad, fecha, evidencia)

DescuentosFiscales (id, empresa_id, monto_descuento, año)

# Arquitectura del Sistema 
------------------------

# CRITERIOS DE EVALUACION
Este sistema asignará descuentos fiscales según el impacto ambiental generado por las acciones de la empresa. La reducción fiscal se calculará en función de los siguientes criterios:

Acción Ambiental     Unidad de Medida       Reducción Fiscal (%)
Reciclaje de plástico  kg reciclados       0.5% por cada 100 kg

Manejo de aguas residuales  m³ tratados     1% por cada 500 m³

Inversión en energías       USD invertidos           2% por cada $10,000
renovables                    

Programas de reforestación    árboles plantados  0.75% por cada 1,000 árboles
