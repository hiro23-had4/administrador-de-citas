# administrador-de-citas
Este proyecto es una aplicación web en JavaScript, HTML y CSS que permite gestionar citas para pacientes veterinarios.

🐾 Administrador de Citas Veterinarias

Este proyecto es una aplicación web en JavaScript, HTML y CSS que permite gestionar citas para pacientes veterinarios.

✨ Características principales:

📌 Formulario dinámico para registrar pacientes (nombre, propietario, email, fecha y síntomas).

📋 Visualización de citas con información estructurada.

🛠️ Funciones CRUD completas:

Crear nuevas citas.

Editar información de una cita existente.

Eliminar citas registradas.

⚡ Notificaciones dinámicas (errores y confirmaciones).

🎨 Diseño con TailwindCSS para un estilo moderno y responsivo.

🔑 Generación única de IDs para identificar cada cita.

🔍 Tecnologías usadas:

JavaScript Vanilla para toda la lógica (sin frameworks).

HTML5 para la estructura del formulario y la lista de citas.

CSS/TailwindCSS para el estilo.

📂 Estructura principal del código:

class Notificacion → Muestra mensajes de éxito o error.

class AdminCitas → Maneja el arreglo de citas y sus operaciones (agregar, editar, eliminar, mostrar).

citaObj → Objeto base donde se almacenan temporalmente los datos de la cita.

Eventos para manejar el input de los formularios y las acciones de edición/eliminación.
