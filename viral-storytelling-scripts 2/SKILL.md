---
name: viral-storytelling-scripts
description: Use this skill whenever the user wants to create a viral short-form video script (Instagram Reels, TikTok, YouTube Shorts) anchored in a personal story. Triggers include any mention of "script", "guion", "Reel", "historia para video", "ayúdame con un video", "convierte esto en script", or when the user shares a personal anecdote/experience and wants it turned into content. Also trigger when the user wants hook variations, CTAs, or to apply storytelling frameworks (South Park rule, 6 senses, 4 C's, 4 Horsemen) to their content. Optimized for 45-90 second Spanish-language scripts for entrepreneurs/AI-content creators, but works for any niche. ALWAYS use this skill when Mateo shares a story and wants script output — never invent hooks from scratch, always use the curated bank.
---

# Viral Storytelling Scripts

Sistema integral para transformar historias personales en scripts virales de 45-90 segundos, combinando un banco curado de 100 hooks con los frameworks narrativos de Caleb Ralston, Kallaway y Vinh Giang.

## Cuándo se activa esta skill

El usuario comparte una historia, experiencia, anécdota o aprendizaje real y quiere convertirlo en script. Ejemplos:
- "Hice una skill que se viralizó, ayúdame con el script"
- "Ayer me pasó algo en una llamada con cliente, hagamos contenido"
- "Tengo esta idea, conviértela en Reel"
- "Necesito un script de 60 segundos sobre X"

## Reglas no negociables

Estas reglas siempre se aplican y **nunca se rompen** sin importar lo que pida el usuario en el momento:

1. **Los hooks SOLO vienen del banco curado.** Nunca inventes hooks nuevos. Si ningún hook del banco encaja, dilo y pide al usuario que comparta más contexto. Lee `references/hooks-bank.md` siempre.
2. **El hook "Tengo una confesión que hacer" está prohibido.** No lo uses ni lo sugieras.
3. **La historia real es el ancla.** Si el usuario no comparte una historia, experiencia o aprendizaje específico suyo, **detente y pídela**. No escribas scripts genéricos.
4. **Sin referencias a cámara/filmar.** El contenido es generado con IA, no se filma. Nunca digas "como ves en cámara", "estoy grabando", "mira detrás de mí", etc.
5. **Sin lenguaje de marketing inflado.** Nada de "transforma tu vida", "el secreto definitivo", "increíble método". Tono directo, casual, conversacional.
6. **Español casual, registro hablado.** Como si lo dijera una persona real en una conversación, no como anuncio.
7. **45-90 segundos = 120-220 palabras.** No te pases. Si la historia da para más, propón cortarla en varios scripts.

## Flujo todo-en-uno

Cuando el usuario comparta una historia, ejecuta estos pasos **en una sola respuesta**:

### Paso 1 — Filtra la idea con los 4 Jinetes (silencioso, mental)

Antes de escribir, valida internamente que la historia pasa los 4 filtros (lee `references/algorithm-filter.md` para detalles):

1. **Relevancia** — ¿resuelve un problema real del público?
2. **No-obviedad** — ¿aporta perspectiva nueva?
3. **Absorción** — ¿se entiende en una pasada?
4. **Distancia de implementación** — ¿se puede actuar hoy?

Si la historia falla en alguno, **díselo al usuario** y sugiere cómo reframearla antes de continuar. No escribas un script que no pase los 4 filtros.

### Paso 2 — Selecciona 3 hooks del banco

Lee `references/hooks-bank.md` y elige **3 hooks de 3 categorías distintas** que encajen con la historia. Cada uno representa un ángulo emocional diferente:

- 1 hook de **curiosidad** o **autoridad** (intriga/credibilidad)
- 1 hook de **identificación/dolor** o **transformación** (conexión emocional)
- 1 hook de **controversia** o **comparación** (postura/contraste)

Si la historia es claramente narrativa, también puedes incluir uno de la categoría **storytelling**.

Adapta los `___` a las variables específicas de la historia. Mantén exactamente la estructura del hook del banco — no la modifiques.

### Paso 3 — Aplica el framework narrativo al cuerpo

Lee `references/narrative-framework.md` y construye el cuerpo del script aplicando:

- **Estructura 4 C's** en los primeros 15 segundos (Call out → Credibility → Compass → Core Learning)
- **Regla South Park** — reemplaza los "y luego" por "pero" / "por lo tanto" para crear tensión
- **6 sentidos** — convierte momentos clave en presente activando vista, sonido, emoción, tacto
- **Banco de Credibilidad** — inyecta UN dato concreto que valide por qué el usuario tiene autoridad para hablar del tema
- **Puente del Significado** — cierra la historia con "La razón por la que te cuento esto es..." para conectar con el aprendizaje

### Paso 4 — Construye el CTA

El CTA típico de Mateo es: comentar una palabra clave para recibir un recurso (skill, guía, link a comunidad). Si el usuario no especifica el recurso, **pregúntalo al final** o sugiere uno basado en el tema del script.

Estructura del CTA en 1-2 frases:
- Beneficio claro de lo que reciben
- Acción específica ("comenta [palabra]")

### Paso 5 — Entrega el output con el formato del template

Usa el formato exacto de `assets/output-template.md`. El entregable incluye:

1. **3 hooks variantes** (de 3 categorías distintas, con la categoría etiquetada)
2. **Hook recomendado** (señala cuál crees que funciona mejor y por qué — 1 frase)
3. **Script completo** con timestamps aproximados (0:00-0:05, 0:05-0:15, etc.)
4. **CTA** integrado al final del script
5. **Notas de aplicación** — qué frameworks se aplicaron y dónde (1-2 líneas, breve)

## Sobre el Banco de Credibilidad

El usuario (Mateo) tiene autoridad en estos temas que puedes usar para inyectar credibilidad cuando encajen con la historia:

- Crea contenido sobre Claude AI y skills desde hace meses
- Tiene una agencia de contenido AI
- Creó un AI influencer (Santi Salinas) que se viralizó tempranamente
- Hace Reels constantemente sobre productividad con IA
- Tiene comunidad activa de gente interesada en IA

Si la historia da pie para mencionar uno de estos puntos, hazlo de forma natural. **Nunca inventes credenciales que no estén aquí.** Si necesitas un dato específico (números, fechas, casos), pregúntale al usuario.

## Cuando la historia no es suficiente

Si el usuario comparte algo demasiado vago ("hice un video que funcionó bien", "tuve una idea"), pide:

1. ¿Qué pasó exactamente? (el evento concreto)
2. ¿Qué sentiste o pensaste en ese momento?
3. ¿Qué aprendiste o qué cambió después?
4. ¿A quién quieres ayudar contando esto?

Sin estas 4 piezas, no escribas el script. Pregunta primero.

## Iteración

Después del primer entregable, el usuario suele pedir ajustes. Aplica los siguientes patrones:

- **"Otro hook"** → ofrece 2 más del banco, de categorías que no usaste todavía
- **"Más corto"** → reduce el cuerpo, mantén la estructura 4 C's
- **"Más historia, menos lección"** → expande la sección de los 6 sentidos, acorta el cierre
- **"Cambia el tono"** → reescribe manteniendo la misma estructura, ajusta vocabulario
- **"Hazlo más controversial"** → cambia el hook a categoría Controversia y refuerza la postura del Puente del Significado

Nunca reescribas todo desde cero si el usuario pide un ajuste puntual. Modifica solo lo necesario.

## Referencias

- `references/hooks-bank.md` — Banco completo de 100 hooks por categoría (siempre consultar antes del paso 2)
- `references/narrative-framework.md` — South Park, 6 sentidos, 4 C's, Puente del Significado (consultar antes del paso 3)
- `references/algorithm-filter.md` — 4 Jinetes del Engagement, ingeniería de comentarios (consultar antes del paso 1)
- `assets/output-template.md` — Formato exacto del entregable final
