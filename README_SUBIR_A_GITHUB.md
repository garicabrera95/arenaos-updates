# Subir update ArenaOS 2.1.24 a GitHub

Sube estos archivos al repo `garicabrera95/arenaos-updates`:

```text
latest.json
releases/ArenaOS-update-2.1.24.zip
```

Después configura en `C:\ArenaOS\config\.env`:

```env
ARENAOS_UPDATE_FEED_URL=https://raw.githubusercontent.com/garicabrera95/arenaos-updates/main/latest.json
ARENAOS_UPDATE_CHECK_INTERVAL_HOURS=6
```

Cierra y abre ArenaOS. Luego ve a:

```text
Configuración > Actualizaciones > Buscar actualizaciones
```

Debe aparecer ArenaOS 2.1.24.
