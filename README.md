# Generador de Casos de Prueba

Herramienta web que genera casos de prueba QA (positivos, negativos y de borde)
a partir de Historias de Usuario usando IA local con Ollama. Sin API key ni costos externos.

## Archivos
- `generador_casos_prueba.html` — interfaz web
- `proxy.py` — servidor local que conecta el HTML con Ollama

## Requisitos
- Python 3
- Ollama instalado y corriendo

## Uso
```bash
ollama pull llama3.2
python proxy.py
```
Abrir http://localhost:8080
