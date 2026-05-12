# 🧪 Laboratorio: MS-4023 — Transform Ideas into Action with Copilot Chat

**Duración total:** 90 minutos  
**Nivel:** Principiante  
**Requisito:** Cuenta Microsoft 365 con licencia Copilot activa  
**URL de acceso:** [https://m365copilot.com](https://m365copilot.com)

---

## 🎯 Objetivo general

Aprender a utilizar Microsoft 365 Copilot Chat para potenciar la productividad diaria: desde generar contenido y estructurar documentos hasta colaborar en tiempo real y crear agentes personalizados.

---

## 🧩 Parte 1: Engagement e introducción

⏱️ **Tiempo estimado: 10 minutos**

### 🔹 Paso 1 – Preguntas de apertura

**🎯 Objetivo:** Activar conocimiento previo y conocer el nivel real de la sala.

El instructor abre con las siguientes preguntas al grupo:

> 💬 *"¿Alguien usó alguna IA esta semana? ¿Para qué?"*

> 💬 *"¿Cuántos usaron ChatGPT alguna vez? ¿Y Copilot?"*

> 💬 *"Si pudieran automatizar UNA tarea de su trabajo con IA, ¿cuál sería?"*

📝 **Nota para el instructor:** No corrijas ni des respuestas todavía. El objetivo es escuchar y calibrar la audiencia. Anotá mentalmente quién ya tiene experiencia y quién no.

---

### 🔹 Paso 2 – Encuadre de la sesión

**🎯 Objetivo:** Establecer expectativas claras.

El instructor presenta en 2 minutos:

- Qué vamos a hacer hoy (flujo completo: idea → documento → mail → colaboración → agente)
- Qué NO vamos a cubrir (configuración de tenant, administración, licenciamiento)
- Regla de la sesión: **practicamos en vivo, no miramos**

---

## 🧩 Parte 2: Tipos de Copilot

⏱️ **Tiempo estimado: 8 minutos**

### 🔹 Paso 3 – El ecosistema Copilot

**🎯 Objetivo:** Entender que "Copilot" no es una sola cosa.

El instructor explica los tres tipos principales:

| Tipo | Dónde | Para qué |
|---|---|---|
| **Copilot Web** | copilot.microsoft.com | Búsqueda web + IA general, sin datos de empresa |
| **Microsoft 365 Copilot Chat** | m365copilot.com | IA con acceso a tus datos de Microsoft 365 |
| **Copilot en apps 365** | Dentro de Word, Outlook, Teams, etc. | Asistencia contextual dentro de cada aplicación |

Y menciona que el ecosistema es más amplio:

- **GitHub Copilot** → para desarrolladores, asistente de código
- **Copilot Studio** → para crear agentes personalizados (lo veremos al final)
- **Copilot en Dynamics, Power Platform, etc.**

> 💬 Pregunta al grupo: *"¿Cuál de estos ya tenían en el radar?"*

---

## 🧩 Parte 3: Ventajas del Copilot empresarial

⏱️ **Tiempo estimado: 7 minutos**

### 🔹 Paso 4 – Por qué Copilot en tu organización es diferente

**🎯 Objetivo:** Entender los diferenciadores clave frente a IA pública.

El instructor explica los cuatro pilares:

1. **Tus datos, en tu organización** — Copilot accede a tus mails, documentos y reuniones. Nadie externo los ve.
2. **Enterprise Data Protection (EDP)** — Los datos no salen del tenant de Microsoft. Las conversaciones no se usan para entrenar modelos.
3. **Respuestas con contexto empresarial** — No responde con información genérica: responde con *tu* información.
4. **No se entrena con tu contenido** — A diferencia de muchas IAs públicas, lo que escribís no alimenta ningún modelo.

> 💬 Pregunta al grupo: *"¿Alguien tenía dudas sobre si podían usar IA con información de la empresa? ¿Qué les preocupaba?"*

---

## 🧩 Parte 4: Integración con Microsoft 365

⏱️ **Tiempo estimado: 15 minutos**

### 🔹 Paso 5 – Acceder a Copilot Chat

**🎯 Objetivo:** Todos con la herramienta abierta y funcional.

1. Ir a [https://m365copilot.com](https://m365copilot.com)
2. Iniciar sesión con la cuenta corporativa
3. Verificar que aparece el modo **Work** (no Web)

📝 **Nota para el instructor:** Esperá que todos estén dentro antes de continuar. Si alguien no puede acceder, pasá al siguiente sin detenerte.

---

### 🔹 Paso 6 – Crear un documento con Copilot en Word

**🎯 Objetivo:** Ver cómo Copilot funciona dentro de las aplicaciones de Microsoft 365.

1. Abrir **Word** (online o desktop)
2. Crear un documento en blanco
3. Usar el comando `/` para invocar Copilot dentro del documento
4. Escribir el siguiente prompt:

```
Crea un resumen de reunión con el cliente Empresa ABC sobre la propuesta de expansión regional.
Incluye: asistentes ficticios, fecha de hoy, tres puntos discutidos, dos compromisos asumidos y próximos pasos.
```

5. Guardar el documento como:  
   👉 `Reunión - Empresa ABC.docx`

📝 **Nota para el instructor:** Este documento lo vamos a usar en el siguiente bloque para generar el mail. Que todos lo tengan guardado.

---

## 🧩 Parte 5: Prompting — creamos el mail

⏱️ **Tiempo estimado: 15 minutos**

### 🔹 Paso 7 – Subir el documento a Copilot Chat

**🎯 Objetivo:** Usar un documento real como contexto para generar contenido.

1. Ir a [https://m365copilot.com](https://m365copilot.com)
2. Adjuntar el archivo `Reunión - Empresa ABC.docx` (ícono de clip)
3. Antes de escribir el prompt, el instructor explica el framework de prompting:

**Framework GCRE:**
- **G**oal — ¿Qué quiero que haga?
- **C**ontext — ¿Con qué información?
- **R**ole — ¿Desde qué perspectiva?
- **E**xpectation — ¿En qué formato lo quiero?

---

### 🔹 Paso 8 – Generar el mail

**🎯 Objetivo:** Practicar prompting efectivo con un caso real.

Cada participante escribe su propio prompt. Ejemplo de prompt bien construido:

```
Usando el documento adjunto, redactá un mail de seguimiento post-reunión para el cliente.
Tono: profesional pero cercano.
Incluí: agradecimiento por la reunión, resumen de los compromisos asumidos y próximos pasos con fechas tentativas.
Formato: asunto + cuerpo del mail. Extensión: no más de 200 palabras.
```

> 💬 Pregunta al grupo después de ver los resultados: *"¿El resultado fue lo que esperaban? ¿Qué cambiarían del prompt?"*

📝 **Práctica:** Cada participante ajusta su prompt al menos una vez con una indicación de mejora (más corto, diferente tono, agregar firma, etc.)

---

## 🧩 Parte 6: Prompt Gallery

⏱️ **Tiempo estimado: 5 minutos**

### 🔹 Paso 9 – Guardar el prompt

**🎯 Objetivo:** Aprender a reutilizar prompts efectivos.

1. Una vez que el mail quedó bien, hacer clic en los tres puntos del mensaje
2. Seleccionar **Guardar prompt** (o acceder a la Prompt Gallery desde el menú)
3. Darle un nombre descriptivo:  
   👉 `Mail de seguimiento post-reunión`
4. Explorar la Prompt Gallery de Microsoft para ver prompts predefinidos por rol

> 💬 *"¿Para qué tarea repetitiva de su día a día guardarían un prompt?"*

---

## 🧩 Parte 7: Colaboración con Copilot Pages

⏱️ **Tiempo estimado: 10 minutos**

### 🔹 Paso 10 – Editar en Pages

**🎯 Objetivo:** Ver cómo Copilot facilita la colaboración en tiempo real.

1. En la respuesta del mail generado, hacer clic en **Editar en Pages**
2. Explorar la interfaz de Pages:
   - Cambiar el título de la página
   - Modificar un párrafo específico del mail
   - Usar el comando `/` para agregar un bloque nuevo (tabla, lista, etc.)
   - **@mencionar** a un compañero para simular colaboración
3. Compartir la página con alguien del grupo

> 💬 *"¿En qué situación de trabajo real usarían esto? ¿Revisión de propuestas, documentación de proyectos?"*

📝 **Nota para el instructor:** Si Pages no está habilitado en el tenant, mostrarlo con screen sharing desde tu cuenta. No detener el flujo.

---

## 🧩 Parte 8: Creación de un agente

⏱️ **Tiempo estimado: 12 minutos**

### 🔹 Paso 11 – Crear un agente personalizado

**🎯 Objetivo:** Mostrar el nivel avanzado de personalización de Copilot.

1. En Copilot Chat, ir a **Crear agente** (ícono o menú lateral)
2. Definir el agente con el siguiente prompt de configuración:

```
Sos un asistente de seguimiento comercial. Cuando alguien te describe una reunión con un cliente,
generás automáticamente: un resumen ejecutivo, un mail de seguimiento y una lista de próximos pasos.
Usá siempre un tono profesional y estructurado.
```

3. Darle un nombre al agente:  
   👉 `Asistente Comercial`
4. Probarlo con una entrada simple:  
   *"Tuve una reunión con el cliente XYZ, hablamos de renovar el contrato y quedamos en enviar una propuesta antes del viernes."*

5. Mostrar el resultado y compararlo con lo que haríamos manualmente

> 💬 *"¿Qué agente crearían para su trabajo? ¿Qué tarea repetitiva podría tener su propio asistente?"*

---

## 🧩 Cierre y reflexión

⏱️ **Tiempo estimado: 8 minutos**

### 🔹 Paso 12 – Compromiso de aplicación

**🎯 Objetivo:** Anclar el aprendizaje con una acción concreta.

Cada participante escribe en el chat de la sesión (o en voz alta):

> *"Esta semana voy a usar Copilot para \_\_\_\_\_\_\_\_\_\_."*

---

### 🔹 Paso 13 – Recursos para continuar

**🎯 Objetivo:** Dar continuidad al aprendizaje.

| Recurso | URL |
|---|---|
| Curso oficial MS-4023 | [learn.microsoft.com/training/courses/ms-4023](https://learn.microsoft.com/en-us/training/courses/ms-4023) |
| Prompt Gallery de Microsoft | Disponible dentro de Copilot Chat |
| Adopción de Copilot | [adoption.microsoft.com/copilot](https://adoption.microsoft.com/en-us/copilot/) |

---

## ✅ Resultado esperado al finalizar

- ✔ Entendiste el ecosistema Copilot (Web, M365, en apps, GitHub Copilot)
- ✔ Conocés las ventajas del Copilot empresarial vs. IA pública
- ✔ Creaste un documento con Copilot dentro de Word
- ✔ Generaste un mail profesional con prompting efectivo
- ✔ Guardaste un prompt en la Prompt Gallery
- ✔ Exploraste la colaboración en tiempo real con Pages
- ✔ Creaste y probaste tu primer agente de Copilot

---

## ⏱️ Resumen de tiempos

| Parte | Contenido | Tiempo |
|---|---|---|
| 1 | Engagement e introducción | 10 min |
| 2 | Tipos de Copilot | 8 min |
| 3 | Ventajas del Copilot empresarial | 7 min |
| 4 | Integración con Microsoft 365 | 15 min |
| 5 | Prompting — el mail | 15 min |
| 6 | Prompt Gallery | 5 min |
| 7 | Copilot Pages | 10 min |
| 8 | Creación de agente | 12 min |
| Cierre | Reflexión y recursos | 8 min |
| **Total** | | **90 min** |
