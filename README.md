# Academia Estelar integral v3

Paquete web autocontenido para laptop, iPad y iPhone. Publica todos los archivos juntos en la raíz de un hosting HTTPS y abre `index.html`.

## Experiencia
- Cuatro pestañas: Matemáticas, Español, Inglés y Miscelánea.
- Diez mundos por pestaña y diez tipos visibles por mundo.
- El texto del enunciado y la pregunta usan exactamente el mismo tamaño (`--test-size`), con colores distintos.
- El feedback aparece como un popup breve sobre el test: 1.9 s tras un acierto y 3.9 s tras un error.
- El popup no requiere botón; después avanza automáticamente.
- La ruta mantiene 3 preguntas del mismo tipo y 9 del mismo mundo.
- La dificultad aumenta lentamente: requiere 6 aciertos consecutivos, dominio suficiente y tiempo adecuado; sube 0.16 y baja 0.08 tras error.
- Perfiles locales, misión diaria, puntos, racha, exportación e importación.

## iOS
La aplicación debe publicarse bajo HTTPS. En Safari: Compartir > Añadir a pantalla de inicio. El service worker usa la caché `academia-estelar-integral-v3`.

## Actualización
Si ya existe una versión instalada, elimina una vez el acceso anterior o los datos del sitio para evitar archivos de caché antiguos.
