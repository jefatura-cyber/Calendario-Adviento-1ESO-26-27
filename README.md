# 24 Aventuras - Calendario de Adviento Matemático

Prototipo funcional sin servidor para el IES Ciudad de Coín, 1.º ESO, diciembre 2026.

## Incluye
- Seis grupos seleccionables (1.º ESO A-F).
- Seis temáticas, cuatro navideñas y dos neutras, elegidas por el alumnado.
- 24 puertas, desbloqueo por fecha y modo de prueba.
- 21 desafíos autocorregibles, con cuatro variantes orientativas de dificultad (1 a 4).
- Tres desafíos abiertos (días 6, 13, 20), con texto, modalidad de foto simulada o entrega en mano.
- Insignias, estrellas, recompensas de ejemplo, panel local de revisión y exportación CSV.
- Diseño adaptable a móvil.

## Cómo probarlo
1. Abre `index.html` en tu navegador (o súbelo a GitHub Pages).
2. Pulsa «Profesorado» y activa «Desbloquear las 24 puertas para probar».
3. Pulsa «Empezar mi aventura» y crea un código ficticio de agente (por ejemplo, DEMO-07).
4. Elige grupo y nivel orientativo de prueba; luego elige una de las seis historias.
5. Completa misiones, presenta una entrega manual y entra en «Profesorado» para validar esa entrega.

## Limitaciones IMPORTANTES
Este archivo es **solo una demostración local**. Los datos se guardan en `localStorage` del navegador. **NO hay autenticación de alumnado o profesorado, ni permisos reales, ni sincronización entre dispositivos, ni copia de seguridad.** Cualquiera con el navegador podría abrir el panel local y cambiar sus registros. La corrección automática también ocurre en el navegador y no es segura frente a manipulación.

No introduzcas datos personales reales de menores. La opción «Fotografía» permite seleccionar un archivo solamente como simulación; **no sube ni guarda la imagen ni el contenido del fichero**. Las recompensas no se canjean realmente. Las historias usan escenas narrativas breves y comparten el motor de retos, no seis guiones completos exclusivos. El perfil de nivel puede elegirse en la demo, pero en producción deberá asignarlo el profesor.

## Para producción en seis grupos
Antes de uso real, contar con aprobación del centro y valoración de protección de datos; autenticar docentes y estudiantes; aplicar permisos de grupo del lado del servidor; almacenar respuestas, imágenes y revisiones en backend privado; crear códigos seguros; dar opciones de eliminación y exportación autorizadas; y revisar didácticamente los problemas por contenido, nivel y ACIS. La publicación HTML en GitHub Pages **no cumple** por sí sola estos requisitos.
