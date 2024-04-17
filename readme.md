
# Descripción

Este es un simple administrador de tareas construido con JavaScript puro. Permite a los usuarios agregar nuevas tareas, marcarlas como completadas y eliminarlas.

## Funcionalidades

- Agregar nuevas tareas
- Marcar tareas como completadas
- Eliminar tareas
- Persistencia de datos utilizando `localStorage`

## Instrucciones de Uso

1. Clona o descarga este repositorio en tu máquina local.
2. Abre el archivo `index.html` en tu navegador web.
3. Utiliza el formulario para agregar nuevas tareas.
4. Marca las tareas como completadas haciendo clic en la casilla de verificación junto a ellas.
5. Haz clic en el botón "Limpiar Tareas Completadas" para eliminar las tareas marcadas como completadas.

## Estructura del Código

El código se organiza en dos archivos principales:

### `main.js`

Este archivo contiene la lógica principal de la aplicación, incluyendo la gestión de tareas, el manejo de eventos y la persistencia de datos mediante `localStorage`.

### `createTaskLi.js`

Aquí se define la función `createTaskLi`, que se encarga de crear elementos de lista de tareas (`<li>`) en el DOM. Cada tarea se representa como un elemento de lista con una casilla de verificación, el texto de la tarea, la fecha de creación y, opcionalmente, una marca de prioridad.

## Autor

Este proyecto fue desarrollado por [Tu Nombre].