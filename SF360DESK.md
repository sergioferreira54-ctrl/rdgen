# SF360Desk

SF360Desk es una versión con el nombre y el logo de SF360 de **RustDesk**, el programa de escritorio remoto de código abierto.

## Licencia

- SF360Desk se basa en RustDesk (https://github.com/rustdesk/rustdesk), © Purslane Tech Pte. Ltd., distribuido bajo la licencia **GNU AGPL-3.0**.
- Este generador se basa en rdgen (https://github.com/bryangerlach/rdgen).
- El código fuente de SF360Desk está disponible en este repositorio. Incluye la configuración (`sf360desk/config.json`) y el flujo de compilación (`.github/workflows/sf360desk-windows.yml`).
- No se modificó la licencia ni el texto del acuerdo de licencia. Se conservan los avisos de copyright originales y el crédito "Powered by RustDesk" dentro de la aplicación.
- "RustDesk" es una marca de sus respectivos dueños. SF360Desk no está afiliado a RustDesk ni a Purslane Tech.

## Qué se cambió

- Nombre de la aplicación: SF360Desk
- Ícono y logo: SF360
- Tema claro por defecto
- Sin aviso de "nueva versión" (para que no se instale el RustDesk original encima)
- Servidores: los públicos de RustDesk

## Cómo compilar

1. Pestaña **Actions** → **SF360Desk Windows** → **Run workflow** (versión `1.5.3`).
2. Esperar unos 30 a 45 minutos.
3. Descargar el artefacto **SF360Desk-windows-x64**, que contiene `sf360desk.exe` y `sf360desk.msi`.
