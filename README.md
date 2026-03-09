# 🏠 SJ Gestión Inmobiliaria - Guía de Deploy en Vercel

## 🚀 **Opción 1: Subir Archivos Directamente (MÁS FÁCIL)**

### **Paso a Paso (5 minutos):**

1. **Crear cuenta en Vercel**
   - Ve a: https://vercel.com
   - Click en "Sign Up" (esquina superior derecha)
   - Elige una opción:
     - Continue with GitHub (recomendado)
     - Continue with GitLab
     - Continue with Email
   - Completa el registro (es gratis, no pide tarjeta)

2. **Crear nuevo proyecto**
   - Una vez dentro, click en "Add New..." 
   - Selecciona "Project"
   - En la pantalla que aparece, busca el botón "Upload" (esquina superior derecha)

3. **Subir tus archivos**
   - **Opción A:** Arrastra la carpeta completa que descargaste
   - **Opción B:** Click en "Select Directory" y elige la carpeta
   
   La carpeta debe contener:
   ```
   📁 sj-gestion-inmobiliaria/
   ├── 📄 index.html
   ├── 📄 propiedad.html
   ├── 📄 vercel.json
   └── 📄 README.md (este archivo)
   ```

4. **Configurar proyecto**
   - Project Name: `sj-gestion-inmobiliaria` (o el que prefieras)
   - Framework Preset: Other
   - Root Directory: `./` (dejar como está)
   - Build and Output Settings: No tocar nada
   - Click en "Deploy"

5. **¡Esperar 30 segundos!**
   - Vercel procesará y publicará tu sitio
   - Verás una animación de confeti cuando esté listo 🎉

6. **Tu sitio está vivo!**
   - URL: `https://sj-gestion-inmobiliaria.vercel.app`
   - Puedes personalizar el dominio después
   - Click en "Visit" para ver tu sitio

---

## 🔄 **Opción 2: Conectar con GitHub (Para actualizar fácilmente)**

### **Ventajas:**
- Cada vez que hagas un cambio en GitHub, se actualiza automáticamente
- Historial de versiones
- Más profesional

### **Pasos:**

1. **Crear repositorio en GitHub**
   - Ve a: https://github.com
   - Click en "New repository" (botón verde)
   - Nombre: `sj-gestion-inmobiliaria`
   - Descripción: "Sitio web de SJ Gestión Inmobiliaria"
   - Public o Private (como prefieras)
   - Click "Create repository"

2. **Subir archivos al repositorio**
   - En tu computadora, abre la carpeta del proyecto
   - Arrastra los archivos a la página de GitHub
   - O usa GitHub Desktop si prefieres interfaz gráfica
   - Commit: "Primer commit - sitio web completo"

3. **Conectar Vercel con GitHub**
   - En Vercel, click "Add New..." → "Project"
   - Click en "Import Git Repository"
   - Autoriza el acceso a GitHub
   - Selecciona el repositorio `sj-gestion-inmobiliaria`
   - Click "Import"
   - Framework Preset: Other
   - Click "Deploy"

4. **¡Listo!**
   - Ahora cada vez que hagas cambios en GitHub
   - Vercel se actualiza automáticamente
   - Sin necesidad de re-subir nada

---

## 📝 **Después del Deploy**

### **Tu sitio estará en:**
```
https://sj-gestion-inmobiliaria.vercel.app
```

### **Panel de Control:**
En el dashboard de Vercel podrás:
- ✅ Ver estadísticas de visitas
- ✅ Agregar dominio personalizado
- ✅ Ver logs de errores
- ✅ Re-deployar versiones anteriores
- ✅ Configurar variables de entorno

---

## 🌐 **Agregar Dominio Personalizado (Opcional)**

Si tienes un dominio propio (ej: `sjgestion.com`):

1. En tu proyecto de Vercel, ve a "Settings"
2. Click en "Domains"
3. Escribe tu dominio: `sjgestion.com`
4. Sigue las instrucciones para configurar DNS
5. ¡Listo! Tu sitio estará en tu dominio

**Proveedores de dominios recomendados:**
- Namecheap (~$10/año)
- Google Domains (~$12/año)
- Cloudflare (~$10/año)

---

## 🔧 **Actualizar el Sitio (Con GitHub)**

### **Método 1: En GitHub Web**
1. Ve a tu repositorio en GitHub
2. Click en el archivo que quieres editar (ej: `index.html`)
3. Click en el ícono de lápiz (Edit)
4. Haz tus cambios
5. Scroll abajo, escribe mensaje: "Actualización: [lo que cambiaste]"
6. Click "Commit changes"
7. ¡Vercel actualiza automáticamente en 30 segundos!

### **Método 2: Desde tu computadora**
1. Edita los archivos en tu PC
2. Sube los cambios a GitHub
3. Vercel detecta y publica automáticamente

### **Método 3: Subir nueva versión directo a Vercel**
1. Ve a tu proyecto en Vercel
2. Click en "Deployments"
3. Click en "Upload" (arriba)
4. Sube la carpeta actualizada
5. Se crea una nueva versión

---

## ⚙️ **Configuraciones Importantes**

### **Variables de Entorno (si las necesitas)**
Si en el futuro quieres guardar contraseñas o API keys:
1. Settings → Environment Variables
2. Agrega: `NOMBRE_VARIABLE` = `valor`
3. Re-deploy el proyecto

### **Analytics (Estadísticas)**
Vercel incluye analytics gratis:
1. Settings → Analytics
2. Enable Analytics
3. Verás gráficas de visitas, performance, etc.

---

## 🐛 **Solución de Problemas**

### **"Error: No se encuentra index.html"**
- Asegúrate de que `index.html` está en la raíz del proyecto
- No debe estar dentro de subcarpetas

### **"Las imágenes no cargan"**
- Verifica que las URLs de Cloudinary estén correctas
- Revisa la consola del navegador (F12) para ver errores

### **"El sitio se ve diferente"**
- Limpia el caché del navegador (Ctrl + Shift + R)
- Espera 1-2 minutos a que se propague el deploy

### **"No puedo subir archivos"**
- Verifica que la carpeta tenga los archivos correctos
- Intenta comprimir en .zip y subir el .zip

---

## 📊 **Ventajas de Vercel**

✅ **Gratis para siempre** (para proyectos personales)
✅ **Ancho de banda ilimitado** (sin cargos ocultos)
✅ **SSL/HTTPS gratis** (seguridad automática)
✅ **CDN global** (sitio ultra rápido en todo el mundo)
✅ **Deploy instantáneo** (30 segundos o menos)
✅ **Preview deployments** (ver cambios antes de publicar)
✅ **Sin límites de proyectos** (puedes crear más sitios)

---

## 🆘 **¿Necesitas Ayuda?**

### **Recursos Oficiales:**
- Documentación: https://vercel.com/docs
- Soporte: https://vercel.com/support
- Comunidad: https://github.com/vercel/vercel/discussions

### **Contacto Directo:**
Si tienes problemas, puedes:
1. Revisar los logs en Vercel Dashboard
2. Consultar la documentación
3. Preguntar en la comunidad de Vercel

---

## 🎯 **Próximos Pasos Sugeridos**

Después de que tu sitio esté publicado:

1. **Probar todas las funcionalidades:**
   - ✅ Login como admin
   - ✅ Agregar nueva propiedad
   - ✅ Subir imágenes
   - ✅ Agregar foto 360°
   - ✅ WhatsApp links

2. **Compartir el link:**
   - Con clientes potenciales
   - En redes sociales
   - En WhatsApp Business

3. **Monitorear:**
   - Ver analytics de visitas
   - Revisar qué propiedades son más vistas

4. **Optimizar:**
   - Agregar más propiedades reales
   - Subir fotos de alta calidad
   - Agregar tours 360° a propiedades destacadas

---

## 📱 **Tips Pro**

### **Para mejor rendimiento:**
- Optimiza imágenes antes de subir (usa TinyPNG.com)
- Las fotos no deberían pesar más de 500KB cada una
- Usa formato WebP cuando sea posible

### **Para mejor SEO:**
- Agrega descripción única a cada propiedad
- Usa títulos descriptivos
- Incluye ubicaciones específicas

### **Para más conversiones:**
- Actualiza propiedades regularmente
- Responde rápido a WhatsApp
- Agrega fotos 360° a propiedades premium

---

## 🎉 **¡Estás Listo!**

Tu sitio profesional de gestión inmobiliaria estará en línea en menos de 5 minutos.

**URL final:** `https://[tu-nombre-proyecto].vercel.app`

¡Éxito con tu inmobiliaria! 🏠🚀
