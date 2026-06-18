# 🛡️ Talleres Prácticos — Ciberseguridad para Centros Ferreteros

**pumarino.cl · AI Secure Labs**  
Sergio Leiva Martínez — Consultor Senior en Ciberseguridad

---

## 🔐 Acceso protegido por clave

Este sitio tiene una pantalla de acceso con contraseña.

**Clave por defecto:** `ferreteros2026`

> ⚠️ **Importante:** Esta es una protección básica (disuasoria), no seguridad robusta de nivel empresarial. Cualquier persona con conocimientos técnicos podría ver el código fuente del navegador y encontrar la lógica de validación. Es adecuada para filtrar el acceso casual de quienes no tienen el enlace y la clave — no la uses para proteger información confidencial real.

### Cómo cambiar la clave

1. Abre `generador_clave.html` en tu navegador (incluido en este paquete)
2. Escribe la nueva clave que darás a tus alumnos
3. Copia el código generado (algo como `const PWG_HASH = "...";`)
4. En GitHub, abre `index.html` → clic en el ícono de lápiz ✏️ (editar)
5. Busca la línea `const PWG_HASH = "..."` y reemplázala por la que copiaste
6. Guarda los cambios ("Commit changes") — la nueva clave estará activa en 1-2 minutos

---

## 🎯 ¿Qué contiene este recurso?

Tres talleres prácticos e interactivos diseñados para capacitaciones presenciales o remotas en ciberseguridad, orientados a equipos de trabajo de centros ferreteros y comercio en general.

### 🎣 Taller A — Simulacro de Phishing
- **6 correos electrónicos** realistas para identificar como legítimos o phishing
- Incluye ataques de: SII falso, fraude BEC (cambio de cuenta bancaria), suplantación de Microsoft 365 y **typosquatting** (dominio casi idéntico al real)
- Pistas ocultas al pasar el cursor · Marcador de puntaje · Explicaciones detalladas

### 🔑 Taller B — Auditoría Express de Contraseñas
- Evaluador de contraseñas en tiempo real con 7 criterios de seguridad
- Tabla comparativa de contraseñas débiles vs seguras con tiempos de crackeo
- Recomendaciones de gestores de contraseñas

### 📋 Taller C — Mapa de Activos Críticos
- Formulario interactivo para identificar activos de información de la empresa
- Clasificación por nivel de impacto (Alto / Medio / Bajo)
- Resumen de riesgo y medidas de protección propuestas

---

## 🚀 Cómo usar

### Online (recomendado para capacitaciones)
Comparte el link de GitHub Pages **junto con la clave de acceso** a tus participantes:
```
https://TU-USUARIO.github.io/NOMBRE-REPOSITORIO
```
Cada participante ingresa la clave una vez por sesión de navegador (no se la vuelve a pedir hasta que cierre la pestaña).

### Sin internet (sala con proyector)
Descarga `index.html` y ábrelo directamente en Chrome o Edge. Funciona sin conexión excepto por la fuente tipográfica. La clave funciona igual.

---

## 📋 Instrucciones por taller

| Taller | Duración | Participantes | Modalidad |
|--------|----------|---------------|-----------|
| A — Phishing | ~5 min | 3–6 voluntarios | Grupal proyectado o individual en dispositivo |
| B — Contraseñas | ~5 min | Individual | Cada participante en su dispositivo |
| C — Activos Críticos | ~5 min | Grupos de 2 | Un dispositivo por grupo |

---

## 📁 Archivos incluidos

- `index.html` — El sitio completo con los 3 talleres y pantalla de clave
- `generador_clave.html` — Herramienta para generar nuevas claves de acceso
- `.nojekyll` — Archivo técnico requerido por GitHub Pages (no eliminar)
- `README.md` — Este archivo

---

## 🔖 Marcos de referencia

- **ISO 27001:2022** — Sistema de Gestión de Seguridad de la Información
- **NIST CSF 2.0** — Marco de Ciberseguridad
- **ISO 27035** — Respuesta ante Incidentes
- **ISO 27032** — Ciberseguridad en el Ciberespacio
- **Ley 21.719** — Protección de Datos Personales (Chile)
- **Ley 21.663** — Ley Marco de Ciberseguridad (Chile)

---

## 📞 Contacto

**pumarino.cl** · contacto@pumarino.cl · www.pumarino.cl  
**AI Secure Labs** · sergio@aisecurelabs.com · www.aisecurelabs.com

---

*Material de uso educativo. Prohibida su reproducción comercial sin autorización.*
