# Actividad Hacker Women.

## Analisis y Planificacion del Pentest (Caso Aurora Market)

### Objetivo del Pentest.

1. Identificar posibles vulnerabilidades de seguridad en la Aplicacion Web de Aurora Market que pueden ser aprovechadas por el atacante y comprometer la confidencialidad, Integridad o disponibilidad de la informacion.

2. Evaluar el Nivel de Riesgo de las Vulnerabilidades identificadas, considerando la probabilidad de Explotacion y el impacto que podrian generar sobre la informacion y las operaciones de Aurora Market.

3. Proponer Medidas de Mitigacion y recomendaciones sde seguridad para las vulnerabilidades identificadas priorizando aquello que representa un mayor riesgo para Aurora Market.

### Alcance

* Si se Evaluara:
Aurora Market solo indico que se evaluara unicamente la aplicacion Web.
Las Funcionalidades accesibles para los Usuarios y los mecanismos de Autenticacion y control de acceso asociados a la aplicacion.

* Fuera del Alcance:
Sistemas o servidores internos que no hayan sido expresamente autorizados.
Equipos Personales o Corporativos de lOS Empleados.
Correos Electronicos y otros servicios corporativos ajenos a la Aplicacion evaluada.
Cualquier Infraestructura o Activo de terceros que no forme parte de Aurora Market.

### Autorizacion y Condiciones

* Permisos Requeridos:
Antes de iniciar el Pentest se debe contar con una autorizacion Formal por escrito de Aurora Market en la que se establezca el Alcance, las actividades permitidas, las restricciones y las condiciones de Evaluacion.

* Condiciones Acordadas:
No interrumpir el servico ni afectar la disponibilidad de la aplicacion.
No modificar ni eliminar informacion Real de los Clientes.
Realizar las pruebas preferiblemente en horarios de menor actividad para reducir el impacto sobre las operaciones.
Comunicar inmediatamente a Aurora Market cualquier Vulnerabilidad o hallazgo critico identificado.

### Tipo de Pentest.

Gray-Box:

 Ya que el equipo dispone de informacion limitada sobre el entorno de Aurora Market.solo se conoce la existencia de la aplicacion Web, la base de Datos y un mecanismo de autenticacion y diferentes tipos de usuarios pero no cuenta con todos los detalles tecnicos de infraestructura.

### Planificacion

* Objetivo:
Evaluar la Seguridad de la aplicacion Web Aurora Market mediante la identificacion de Vulnerabilidades, el analisis de los Riesgos asociados y la propuesta de medidas de Mitigacion.

* Alcance:
La evaluacion se limitara exclusivamente a la aplicacion Web y a los componentes expresamente autorizados por Aurora Market, cualquier sistema o servicio no autorizado quedara fuera del alcance.

* Permisos y condiciones:
se contara con una autorizacion Formal antes de iniciar las pruebas.Se respetan las condiciones establecidas por Aurora Market de no interrumpir el servicio, no modificar ni eliminar la informacion real de los clientes,evitar afectar la disponibilidad y comunicar inmediatamente cualquier hallazgo critico.

* Metodologia:
se seguira una metodologia estructurada de pentesting como OWASP que permitira realizar la evaluacion de forma organizada y sistematica facilitando la identificacion, analisi y documentacion de las vulnerabilidades encontradas OWASP WSTG es la mas indicada para analizar Aplicacion Web.


* Recopilacion de informacion Previa:
Se analizara la informacion disponible sobre la aplicacion Web para comprender su funcionamiento, identificar posibles areas de interes y estructurar las pruebas necesarias para cumplir los obajetivos establecidos.

* Recursos Necesarios:
Se requerira un equipo de trabajo, Herramientas de analisis de seguridad como Burp suite, OWASP ZAP Y Nmap.Un Acceso autorizado y cuentas de pruebas proporcionadas por Aurora Market, Documentacion de autorizacion Formal y alcance y tiempo para realizar las pruebas y un canal de comunicacion con la Empresa.


* Programacion del Pentest:
Se establecen previamente la duracion y horarios de las pruebas Aurora Market hace enfasis en que sea en un horario de menor actividad para minimizar impactos sobre las operaciones y sus usuarios.


### Fases del Pentest.

* Reconocimiento: 
Se recopila informacion sobre la aplicacion Web de Aurora Market para conocer el entorno, identificar funcionalidad y posibles puntos de entrada, siempre respetando el alcance establecido.

* Analisis de Vulnerabilidades: 
Se Analizan los componentes y funcionalidades identificadas durante el reconocimiento para detectar posibles debilidades de seguridad que pueden representarun Riesgo para Aurora Market.Revisamos Autenticacion, controles de acceso, configuraciones expuestas de la aplicacion siempre dentro del alcance establecido.

* Explotacion:
Aqui se comprueba de forma controlada si las vulnerabilidades identificadas pueden ser explotadas respetando en todo momento el 
alcance y las condiciones establecidas por Aurora Market, sin modificar informacion Real y sin interrumpir el servicio mi afectar la disponibilidad de la aplicacion.

* Post- Explotacion:
Se analizara el Nivel de Acceso obtenido y el posible impacto de las vulnerabilidades explotadas respetando el limite establecido sin afectar las operaciones de la organizacion.

* Informe:
Se documentaran las vulnerabilidades identificadas las evidencias obtenidas, su nivel de riesgo e impacto asi como las recomendaciones para su Mitigacion. Este informe servira como Registro de la evaluacion realizada y permitira al equipo de Aurora Market tomas las medidas necesarias para mejorar la seguridad de la aplicacion.


### Investigacion.

Aqui debemos usar una metodologia que nos proporcione una estructura para saber que areas revisar y como organizar las pruebas evitando trabajar de manera improvisada.

Para este Caso de Aurora Market usaremos OWASP web security testing Guide (WSTG) la cual resulta ser la mas adecuada para este proyecto porque la aplicacion Web es el objetivo principal de la evaluacion y nos permite realizar pruebas de manera estructurada, sistematica y ordenada abarcando diferentes areas de seguridad como autenticacion, autorizacion, gestion de sesiones y validacion de entradas.

Su utilizacion ayudara a organizar las pruebas, reducir la posibilidad de omitir aspectos importantes y documentar adecuadamente los hallazgos obtenidos durante el Pentest.



