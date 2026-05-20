# 🚗 Urban Routes — Pruebas Web & Funcionales

Pruebas manuales de la funcionalidad **Compartir Automóvil** de Urban Routes en múltiples entornos y navegadores.

[![Manual Testing](https://img.shields.io/badge/Manual%20Testing-007ACC?style=for-the-badge)]()
[![JIRA](https://img.shields.io/badge/JIRA-0052CC?style=for-the-badge&logo=jira&logoColor=white)](https://www.atlassian.com/software/jira)
[![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=for-the-badge&logo=google-sheets&logoColor=white)]()
[![Cross Browser](https://img.shields.io/badge/Cross--Browser%20Testing-FF8C00?style=for-the-badge)]()

---

## 📋 Descripción del proyecto

Urban Routes es una aplicación web que calcula rutas, duración y precios para distintos medios de transporte. En este proyecto se validó la funcionalidad de **Compartir Automóvil**, analizando requisitos y diseños en Figma, y ejecutando pruebas en dos entornos:

| Entorno | Navegador | Resolución |
|---|---|---|
| Entorno 1 | Google Chrome | 800 x 600 |
| Entorno 2 | Mozilla Firefox | 1920 x 1080 |

---

## 🎯 Objetivos

- Validar que el diseño del formulario de reserva coincidiera con los requisitos
- Probar la funcionalidad de las ventanas "Método de pago" y "Agregar tarjeta"
- Diseñar y ejecutar casos de prueba para el botón "Reservar" y el flujo completo de reserva
- Reportar bugs en Jira con documentación y evidencia de respaldo

---

## 🛠️ Herramientas utilizadas

| Herramienta | Uso |
|---|---|
| **Google Chrome / Firefox** | Ejecución de pruebas cross-browser |
| **Google Sheets** | Listas de comprobación y casos de prueba |
| **Jira** | Reporte y seguimiento de bugs |
| **Figma** | Revisión de diseños UI |

---

## 🔍 Alcance de las pruebas

### 1. Lista de comprobación — Diseño del formulario de reserva
- Verificación visual: ortografía, disposición de elementos y apariencia
- Validación del mapa de navegación central
- Pruebas en ambos entornos (Chrome y Firefox)
- Ventanas emergentes: "Automóvil reservado", "¿Seguro que quieres cancelar?" y "Viaje cancelado"

### 2. Lista de comprobación — "Método de pago" y "Agregar tarjeta"
- Técnicas aplicadas: **Partición de clases de equivalencia** y **Análisis de valores límite**
- Pruebas positivas y negativas para cada campo

### 3. Casos de prueba — Botón "Reservar"
- Validación de condiciones de activación del botón
- Verificación del texto informativo (distancia y duración del viaje)
- Pruebas positivas y negativas

### 4. Casos de prueba — Flujo completo de reserva
- Flujo end-to-end de la reserva de automóvil compartido
- Validación de lógica de negocio según requisitos

---

## 📊 Resultados

| Entregable | Detalle |
|---|---|
| Lista de comprobación de diseño | ✅ Ejecutada en Chrome y Firefox |
| Lista de comprobación Método de pago | ✅ Con clases de equivalencia y valores límite |
| Casos de prueba botón "Reservar" | ✅ Positivos y negativos |
| Casos de prueba reserva completa | ✅ Positivos y negativos |
| Bugs reportados en Jira | ✅ Con evidencia y pasos para reproducir |

---

## 📁 Estructura del repositorio

```
qa-urban-routes-web/
├── 📄 README.md
├── 📁 checklists/
│   ├── 01-diseno-formulario-reserva.md
│   └── 02-metodo-pago-agregar-tarjeta.md
├── 📁 test-cases/
│   ├── 03-casos-boton-reservar.md
│   └── 04-casos-reserva-completa.md
├── 📁 bug-reports/
│   └── bugs-encontrados.md
└── 📁 evidence/
    ├── chrome-800x600/      ← https://drive.google.com/drive/folders/1VpAdy5Byfjurq6XZ0x3ge0M4aMtDmwP3?usp=drive_link
    └── firefox-1920x1080/   ← https://drive.google.com/drive/folders/1VpAdy5Byfjurq6XZ0x3ge0M4aMtDmwP3?usp=drive_link
```

---

## 🐞 Proceso de reporte de bugs en Jira

Cada bug reportado incluye:
- **Título** — descripción clara del defecto
- **Entorno** — navegador y resolución donde se detectó
- **Pasos para reproducir** — numerados y detallados
- **Resultado esperado** — según requisitos o diseño en Figma
- **Resultado actual** — comportamiento incorrecto observado
- **Evidencia** — capturas de pantalla del defecto
- **Severidad / Prioridad** — clasificación del impacto

---

## 🔧 Técnicas de testing aplicadas

- **Partición de clases de equivalencia** — agrupar valores válidos e inválidos para reducir casos redundantes
- **Análisis de valores límite** — probar en los extremos de los rangos permitidos
- **Pruebas de diseño UI** — comparación visual contra diseños en Figma
- **Cross-browser testing** — validación en dos navegadores con distintas resoluciones

---

## 📎 Recursos adicionales

- 📂 [Hoja de cálculo completa en Google Sheets](#) ← *(https://docs.google.com/spreadsheets/d/1BBJNZkpSITBHjIVGXV9larGiAn5CvJBV/edit?usp=drive_link&ouid=114380237435694438896&rtpof=true&sd=true)*
- 🎨 [Diseños en Figma](https://www.figma.com/file/I6nSmK36O9DINiDCYZsZeS/Urban-Routes-ES)

---

## 👤 Autor

**Josafat Gabriel Hernandez Rizo**
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Perfil-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/josafatgabrielhernandezrizo)
[![Gmail](https://img.shields.io/badge/Gmail-Contacto-D14836?style=flat-square&logo=gmail)](mailto:josafatgabrielhernandezrizo@gmail.com)
