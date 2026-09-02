# 🤖 Jarvis - Asistente Personal IA

Tu asistente personal todo-en-uno al estilo Jarvis: responde preguntas, redacta textos, organiza tareas, busca informacion en internet, lee y escribe archivos, ejecuta comandos y crea sitios web completos. Ejecuta con autonomia plena y sin pedir confirmaciones.

## 🚀 Como usarlo

### Opcion 1: OpenHands Cloud (gratis, recomendado)

Tu cuenta de OpenHands Cloud ya tiene Jarvis disponible. Para usarlo:

1. Entra a https://app.all-hands.dev (inicia sesion con tu cuenta)
2. Conecta este repositorio de GitHub (o usa el que ya tienes)
3. Crea una nueva conversacion y pidele a Jarvis cualquier cosa, por ejemplo:
   - "Crea un sitio web para mi negocio"
   - "Busca en internet los precios de X"
   - "Organiza mis tareas para esta semana"

### Opcion 2: Local (gratis, 100% privado)

1. Instala OpenHands en tu computadora ( (https://docs.openhands.dev))
2. Configura tu OpenHands LLM Key como variable de entorno:
   ```bash
   export LLM_API_KEY="sk-oh-TU-CLAVE-AQUI"
   ```
   (Reemplaza por tu clave real, que obtienes en https://app.all-hands.dev/settings/api-keys)
   **Nunca pegues tu clave en archivos del repositorio** — usala solo como variable de entorno o en el UI de OpenHands. 
3. Clona este repositorio
4. Abre OpenHands en la carpeta del proyecto y habla con Jarvis


## 📂 Estructura

```
.
├── README.md          # Este archivo
└── .agents/
    └── agents/
        └── jarvis.md   # El asistente Jarvis (agente de OpenHands)
```

## 🧠 Que puede hacer Jarvis

| Habilidad | Ejemplo |
|---|---|
| 💬 Responder preguntas | "Explicame que es un API REST" |
| ✍️ Redactar textos y correos | "Escribeme un correo formal para pedir vacaciones" |
| 📋 Organizar tareas | "Organiza mi semana" |
| 🌐 Buscar en internet | "Busca los precios de X y resumemelo" |
| 📁 Leer y editar archivos | "Leeme este documento y resumemelo" |
| 💻 Ejecutar comandos | "Instala las dependencias de este proyecto" |
| 🎨 Crear sitios web | "Crea una pagina de presentacion para mi negocio" |

## 🔧 Personalizar

Edita el archivo `.agents/agents/jarvis.md` para cambiar su personalidad, agregar habilidades o ajustar su nivel de autonomia. Jarvis se escanea al inicio de cada conversacion, asi que los cambios toman efecto en conversaciones nuevas.

---

Hecho con ❤️ por un asistente IA (OpenHands) en nombre de rodriguezcaceres615-# ¡Jarvis, al servicio!