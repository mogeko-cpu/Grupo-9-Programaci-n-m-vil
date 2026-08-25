# Planeación del prototipo integrado

> Este entregable debe estar acompañado por un prototipo realizado en Figma.
> En esta etapa se espera un prototipo de baja o media fidelidad que integre los flujos aprobados en la semana 3 y permita una validación más amplia.

## Información del equipo

**Nombre del equipo:** Grupo 9

**Integrantes:** Sebastián González Quintanilla, Kevin Ruiz Espitia, Alejandro Santiago Caballero, Leonel Triana Martínez


## Flujos que vamos a integrar

Escriban los flujos aprobados en la semana 3 que harán parte de este prototipo.

1. **Flujo 1 - Publicar y explorar ideas:** El usuario puede publicar su idea y explorar ideas de otros estudiantes.

2. **Flujo 2 - Unirse y formar equipo:** El usuario interesado en una idea puede solicitar unirse y el creador puede evaluar y aceptar solicitudes.

3. **Flujo 3 - Estructurar y gestionar el proyecto:** El equipo puede definir roles, tareas y fechas, y registrar avances.

4. **Flujo 4 - Recibir mentoría y conectar con aliados externos:** El equipo puede solicitar mentoría y conocer retos externos.


## Objetivo del prototipo

¿Qué quieren mostrar o comprobar al integrar estos flujos en un solo prototipo?

Queremos mostrar el viaje completo de un estudiante dentro del ecosistema de innovación: desde que descubre una idea, se une a un equipo, estructura el proyecto, y finalmente recibe acompañamiento. Queremos comprobar si la experiencia es fluida, si los usuarios entienden cómo avanzar de un flujo a otro, y si la integración entre flujos reduce la fricción que hoy existe en el proceso real.


## Alcance

¿Qué sí incluirá el prototipo?

1. Pantalla de inicio con lista de ideas destacadas y acceso a explorar.

2. Flujo completo de publicación de una idea (formulario básico).

3. Flujo de exploración de ideas con filtros y vista de detalle.

4. Flujo de solicitud de unión a un proyecto (con preguntas breves).

5. Flujo de gestión de solicitudes para el creador de la idea.

6. Espacio de trabajo del proyecto con miembros, tareas y avance.

7. Flujo de solicitud de mentoría (cuestionario guiado).

¿Qué no incluirá por ahora?

- Autenticación o registro de usuarios (asumimos que el usuario ya está logueado).

- Notificaciones en tiempo real.

- Integración con herramientas externas (Google Drive, etc.).

- Diseño visual final o sistema de colores pulido.

- Funcionalidades de edición o eliminación de contenido.

- Perfiles de usuario detallados.


## Pantallas, escenas o partes principales

Enumeren los elementos que van a construir y cómo se conectan entre sí.

1. **Pantalla de inicio:** Muestra ideas destacadas, acceso a "Explorar ideas" y "Publicar idea", y acceso al espacio de trabajo del proyecto.

2. **Explorar ideas:** Lista de ideas con filtros por categoría y estado. Al hacer clic, se abre la vista de detalle.

3. **Vista de detalle de idea:** Muestra título, descripción, creador, colaboradores necesarios. Botón "Quiero unirme" (Flujo 2) y "Guardar idea".

4. **Publicar idea (Flujo 1):** Formulario con título, descripción, categoría, habilidades requeridas. Botón "Publicar".

5. **Solicitud de unión (Flujo 2):** Cuestionario breve con 3 preguntas (motivación, habilidades, disponibilidad). Botón "Enviar solicitud".

6. **Panel de solicitudes (Flujo 2):** Lista de solicitudes recibidas por el creador con respuestas del cuestionario. Botones "Aceptar" o "Rechazar".

7. **Espacio de trabajo (Flujo 3):** Vista general del proyecto con resumen de miembros, tareas y avance. Tabs de navegación a "Miembros", "Tareas", "Archivos" y "Progreso".

8. **Gestión de tareas (Flujo 3):** Lista de tareas con estado, asignado y fecha. Botón "Agregar tarea" con formulario.

9. **Registro de avance (Flujo 3):** Modal con selector de tarea, porcentaje de avance y comentario.

10. **Solicitud de mentoría (Flujo 4):** Cuestionario guiado de 4 preguntas sobre el proyecto. Recomendación de mentores con perfiles y botón "Solicitar mentoría".

11. **Retos externos (Flujo 4):** Lista de retos planteados por aliados externos con descripción y botón "Tomar reto".


## Integración entre flujos

¿Cómo se conectan entre sí los flujos aprobados?

- **Flujo 1 → Flujo 2:** Desde la vista de detalle de una idea, el usuario puede iniciar el flujo de unión. El creador de la idea recibe las solicitudes en su panel.

- **Flujo 2 → Flujo 3:** Una vez que el creador acepta solicitudes y el equipo se forma, el espacio de trabajo del proyecto se activa automáticamente. Los miembros aceptados tienen acceso al espacio de trabajo.

- **Flujo 3 → Flujo 4:** Desde el espacio de trabajo, el equipo puede acceder a la sección de mentoría. El cuestionario de mentoría usa información del proyecto (categoría, etapa) para hacer recomendaciones más precisas.

- **Flujo 1 → Flujo 4:** Los retos externos se muestran como "ideas" especiales que los equipos pueden adoptar, conectando la exploración de ideas con la sección de aliados externos.


## Herramienta de trabajo

¿Cómo construirán el prototipo integrado?

**Herramienta esperada:** Figma

Si usan algún apoyo adicional, indíquenlo aquí:

- Componentes reutilizables para mantener consistencia entre pantallas.

- Wireframes de baja fidelidad para validar navegación antes de agregar detalle.

- Conexiones entre pantallas con interacciones básicas (click → navegar).


## Hipótesis a validar

¿Qué creen que sucederá cuando un usuario vea o use este prototipo?

- Los usuarios entenderán que la plataforma les permite publicar, explorar y unirse a ideas en un solo lugar.

- Los usuarios encontrarán natural la transición de "unirse a una idea" a "gestionar el proyecto".

- Los usuarios valorarán el cuestionario guiado para mentoría porque les da confianza al elegir.

- Los usuarios podrán completar el flujo completo sin ayuda externa.

- Los usuarios expresarán que "esto es lo que necesitaba" o "por qué no existía antes".