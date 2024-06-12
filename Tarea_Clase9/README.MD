## Gestor de Tareas
Este es un simple gestor de tareas desarrollado en Python utilizando programación orientada a objetos (POO). El gestor permite al usuario crear, eliminar y listar tareas, con la capacidad de manejar dos tipos de tareas diferentes: tareas generales y tareas con fecha de vencimiento.

#### Funcionalidades
- Agregar Tarea: Permite al usuario agregar una nueva tarea al gestor.
- Eliminar Tarea: Permite al usuario eliminar una tarea existente del gestor.
- Listar Tareas: Muestra al usuario todas las tareas almacenadas en el gestor, con sus respectivos detalles.
#### Estructura del Proyecto
El proyecto consta de los siguientes archivos:

- gestor_tareas.py: Contiene la implementación del gestor de tareas y las clases relacionadas.
- README.md: Este archivo que proporciona información sobre el proyecto.
### Clases
#### TareaGeneral
Representa una tarea simple con un nombre, descripción y prioridad.

##### Atributos:
- nombre: El nombre de la tarea.
- descripcion: La descripción de la tarea.
- prioridad: La prioridad de la tarea (alta, media, baja).
##### TareaConFecha
Extiende la clase TareaGeneral para incluir una fecha de vencimiento adicional.

##### Atributos Adicionales:
- fecha: La fecha de vencimiento de la tarea.
ListaTareas
Administra una lista de tareas, permitiendo operaciones como agregar, eliminar y listar tareas.

#### Métodos:
- agregar_tarea(tarea): Agrega una tarea a la lista.
- eliminar_tarea(nombre): Elimina una tarea por su nombre de la lista.
- listar_tareas(): Muestra todas las tareas almacenadas en la lista.
#### Uso
Para utilizar el gestor de tareas, simplemente ejecuta el archivo gestor_tareas.py en un entorno de Python. El programa te guiará a través de las diferentes opciones disponibles para gestionar tus tareas.


`python Tarea Oralidad Programación II.ipynb`

Este README proporciona una visión general del proyecto, incluyendo su funcionalidad, estructura y cómo utilizarlo. Puedes personalizarlo según tus necesidades y agregar más detalles según sea necesario.