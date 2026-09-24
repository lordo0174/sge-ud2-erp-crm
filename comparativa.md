# Comparativa ERP-CRM

## 1. Datos

- **Propietario:** lordo0174
- **Empresa:** 29 - TecnoAyuda
- **Palabra del día:** chorizo

## 2. Licencias y modelos

### Software libre

El software libre permite al usuario utilizar, estudiar, modificar y compartir el programa. Estas libertades están garantizadas por la licencia del software.

### Código abierto (Open Source)

El código abierto permite acceder al código fuente del programa y modificarlo y distribuirlo según las condiciones de su licencia. La Open Source Initiative (OSI) establece los criterios que deben cumplir las licencias para considerarse de código abierto.

### Software propietario

El software propietario es aquel cuyo uso, modificación y distribución están controlados por su propietario mediante una licencia. Normalmente, el usuario no tiene acceso al código fuente ni permiso para modificarlo libremente.

### Libre no significa gratuito

Que un software sea libre no significa que tenga que ser gratuito. El término "libre" hace referencia a las libertades que tiene el usuario sobre el software, no a su precio. Una empresa puede cobrar por la instalación, configuración, soporte, mantenimiento, alojamiento u otros servicios relacionados con un programa libre.

### Community frente a Enterprise

Una edición Community suele ofrecer las funcionalidades principales del producto y está orientada a usuarios que necesitan una solución con menos servicios o funcionalidades empresariales adicionales. Una edición Enterprise suele ser una versión comercial que incorpora funcionalidades adicionales, servicios de soporte y otras prestaciones destinadas a empresas, normalmente mediante una suscripción o licencia de pago.


## 3. Fichas técnicas

### 3.1 Odoo Community

- **Tipo:** ERP libre y de código abierto.
- **Licencia:** GNU LGPLv3.
- **Versión vigente consultada:** Odoo 19.
- **Lenguaje del servidor:** Python.
- **SGBD compatible:** PostgreSQL 13 o superior.
- **Modalidad:** instalación local (on-premise), Odoo.sh y Odoo Online. La edición Community puede instalarse desde el código fuente.
- **Módulos principales:** CRM, Ventas, Contabilidad y Facturación, Inventario, Compras, Fabricación, Punto de Venta, Sitio web, Comercio electrónico, Recursos Humanos, Marketing y Servicio de asistencia.
- **Requisitos principales:** Python 3.10 o superior y PostgreSQL 13 o superior. Las dependencias de Python se encuentran en el archivo `requirements.txt`.
- **Fuentes oficiales:**https://www.odoo.com/documentation/19.0/legal/licenses.html https://www.odoo.com/documentation/19.0/es/administration/on_premise https://www.odoo.com/documentation/19.0/es/applications.html
- **Fecha de consulta:** 24/09/2026.

### 3.2 Microsoft Dynamics 365 Finance

- **Tipo:** ERP propietario y comercial.
- **Licencia:** licencia comercial mediante suscripción de Microsoft Dynamics 365.
- **Versión vigente consultada:** Dynamics 365 Finance 10.0.49, con actualización automática disponible en septiembre de 2026.
- **Lenguaje del servidor:** X++, utilizado para desarrollar y personalizar la lógica de las aplicaciones Finance and Operations. X++ se compila en Microsoft .NET CIL.
- **SGBD:** Azure SQL Database en los entornos cloud administrados por Microsoft. En determinados escenarios también se utiliza Microsoft SQL Server.
- **Modalidad:** principalmente cloud mediante Microsoft Azure; también existen opciones de despliegue on-premises para determinados escenarios de Finance and Operations.
- **Módulos principales:** contabilidad general, cuentas por pagar, cuentas por cobrar, presupuestos, gestión de efectivo y bancos, contabilidad de costes, activos fijos y otros procesos financieros y empresariales.
- **Requisitos principales:** suscripción/licencia de Dynamics 365, acceso a Internet y un entorno compatible con Microsoft Azure. Para desarrollo y personalización se utiliza Visual Studio y las herramientas de Finance and Operations.
- **Fuentes oficiales:** https://learn.microsoft.com/en-us/dynamics365/finance/get-started/whats-new-home-page https://learn.microsoft.com/en-us/dynamics365/fin-ops-core/dev-itpro/dev-ref/xpp-language-reference https://learn.microsoft.com/en-us/dynamics365/fin-ops-core/dev-itpro/deployment/cloud-deployment-overview
- **Fecha de consulta:** 24/09/2026.

### 3.3 SuiteCRM

- **Tipo:** CRM libre y de código abierto.
- **Licencia:** GNU AGPLv3.
- **Versión vigente consultada:** SuiteCRM 8.10.2.
- **Lenguaje del servidor:** PHP.
- **SGBD compatibles:** MariaDB y MySQL.
- **Modalidad:** instalación local/on-premise. También puede desplegarse en un servidor o infraestructura cloud propia.
- **Módulos principales:** Cuentas, Contactos, Clientes potenciales, Oportunidades, Calendario, Llamadas, Reuniones, Tareas, Documentos, Campañas, Encuestas, Casos, Proyectos, Informes y gestión de incidencias.
- **Requisitos principales:** para SuiteCRM 8.10.x se requiere PHP 8.2, 8.3 o 8.4, servidor web Apache 2.4 y MariaDB o MySQL en las versiones compatibles indicadas por la matriz oficial.
- **Fuentes oficiales:** https://docs.suitecrm.com/8.x/admin/licensing https://docs.suitecrm.com/8.x/admin/releases/8.10
- **Fecha de consulta:** 24/09/2026.

### 3.4 Salesforce

- **Tipo:** CRM propietario y comercial.
- **Licencia:** software propietario ofrecido mediante planes y suscripciones comerciales de Salesforce.
- **Versión vigente consultada:** Salesforce Winter '27.
- **Lenguaje del servidor:** Apex para desarrollar lógica del lado del servidor y personalizaciones sobre la plataforma Salesforce.
- **SGBD:** Salesforce utiliza una infraestructura de base de datos gestionada por Salesforce. El cliente no selecciona ni administra un SGBD tradicional para la aplicación. SalesforceDB forma parte de la infraestructura actual de la plataforma.
- **Modalidad:** servicio cloud/SaaS. La infraestructura de Salesforce se ejecuta actualmente sobre Hyperforce y servicios de nube pública.
- **Módulos principales:** Sales Cloud, Service Cloud, Marketing Cloud, Commerce Cloud, Agentforce y Data 360, además de herramientas de automatización, análisis e integración.
- **Requisitos principales:** conexión a Internet, navegador web compatible y una cuenta/licencia de Salesforce. La infraestructura y las bases de datos son gestionadas por Salesforce.
- **Fuentes oficiales:** https://www.salesforce.com/products/innovation/releases/?bc=OTH&d=7010M000002McDl https://developer.salesforce.com/docs/platform/aura-platform/guide/apex-intro.html
- **Fecha de consulta:** 24/09/2026.

## 4. Fe de erratas del tema 2

## 4. Fe de erratas del tema 2

### Errata 1: versión de Odoo

- **Qué dice el tema:** El tema indica que la versión actual de Odoo es la 14. También indica que el servidor utiliza Python 3.10 o posterior y PostgreSQL. 
- **Qué es correcto actualmente:** La documentación oficial actual corresponde a Odoo 19. Odoo 19 requiere Python 3.10 o posterior y utiliza PostgreSQL, siendo PostgreSQL 13 o superior la versión mínima compatible.
- **Fuente:** Documentación oficial de Odoo 19: https://www.odoo.com/documentation/19.0/es/administration/on_premise/source.html
- **Fecha de consulta:** 24/09/2026

### Errata 2: versión y bases de datos de SuiteCRM

- **Qué dice el tema:** El tema indica que SuiteCRM dispone de la versión 7.14.5 bajo licencia AGPL-3.0 y que puede funcionar con MySQL, MariaDB o SQL Server.
- **Qué es correcto actualmente:** La documentación oficial actual de SuiteCRM muestra la versión 8.10.2, publicada el 31 de julio de 2026. Para SuiteCRM 8.10.x, las bases de datos compatibles indicadas oficialmente son MariaDB 10.6, 10.11, 11.4 y 11.8, y MySQL 8.0 y 8.4. SQL Server no aparece en la matriz de compatibilidad actual.
- **Fuente:** Documentación oficial de SuiteCRM: https://docs.suitecrm.com/8.x/admin/releases/8.10/ y https://docs.suitecrm.com/8.x/admin/compatibility-matrix/
- **Fecha de consulta:** 24/09/2026

## 5. Matriz de decisión y 

## 5. Matriz de decisión

Para TecnoAyuda se han comparado tres soluciones: Odoo Community, SuiteCRM y Salesforce. La selección de los criterios se ha realizado teniendo en cuenta las necesidades de la empresa, especialmente la gestión centralizada de las incidencias de los 14 técnicos.

### Criterios y pesos

- **Gestión de incidencias: 30 %**
- **Gestión de clientes/CRM: 20 %**
- **Coste total (TCO): 20 %**
- **Personalización: 10 %**
- **Facilidad de implantación: 10 %**
- **Escalabilidad: 10 %**

Los pesos suman un total del 100 %.

### Puntuaciones

| Criterio | Peso | Odoo Community | SuiteCRM | Salesforce |
|---|---:|---:|---:|---:|
| Gestión de clientes/CRM | 20 | 4 | 5 | 5 |
| Gestión de incidencias | 30 | 2 | 5 | 5 |
| Coste total (TCO) | 20 | 5 | 5 | 2 |
| Personalización | 10 | 5 | 5 | 4 |
| Facilidad de implantación | 10 | 4 | 3 | 4 |
| Escalabilidad | 10 | 5 | 4 | 5 |
| **TOTAL PONDERADO** | **100** | **3,80** | **4,70** | **4,00** |

### Justificación de las puntuaciones

**Odoo Community**

- **Gestión de clientes/CRM: 4/5.** Odoo dispone de funcionalidades CRM para gestionar clientes, oportunidades y actividades.
- **Gestión de incidencias: 2/5.** Odoo dispone de una aplicación Helpdesk para la gestión de tickets, pero esta funcionalidad pertenece a la edición Enterprise. Por este motivo, la puntuación de Odoo Community es inferior.
- **Coste total: 5/5.** La edición Community es de código abierto y no requiere el pago de una licencia Enterprise, aunque pueden existir costes de instalación, alojamiento y mantenimiento.
- **Personalización: 5/5.** Al tratarse de software de código abierto, permite modificar y adaptar el sistema.
- **Facilidad de implantación: 4/5.** Odoo integra diferentes aplicaciones en una misma plataforma, aunque pueden ser necesarios módulos adicionales para cubrir todas las necesidades de TecnoAyuda.
- **Escalabilidad: 5/5.** La plataforma permite ampliar sus funcionalidades mediante diferentes aplicaciones.

**SuiteCRM**

- **Gestión de clientes/CRM: 5/5.** Es una solución CRM de código abierto orientada a la gestión de relaciones con clientes.
- **Gestión de incidencias: 5/5.** Dispone del módulo Cases, diseñado para registrar y gestionar solicitudes de soporte de los clientes.
- **Coste total: 5/5.** No requiere pagar licencias por usuario, aunque existen costes asociados al alojamiento, instalación, configuración y mantenimiento.
- **Personalización: 5/5.** Su carácter de código abierto permite adaptar el sistema a las necesidades de la empresa.
- **Facilidad de implantación: 3/5.** Su instalación requiere configurar servidor web, PHP y una base de datos, por lo que puede necesitar más trabajo técnico.
- **Escalabilidad: 4/5.** Puede crecer junto con la empresa, aunque una instalación propia requiere gestionar también la infraestructura.

**Salesforce**

- **Gestión de clientes/CRM: 5/5.** Salesforce es una plataforma CRM con funcionalidades específicas para gestionar clientes y relaciones comerciales.
- **Gestión de incidencias: 5/5.** Service Cloud incluye gestión de casos para registrar y resolver problemas de los clientes y permite trabajar con diferentes canales de atención.
- **Coste total: 2/5.** Utiliza un modelo de suscripción por usuario y las funcionalidades avanzadas pueden aumentar el coste para una empresa con varios técnicos.
- **Personalización: 4/5.** Permite una amplia configuración y personalización dentro de su plataforma.
- **Facilidad de implantación: 4/5.** Al ser una solución en la nube, no es necesario mantener directamente toda la infraestructura del servidor.
- **Escalabilidad: 5/5.** Permite ampliar usuarios, productos y funcionalidades según las necesidades de la empresa.

### Cálculo de las puntuaciones

La puntuación ponderada se obtiene multiplicando cada puntuación por el peso del criterio y dividiendo entre 100.

Por ejemplo, para SuiteCRM:

- Gestión de clientes/CRM: `5 × 20 / 100 = 1,00`
- Gestión de incidencias: `5 × 30 / 100 = 1,50`
- Coste total: `5 × 20 / 100 = 1,00`
- Personalización: `5 × 10 / 100 = 0,50`
- Facilidad de implantación: `3 × 10 / 100 = 0,30`
- Escalabilidad: `4 × 10 / 100 = 0,40`

**Total: 1,50 + 1,00 + 1,00 + 0,50 + 0,30 + 0,40 = 4,70**

### Recomendación para TecnoAyuda

Según los criterios y pesos establecidos para este caso, **SuiteCRM obtiene una puntuación ponderada de 4,70 sobre 5**. Su principal ventaja para TecnoAyuda es que dispone de funcionalidades específicas para gestionar incidencias mediante el módulo Cases y, además, permite trabajar con clientes y contactos.

Por estos motivos, se propone **SuiteCRM como solución candidata para TecnoAyuda**, teniendo en cuenta que la empresa tendría que asumir las tareas de instalación, configuración, mantenimiento y soporte técnico.

### Riesgos

- **TCO:** aunque no haya costes de licencia por usuario en SuiteCRM, hay que considerar los costes de servidores, alojamiento, mantenimiento, configuración y soporte.
- **Vendor lock-in:** al utilizar una solución de código abierto se puede reducir la dependencia de un único proveedor, aunque pueden existir dependencias respecto a la infraestructura, personal técnico o servicios contratados.
- **Soporte:** una instalación propia requiere disponer de conocimientos técnicos o contratar servicios de soporte.
- **Migración futura:** antes de implantar la solución se debe comprobar que los datos puedan exportarse correctamente para facilitar una futura migración a otro sistema.