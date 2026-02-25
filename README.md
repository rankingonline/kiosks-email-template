# Kiosko Email Templates

Este repositorio contiene un set de **4 plantillas de correos electrónicos en HTML** diseñadas específicamente para un ecommerce, junto con una **pantalla de inicio (Index)** para visualizarlas todas juntas.

Todas las plantillas fueron creadas utilizando estructuras basadas en `<table>`, diseño inline CSS para asegurar la mayor compatibilidad posible con los múltiples clientes de correo del mercado (Gmail, Outlook, Apple Mail, etc.), y con un diseño *responsive* para adaptarse a dispositivos móviles.

## 🎨 Identidad de Marca (Branding)

Las plantillas y la galería de inicio fueron personalizadas con la siguiente guía de estilo:

**Tipografía:**
- Fuente Principal: `Poppins` (con *fallback* a tipografías *sans-serif* del sistema si el cliente de correo no soporta Web Fonts).

**Paleta de Colores:**
- **Primary:** `#EB6F79` (Usado para botones principales (CTAs), acentos y precios destacados).
- **Secondary:** `#A1D7E8` (Usado para subtítulos de acento o fondos secundarios que brindan un toque fresco).
- **Dark:** `#2B273B` (Usado para encabezados, títulos importantes, footers y textos de alto contraste).
- **Light:** `#FFFFFF` (Fondo interno de los correos para potenciar la legibilidad y fondos limpios).

---

## 📂 Archivos en el Repositorio

1. **`index.html`**
   - Una galería visual e interactiva construida en CSS puro para previsualizar todas las plantillas antes de utilizarlas.

2. **`template-1-hero.html` (Hero Clásico)**
   - **Enfoque:** Lanzamientos o anuncios importantes.
   - **Estructura:** Banner superior claro, imagen prominente expansiva de borde a borde y un botón central para llamar a la acción.

3. **`template-2-two-columns.html` (Dos Columnas - Z Pattern)**
   - **Enfoque:** Artículos destacados o contenido dinámico.
   - **Estructura:** Encabezado oscuro (#2B273B), columna de texto descriptivo a la izquierda (con CTA rosa #EB6F79), e imagen a la derecha. Adaptativo a móviles verticalmente.

4. **`template-3-product.html` (Flash Sale / Venta Rápida)**
   - **Enfoque:** Urgencia y promociones.
   - **Estructura:** Textos grandes de descuento, imagen masiva de producto central y un botón de "ancho total" de color oscuro para forzar el clic desde móviles.

5. **`template-4-grid.html` (Grid / Cuadrícula de Productos)**
   - **Enfoque:** Catálogos pequeños, Remarketing (Carritos abandonados).
   - **Estructura:** Dos productos ubicados lado a lado con sus fotos, títulos (#2B273B), precios resaltados (#EB6F79) e individuales botones de compra. Se apilan orgánicamente al achicar la pantalla.

---

## ⚙️ Cómo Utilizarlos

1. Abre cualquiera de los archivos `.html` (`template-1-hero.html`, etc.) en tu editor de código preferido (VSCode, Sublime, etc.).
2. **Reemplaza la URL de las imágenes:** 
   Busca la etiqueta `<img src="...">` y cambia el valor actual de Unsplash por las URL absolutas donde alojes las imágenes de tu E-Commerce. Ej: `<img src="https://mi-tienda.com/img/banner.jpg">`
3. **Reemplaza los enlaces (Links):** 
   Busca los botones representados por etiquetas `<a>` con el enlace por defecto `#` (por ejemplo `<a href="#">Ver Detalles</a>`) y cámbialo a tu página de producto `https://tusitio.com/producto`.
4. Copia el código fuente completo e insertalo en tu plataforma de Email Marketing (MailChimp, Klaviyo, Sendinblue, ActiveCampaign, etc.) usando la opción de *Importar HTML personalizado*.
