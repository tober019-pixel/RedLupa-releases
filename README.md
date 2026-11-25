# RedLupa · versiones para Android

Aquí se publican las versiones de **RedLupa para Android**, un escáner de la red local.
Este repositorio solo contiene los APK firmados; el código fuente es privado.

## Instalar

1. En el teléfono, abre la [última versión](../../releases/latest) y descarga `RedLupa-x.y.z.apk`.
2. Ábrelo y permite «Instalar apps desconocidas» para la app con la que lo abriste.
3. Si aparece Play Protect, elige «Más detalles» → «Instalar de todas formas».
4. Al abrir RedLupa, concede la ubicación precisa y las notificaciones.

Requiere Android 8.0 o superior.

## Actualizaciones automáticas

Desde la versión 1.2.0, RedLupa busca actualizaciones una vez al día en este repositorio
(`releases/latest/download/version.json`), descarga el APK, comprueba su SHA-256 y lo instala.
Android solo acepta actualizaciones firmadas con la misma clave que la versión instalada.
Se puede desactivar en *Ajustes → Actualizaciones automáticas*.

## Verificar un APK

Cada versión incluye `version.json` con el SHA-256 del APK. En Windows:

```powershell
Get-FileHash .\RedLupa-1.2.0.apk -Algorithm SHA256
```

Huella SHA-256 del certificado de firma:
`2cef75c98acb3c0d2ca6c3098f92bb59528c56c7f1fe93c140ce86f6b4f36d7f`
