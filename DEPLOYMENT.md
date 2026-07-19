# 🚀 Guía de Deployment - Obra Clara Pro

## Cloudflare Pages (Recomendado)

### Paso 1: Ir a Cloudflare Pages
👉 https://pages.cloudflare.com

### Paso 2: Conectar GitHub
1. Click en **"Connect to Git"**
2. Autoriza Cloudflare en GitHub
3. Selecciona: **`robersdk/gestion-arquitectos`**

### Paso 3: Configurar Deploy
```
Project name:           gestion-arquitectos
Production branch:      main
Build command:          (dejar vacío)
Build output directory: (dejar vacío)
Root directory:         (dejar vacío)
```

### Paso 4: Deploy
- Click: **"Save and Deploy"**
- Espera 1-2 minutos

### ✅ Tu URL
```
https://gestion-arquitectos.pages.dev
```

---

## GitHub Pages (Alternativa)

### Paso 1: Settings del Repo
1. Ve a **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: **main** / root
4. Save

### ✅ Tu URL
```
https://robersdk.github.io/gestion-arquitectos
```

---

## 🔄 Actualizaciones Futuras

Simplemente haz push a la rama `main` y **el deploy es automático** ✨

```bash
git add .
git commit -m "feat: nueva característica"
git push origin main
```

---

## 📊 Estructura de Archivos

```
gestion-arquitectos/
├── index.html           # App completa (SPA)
├── README.md            # Documentación
├── FEATURES.md          # Características
├── DEPLOYMENT.md        # Este archivo
├── _redirects           # Rutas Cloudflare
└── .gitignore           # Archivos ignorados
```

---

## 🎯 URL en vivo

Una vez desplegado, accede a:
- **Cloudflare**: `https://gestion-arquitectos.pages.dev`
- **GitHub Pages**: `https://robersdk.github.io/gestion-arquitectos`

¡Listo! 🎉