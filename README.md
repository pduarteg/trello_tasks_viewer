# 📋 Visor de Tareas desde Trello

Esta es una pequeña aplicación web que permite **visualizar tarjetas (cards) de Trello** en formato de tabla.  
Su objetivo es convertir un **JSON exportado desde Trello** en una tabla interactiva para facilitar la lectura y análisis de tareas.

---

## 🚀 Funcionalidades

- 📂 **Carga de archivo JSON** desde Trello.
- 🖊 **Opción de pegar el JSON** manualmente en un área de texto.
- 🔍 **Búsqueda rápida** por nombre o número de tarjeta (`idShort`).
- 📊 **Tabla dinámica** con columnas para:
  - Número de tarjeta
  - Nombre de la card
  - Lista a la que pertenece
  - Fecha de inicio
  - Fecha de vencimiento
  - Estado (Completada, Pendiente, Vencida)
  - Enlace directo a Trello
- 💾 **Descarga en CSV** de la tabla filtrada.

---

## 🛠 Uso

1. **Exporta tu JSON desde Trello** (puedes usar Power-Ups o API).
2. **Abre la página web**.
3. Haz clic en **"📂 Seleccionar archivo"** o pega el contenido del JSON en el área de texto.
4. Presiona **"Convertir archivo a tabla"** para visualizar las cards.
5. (Opcional) Usa la **barra de búsqueda** para filtrar resultados.
6. Si lo deseas, descarga los resultados en CSV con el botón **"Descargar CSV"**.

---

## 🖼 Vista previa

Ejemplo de la tabla generada:

| #   | Card              | Lista      | Inicio            | Vence            | Estado      | Enlace |
|-----|------------------|-----------|------------------|----------------|-----------|--------|
| 123 | Implementar login| Backlog   | 2025-09-18 10:00 | 2025-09-25 17:00| Pendiente | [Ver](https://trello.com/c/xxxxx) |

---

## 💻 Tecnologías utilizadas

- **HTML5 + CSS3 + JS puro**

---

## 🌐 Despliegue

El sitio está publicado en **GitHub Pages**, por lo que puedes accederlo en:  
