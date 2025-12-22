# WET Chemical - Visor PDF

Visor de PDF con PDF.js. Desplegado en Vercel.

## Desarrollo Local

```bash
python -m http.server 8080
```

Abre `http://localhost:8080/`

## Despliegue en Vercel

1. **Instala Vercel CLI:**
   ```bash
   npm install -g vercel
   ```

2. **Deploy:**
   ```bash
   vercel
   ```

3. **Accede a tu sitio** en la URL que te proporciona Vercel.

## Estructura

- `index.html` - Página principal
- `archivos/` - PDFs para visualizar
- `pdfjs/` - Visor de PDF.js
