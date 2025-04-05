📊 Dashboard de Clases Zoom
Este proyecto es un dashboard dinámico que muestra en tiempo real el estado de las clases que se están realizando mediante Zoom, cruzando datos de una hoja de Google Sheets y la API de Zoom.

🚀 ¿Cómo funciona?
El backend está construido en Google Apps Script como una Web App pública que:

Lee una hoja de cálculo (CURSOS) con la programación semanal de clases.

Consulta reuniones activas en la cuenta de Zoom mediante OAuth (Server-to-Server).

Devuelve una respuesta JSON con las clases activas o por iniciar.

Este HTML:

Se conecta al backend cada 3 minutos.

Muestra tarjetas y una tabla con las clases que deben estar activas.

Usa colores según la asistencia real vs. agendada.

Incluye un temporizador de actualización automática.
