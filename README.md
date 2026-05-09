# 🏃 Scrum & Kanban Quiz

Quiz interactivo para repasar conceptos de Scrum y Kanban, desarrollado como actividad práctica del **Scrum Professional Bootcamp** — Comisión SP1 2026.

---

## 🎯 ¿De qué se trata?

Un juego de preguntas de opción múltiple basado en **situaciones reales de un equipo de desarrollo**. Cada pregunta plantea un escenario concreto y el jugador debe elegir la respuesta correcta en 20 segundos.

Al finalizar, se muestra el puntaje total y un desglose por categoría para identificar qué temas necesitan más repaso.

---

## 📚 Categorías

| Categoría | Color | Preguntas |
|---|---|---|
| Sprint | 🔵 Celeste | 2 |
| Daily | 🟢 Verde | 2 |
| Planning | 🟠 Naranja | 2 |
| Review | 🟣 Violeta | 1 |
| Retro | 🩷 Rosa | 1 |
| Kanban | 🩵 Teal | 4 |
| Scrum Master | 🟡 Amarillo | 3 |

**Total: 15 preguntas**

---

## 🚀 ¿Cómo usar?

No requiere instalación ni dependencias. Solo abrí el archivo en el navegador:

```bash
# Clonar el repo
git clone https://github.com/tu-usuario/scrum-kanban-quiz.git

# Abrir el archivo
cd scrum-kanban-quiz
open index.html
```

O simplemente descargá el archivo `index.html` y hacé doble clic.

---

## 🌐 GitHub Pages

También podés publicarlo con GitHub Pages para acceder desde cualquier dispositivo:

1. Ir a **Settings** del repositorio
2. Sección **Pages**
3. En *Source*, seleccionar `main` y carpeta `/ (root)`
4. Guardar — en unos minutos estará disponible en `https://tu-usuario.github.io/scrum-kanban-quiz`

---

## 🛠️ Tecnologías

- HTML5
- React 18 (vía CDN)
- Babel Standalone (vía CDN)
- CSS en línea

Sin bundlers, sin `npm install`, sin configuración.

---

## ✏️ ¿Cómo agregar preguntas?

Abrí `index.html` y buscá el array `questions`. Cada pregunta tiene esta estructura:

```js
{
  category: "Sprint",         // Categoría (debe estar en categoryColors)
  question: "¿Tu pregunta?",  // Enunciado
  options: [                  // Exactamente 4 opciones
    "Opción A",
    "Opción B",
    "Opción C",
    "Opción D",
  ],
  correct: 1,                 // Índice de la respuesta correcta (0-3)
  explanation: "Explicación que aparece después de responder.",
}
```

---

## 👥 Equipo

Desarrollado por el equipo de la **Comisión SP1 2026** como parte de las actividades del Scrum Professional Bootcamp de Rolling Code School.

- Facundo López
- Lucía David
- Juan Ignacio Burgos
- Noelia Sotelo Bertini
- Nadia Medina
