# Instrucciones para Agregar el Logo

Para que tu logo aparezca correctamente en la Landing Page, sigue estos pasos:

## 📁 Archivos de Logo Necesarios

Guarda tu logo en esta carpeta (`public/images/`) con los siguientes nombres:

### 1. Logo Principal (Navbar - Fondo Blanco)
**Nombre:** `radix-logo.png`
- **Fondo:** Transparente o blanco
- **Color del logo:** Verde oscuro (#0E3F2E) 
- **Dimensiones recomendadas:** 800x200px (ancho x alto)
- **Formato:** PNG con transparencia

### 2. Logo para Footer (Fondo Oscuro) - OPCIONAL
**Nombre:** `radix-logo-white.png`
- **Fondo:** Transparente
- **Color del logo:** Blanco
- **Dimensiones recomendadas:** 800x200px
- **Formato:** PNG con transparencia

**Nota:** Si solo tienes un logo en verde, no te preocupes. El código aplicará un filtro automático para invertir los colores en el footer.

## 🎨 Especificaciones Técnicas

- **Formato:** PNG (preferido por transparencia) o JPG
- **Resolución:** Mínimo 600x150px, recomendado 800x200px
- **Peso:** Máximo 500KB (optimiza si es más pesado)
- **Aspecto ratio:** Mantén la proporción aproximada de 4:1 (ancho:alto)

## 📸 Cómo Guardar tu Logo

1. Toma la imagen del logo que te compartí (o tu versión final)
2. Renómbrala a `radix-logo.png`
3. Guárdala en: `public/images/radix-logo.png`
4. Reinicia el servidor de desarrollo (`npm run dev`)
5. ¡Listo! Tu logo debería aparecer en el Navbar y Footer

## 🔧 Si el Logo No Aparece

1. Verifica que el archivo esté en la ruta correcta: `public/images/radix-logo.png`
2. Asegúrate de que el nombre sea exactamente `radix-logo.png` (minúsculas)
3. Reinicia el servidor con `Ctrl+C` y luego `npm run dev`
4. Limpia la caché del navegador (Ctrl+Shift+R o Cmd+Shift+R)

## 💡 Optimización de Imagen (Opcional)

Para mejor rendimiento, optimiza tu logo en:
- [TinyPNG](https://tinypng.com/) - Compresión PNG
- [Squoosh](https://squoosh.app/) - Optimizador universal
- Photoshop: "Export for Web" con calidad 80-90%

---

Si tienes problemas, verifica que tu logo tenga fondo transparente y esté en formato PNG.

