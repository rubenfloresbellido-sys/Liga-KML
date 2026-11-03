# FC 25 - Manager Tortugas Guerreras

Web para gestionar una liga: equipos, jugadores con cartas estilo FC 25, clasificación de Primera y Segunda División, y la Copa Libertadores (grupos, sorteo y eliminatorias).

## Archivos

- `index.html`: la web completa.
- `data.json`: los datos de la liga (equipos, jugadores, grupos y resultados). Es lo que ven los visitantes.

## Cómo funciona

- **Visitantes:** la web lee `data.json` y muestra los datos. No pueden editar nada.
- **Administrador:** al entrar con la contraseña, los cambios se guardan en el navegador de ese ordenador.

## Cómo actualizar los datos

1. Entra como administrador y haz tus cambios.
2. Pulsa **Exportar datos (data.json)**.
3. Sustituye el `data.json` de la carpeta del proyecto por el nuevo.
4. Sube `data.json` a GitHub (Add file → Upload files → Commit changes).

La web publicada se actualiza en uno o dos minutos.

## Probar en local

Abre la carpeta en VS Code, instala la extensión **Live Server**, haz clic derecho en `index.html` y elige **Open with Live Server**.

## Nota

Cada navegador guarda su propia copia de los cambios del administrador. Antes de cambiar de ordenador, exporta y sube `data.json`.
