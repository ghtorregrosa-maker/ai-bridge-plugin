# AI Bridge State Transfer Plugin

Plugin multiplataforma diseñado para empaquetar el estado lógico de una conversación de desarrollo con una Inteligencia Artificial, generando un archivo JSON de checkpoint y un prompt optimizado para que otra IA pueda continuar el desarrollo sin pérdida de contexto ni fragmentación de código.

## Características
- Extracción automática de flujos de trabajo y stack tecnológico.
- Serialización segura de estados de desarrollo en formato JSON.
- Generación de payloads de transición compatibles con cualquier LLM.

## Instalación y Ejecución (PowerShell / Bash)
```bash
git clone [https://github.com/tu-usuario/ai-bridge-plugin.git](https://github.com/tu-usuario/ai-bridge-plugin.git)
cd ai-bridge-plugin
python ai_transfer.py