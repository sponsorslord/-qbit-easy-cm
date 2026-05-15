# ✳ QBIT Easy CM

Sistema de gestión de calendarios de contenido con IA integrada.

## Cómo subir a Vercel (5 minutos)

### Paso 1 — Subir a GitHub

1. Abrí tu repo en github.com
2. Clic en "Add file" → "Upload files"
3. Arrastrá los dos archivos: `index.html` y `vercel.json`
4. Clic en "Commit changes"

### Paso 2 — Conectar con Vercel

1. Entrá a vercel.com
2. "Add New Project"
3. Seleccioná tu repo de GitHub
4. Dejá todo por default, clic en "Deploy"
5. En ~30 segundos tenés tu URL: `https://tu-repo.vercel.app`

### Paso 3 — Configurar

1. Abrí tu URL
2. Se va a abrir automáticamente la pantalla de configuración
3. Pegá tu API Key de Anthropic
4. Guardá — listo, ya funciona

## Estructura del proyecto

```
qbit-easy-cm/
├── index.html      ← La app completa (todo en un archivo)
└── vercel.json     ← Config de Vercel
```

## Cómo usar

1. Creá un cliente nuevo con su briefing completo
2. Abrí el workspace del cliente
3. Chateá con Claude directamente en la app
4. Cuando los copys estén listos, generá la página del cliente con el botón verde
5. Compartí el archivo HTML descargado con tu cliente

## Datos

Todos los datos (clientes, conversaciones) se guardan en el localStorage del navegador.
No viajan a ningún servidor externo — solo la API key de Anthropic para las llamadas a Claude.
