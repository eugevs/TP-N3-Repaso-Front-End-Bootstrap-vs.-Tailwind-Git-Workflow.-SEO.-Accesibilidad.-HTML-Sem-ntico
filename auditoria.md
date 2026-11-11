# Informe de Auditoría y Optimización Web - Explorando lugares

Este documento detalla los resultados de las auditorías de rendimiento, accesibilidad, buenas prácticas y SEO realizadas con **Lighthouse** en Chrome DevTools para todas las vistas del proyecto, junto con las optimizaciones aplicadas.

---

## 1. Resumen de Optimizaciones Realizadas
- **Optimización de imágenes:** Se reemplazaron los recursos PNG originales por versiones comprimidas en formato **WebP** mediante *Squoosh*, ajustando sus dimensiones para evitar sobrecarga de red y mejorar el *Largest Contentful Paint (LCP)*.
- **Formateo y estructura:** Se aplicó *Prettier* para estandarizar la sintaxis HTML y CSS, y se reorganizaron los assets depositando los wireframes en la carpeta `docs/`.

---

## 2. Resultados de Auditoría por Vista

###  Inicio (`index.html`)
- **Performance:** 100 / 100[cite: 7]
- **Accessibility:** 100 / 100[cite: 7]
- **Best Practices:** 96 / 100[cite: 7]
- **SEO:** 100 / 100[cite: 7]
- *Métricas clave:* FCP (0.6 s) | LCP (0.7 s) | TBT (0 ms) | CLS (0)[cite: 8]
- *Observación:* Optimización del banner hero a formato WebP.

###  Caminatas (`caminatas.html`)
- **Performance:** 100 / 100
- **Accessibility:** 100 / 100
- **Best Practices:** 100 / 100
- **SEO:** 100 / 100
- *Observación:* Uso de miniaturas ajustadas en tarjetas de recorridos.

###  Equipamiento (`equipamiento.html`)
- **Performance:** 100 / 100[cite: 12]
- **Accessibility:** 100 / 100[cite: 12]
- **Best Practices:** 100 / 100[cite: 12]
- **SEO:** 100 / 100[cite: 12]
- *Métricas clave:* FCP (0.6 s) | LCP (0.7 s) | TBT (0 ms) | CLS (0)[cite: 9]
- *Observación:* Carga excelente de las tarjetas de mochilas, calzado y equipo en formato WebP.

###  Contacto (`contacto.html`)
- **Performance:** 100 / 100[cite: 15]
- **Accessibility:** 95 / 100[cite: 15]
- **Best Practices:** 100 / 100[cite: 15]
- **SEO:** 100 / 100[cite: 15]
- *Observación:* Vista de formulario optimizada y ágil.

###  Detalle de Ruta (`ruta-detalle.html`)
- **Performance:** 100 / 100[cite: 19]
- **Accessibility:** 100 / 100[cite: 19]
- **Best Practices:** 77 / 100[cite: 19]
- **SEO:** 100 / 100[cite: 19]
- *Observación:* Excelente rendimiento y carga fluida de los detalles del sendero.

###  Iniciar Sesión (`login.html`)
- **Performance:** 100 / 100[cite: 23]
- **Accessibility:** 100 / 100[cite: 23]
- **Best Practices:** 100 / 100[cite: 23]
- **SEO:** 100 / 100[cite: 23]
- *Observación:* Vista de acceso liviana y con máxima puntuación en todas las métricas.

###  Registro (`registro.html`)
- **Performance:** 100 / 100[cite: 27]
- **Accessibility:** 100 / 100[cite: 27]
- **Best Practices:** 100 / 100[cite: 27]
- **SEO:** 100 / 100[cite: 27]
- *Observación:* Formulario de registro optimizado, accesible y con máxima puntuación.

###  Galería (`galeria.html`)
- **Performance:** 99 / 100[cite: 28]
- **Accessibility:** 100 / 100[cite: 28]
- **Best Practices:** 100 / 100[cite: 28]
- **SEO:** 100 / 100[cite: 28]
- *Observación:* Excelente rendimiento en la grilla de imágenes y componentes multimedia optimizados.

###  Sobre el Sitio (`nosotros.html`)
- **Performance:** 100 / 100[cite: 36]
- **Accessibility:** 100 / 100[cite: 36]
- **Best Practices:** 100 / 100[cite: 36]
- **SEO:** 100 / 100[cite: 36]
- *Observación:* Máxima puntuación en todas las métricas institucionales.

###  Perfil (`perfil.html`)
- **Performance:** 100 / 100[cite: 32]
- **Accessibility:** 100 / 100[cite: 32]
- **Best Practices:** 100 / 100[cite: 32]
- **SEO:** 100 / 100[cite: 32]
- *Observación:* Vista de usuario optimizada con rendimiento perfecto en todas las métricas.
