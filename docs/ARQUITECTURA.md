# Arquitectura funcional inicial

**Estado:** BORRADOR. **Versión:** 0.1.0.

## Componentes propuestos

1. Portal público: presentación institucional, áreas de MANA y convocatoria de proyectos.
2. Banco de proyectos: registro, clasificación, filtros, etapas y trazabilidad.
3. CRM: aliados, organizaciones, inversionistas y contactos, con permisos y consentimiento.
4. Gestión de expedientes: documentos oficiales almacenados en OneDrive y referenciados por identificadores controlados.
5. Panel de gestión: hitos, presupuestos, riesgos e indicadores de impacto.
6. Automatizaciones: revisión humana y registro verificable de las acciones.

## Roles iniciales

Administrador, gestor de proyectos, revisor jurídico-financiero, aliado y usuario externo. Los accesos deben responder al mínimo privilegio.

## Flujo del proyecto

IDEA → FORMULACIÓN → VIABILIDAD → ESTRUCTURACIÓN → FINANCIACIÓN → EJECUCIÓN → EVALUACIÓN.

## Límites

GitHub no sustituye a OneDrive ni es base de datos para expedientes o contactos. La financiación y promoción de inversiones exigen evaluación normativa antes de habilitar transacciones o captación de recursos.

## Próximos controles

- Definir arquitectura técnica y stack antes de escribir código de producción.
- Configurar entornos separados para desarrollo y producción.
- Incorporar pruebas, revisión de seguridad, autorización de publicación y bitácora de versiones.
