# Suyay · Coach Académico FIIS-UNI — Demo interactiva

Demo web interactiva del agente **Suyay** 🌱 ("esperanza" en quechua), un coach
académico por WhatsApp para estudiantes de ingeniería de la **UNI-FIIS**,
construido con **Claude**.

🔗 **Probar la demo:** https://unimauro.github.io/agente-uni-demo/

## Qué hace

Conversas con Suyay como uno de 4 alumnos ficticios y el agente:

- 📊 te muestra tus notas del curso,
- 🎯 calcula **cuánto necesitas en el examen final** para aprobar
  (fórmula real: `NF = (3 mejores PC + EP + 2·EF) / 6`, aprueba con `NF ≥ 10`),
- ⏰ te recuerda tus próximas evaluaciones,
- 💬 te acompaña con tono cálido y peruano cuando la carrera pesa (incluido el caso TRICA),
- 🌱 te reconecta con tu propósito.

## Importante

Esta es una **demo del lado del cliente**: las respuestas son **simuladas** en el
navegador, **sin servidor, sin Claude API y sin Twilio**. Los alumnos y notas son
**ficticios** — no hay ningún dato personal real. El bot completo (Express + SQLite +
Claude Haiku 4.5 + WhatsApp/Twilio) vive en un repositorio privado.

## Proyecto

Parte del proyecto **Modelo Predictivo IA · UNI-FIIS** — modelo de alerta temprana
del rendimiento y la deserción académica.

- 🖥️ Exposición: https://unimauro.github.io/modelo-predictivo-uni/
- 👤 Autor: [Carlos Mauro Cárdenas Fernández](https://unimauro.github.io/)
