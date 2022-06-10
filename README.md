#
# **Desafío WordPress**

En este desafío, creará un plugin para WordPress que añada el shortcode [todolist max\_items=10 allow\_delete=true], el cuál muestra una lista de tareas.

![alt text](https://github.com/newcombin/devskillsWPAdv/blob/main/template.png "Diseño web")

\* El diseño es sólo ilustrativo, puedes personalizarlo a gusto.

## **Contexto**

Se desea mostrar una lista de tareas dinámica en la que se pueda agregar, eliminar o marcar como completada diferentes tareas.

Pueden existir múltiples tareas con el mismo nombre.

## **Requisitos**

**Estructura:**

- Debe tener un título &quot;To Do List&quot;
- Debe mostrar un input y un botón para añadir tareas
- Las nuevas tareas se deben agregar al principio de la lista

**Tarea:**

- Un tarea consiste en un checkbox, un título y un botón para eliminarla
- Cada tarea se puede marcar como completada o desmarcar las veces que se quiera
- Cada vez que una tarea se marca como completada el texto debe tacharse
- Cuando se elimina una tarea esta desaparece de la lista

**Técnicos:**

- Puede crear un plugin desde cero o utilizar un boilerplate si lo prefiere
- Debe crear un Custom Post Type que almacene estas tareas y permita administrarlas desde el área administrativa de WordPress
- Sólo mostrar la lista de tareas a usuarios logueados
- Las tareas se asignan al usuario logueado que la crea
- El usuario logueado sólo ve sus tareas en frontend
- Debe utilizar ajax para agregar, eliminar o marcar como completadas las tareas, de forma que no sea necesario recargar la página
- Al cargar la página las tareas completadas deben estar tachadas y el checkbox marcado
- Para las funcionalidades Javascript puede usar jQuery, aunque se prefiere Vanilla JavaScript.
- Agregar parámetros opcionales de configuración al shortcode [todolist max\_items=10 allow\_delete=true].
**max\_items** para filtrar el número máximo de tareas que se pueden agregar (por defecto sin límite)
**allow\_delete** para permitir o no eliminar tareas (por defecto no se permite)
- Agregar soporte multi-idioma para español e inglés
- Agregar una columna en el administrador de WordPress para identificar si la tarea está completada o no

**Entrega**

- Crear un archivo README.md para indicar como se debe utilizar el plugin
- Subir a un repositorio git con privilegios públicos de lectura y compartir el link
