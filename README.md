# mgDrop

Transferencia de archivos por LAN/WiFi, simple y directa.

## Que es

`mgDrop` sirve para enviar archivos entre dos PCs dentro de la misma red local.

- Sin configuraciones raras.
- Sin cuentas.
- Sin internet (solo red local).

## Como se usa (1 minuto)

1. Abre `mgDrop` en los 2 equipos.
2. En el equipo que **recibe**, copia `Tu IP local`.
3. En el equipo que **envia**, pega esa IP en `IP DESTINO`.
4. Pulsa `Seleccionar archivo`.
5. Pulsa `Enviar`.
6. Revisa el progreso y el tiempo restante en `Estado actual`.

## Donde se guardan los archivos

Los archivos recibidos se guardan en:

`Descargas/mgDrop`

Tambien puedes abrir esa carpeta desde el boton:

`Abrir carpeta de recepcion`

## Requisitos importantes

- Ambos equipos deben estar en la **misma red** (WiFi o cable).
- Si Windows Firewall pregunta, pulsa **Permitir acceso** (red privada).

## Si no funciona

1. Verifica que ambos PCs estan en la misma red.
2. Comprueba que la IP destino esta bien escrita.
3. Cierra y abre `mgDrop` en ambos equipos.
4. Revisa si antivirus/firewall corporativo bloquea conexiones LAN.

## Error `VCRUNTIME140.dll`

Instala Microsoft Visual C++ Redistributable (x64):

[https://aka.ms/vs/17/release/vc_redist.x64.exe](https://aka.ms/vs/17/release/vc_redist.x64.exe)

Despues, vuelve a abrir `mgDrop`.

## Opcion de seguridad

Si activas `Preguntar antes de recibir archivos`, cada recepcion pedira:

- Aceptar
- Rechazar

antes de guardar el archivo.

## Autor

Creado por **Michael MG (GATI - TRC)**.

Hecho en Rust.
