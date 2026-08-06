# ST Soluciones Integrales

Sitio web de ST Soluciones Integrales — remodelaciones y reformas en
Montevideo y Canelones.

Es una sola página estática (`index.html`), sin dependencias ni build:
todo el CSS y el JavaScript van dentro del archivo. Lo único externo son
las tipografías de Google Fonts.

## Publicar en Netlify

1. En https://app.netlify.com entrar a **Add new site → Import an existing
   project → GitHub** y elegir el repositorio `jscodelive/stsolucionesjl`.
2. Netlify lee `netlify.toml` y completa la configuración solo. Si pide
   los datos a mano:
   - **Branch to deploy:** `main`
   - **Build command:** vacío
   - **Publish directory:** `.`
3. **Deploy site**.

Desde ahí, cada `git push` a `main` publica una versión nueva
automáticamente.

## Dominio propio

En Netlify: **Domain management → Add a domain**. Netlify indica qué
registros DNS cargar donde esté comprado el dominio, y emite el
certificado HTTPS solo (Let's Encrypt).

## Editar el sitio

```bash
git clone git@github.com:jscodelive/stsolucionesjl.git
cd stsolucionesjl
# abrir index.html en el navegador para previsualizar
git add index.html && git commit -m "cambio X" && git push
```

## Datos que conviene revisar antes de difundir

- WhatsApp y teléfono: `097 164 582` (`+59897164582`).
- Horario declarado: lunes a sábado, 8:00 a 19:00.
- Zona de trabajo: Montevideo y Canelones.
