# Orden Financiero — App PWA

App financiera educativa para celular. Funciona sin App Store, se instala desde el navegador.

## Herramientas incluidas
- **Drenaje del ingreso**: Barra visual que muestra a dónde va el dinero
- **Línea de tiempo**: Proyección de deuda y ahorro a 24 meses
- **Semáforo semanal**: Cuánto podés gastar esta semana
- **Flujo de caja**: Registro de ingresos y gastos semana a semana o mes a mes

---

## Cómo publicarla GRATIS en 10 minutos

### Paso 1 — Crear cuenta en GitHub
1. Ir a https://github.com y crear cuenta gratuita

### Paso 2 — Crear repositorio
1. Click en "New repository"
2. Nombre: `orden-financiero` (o el que quieras)
3. Marcar como "Public"
4. Click "Create repository"

### Paso 3 — Subir los archivos
Subí estos 3 archivos al repositorio:
- `index.html`
- `manifest.json`
- `sw.js`

Podés hacerlo arrastrando los archivos directamente en GitHub.

### Paso 4 — Activar GitHub Pages
1. En tu repositorio, ir a Settings → Pages
2. En "Source" seleccionar "Deploy from a branch"
3. Branch: `main`, carpeta: `/ (root)`
4. Click Save

En 1-2 minutos tu app queda en:
**https://TU_USUARIO.github.io/orden-financiero**

### Paso 5 — Compartir con alumnos
Mandá esa URL por WhatsApp, email o dentro de tu plataforma de cursos.

Los alumnos en Android verán automáticamente el banner "Instalar app".
En iPhone: abrir en Safari → botón compartir → "Agregar a pantalla de inicio".

---

## Para agregar un ícono real
Creá dos imágenes PNG:
- `icon-192.png` — 192×192 px
- `icon-512.png` — 512×512 px

Subílas junto a los demás archivos. Podés crear los íconos gratis en https://www.canva.com

---

## Notas técnicas
- Funciona offline (Service Worker hace caché)
- Los datos del usuario se guardan localmente en su dispositivo (localStorage)
- Compatible con Android e iOS
- No requiere servidor ni base de datos
