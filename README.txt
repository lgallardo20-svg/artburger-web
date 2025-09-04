# Art Burguer — Sitio estático (solo delivery)
Este paquete contiene un sitio **estático** de una página (HTML + CSS + JS) listo para publicar en **Vercel**.

## 1) Personaliza antes de publicar
1. **WhatsApp:** busca `569XXXXXXXX` y reemplázalo por tu número (formato sin `+`, sin espacios, solo dígitos). Ejemplo `56998765432`.
2. **Correo:** (opcional) en `index.html` busca `contacto@artburguer.cl` y reemplázalo por el tuyo.
3. **Zonas/horarios:** modifica los textos en las secciones “Zonas de reparto” y “Horarios”.

## 2) Sube a GitHub con la web (sin usar código)
1. Crea una cuenta en https://github.com (si no tienes).
2. Arriba a la izquierda: **New** → `Repository name`: `artburguer-web` → **Create repository**.
3. En el repositorio, clic en **Add file** → **Upload files**.
4. Arrastra el archivo ZIP (este) o los archivos adentro del ZIP. Clic **Commit changes**.

## 3) Despliega en Vercel
1. Crea una cuenta en https://vercel.com (Sign Up).
2. Dashboard → **New Project** → **Import Git Repository** → elige `artburguer-web`.
3. Vercel detectará que es un sitio estático (no poner build command). Clic **Deploy**.
4. Obtendrás una URL tipo `https://artburguer.vercel.app`.

## 4) Conecta tu dominio .cl
**Opción simple (recomendada): usar los nameservers de Vercel**  
- En Vercel: Project → **Settings → Domains** → **Add Domain**: agrega `artburger.cl` (o `artburguer.cl` según tu dominio real).  
- Vercel mostrará los nameservers: `ns1.vercel-dns.com` y `ns2.vercel-dns.com`.

**En NIC Chile**  
- Mis dominios → engranaje (⚙️) → **Configuración técnica** → **Servidores DNS**.  
- Agrega: `ns1.vercel-dns.com` y `ns2.vercel-dns.com`. Guardar.

**Volver a Vercel**  
- En **Settings → Domains**: presiona **Verify** en tu dominio hasta que quede “Active”.

> Nota: la propagación puede demorar un rato. Si no responde enseguida, inténtalo más tarde.

## 5) Actualizaciones de contenido
- Para cambiar textos, edita `index.html` desde la interfaz web de GitHub (botón ✏️ “Edit”), y luego **Commit changes**. Vercel publicará automáticamente la nueva versión.
