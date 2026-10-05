# Fundamentos de LLMs

> Notas de estudio en español sobre cómo funcionan los modelos de lenguaje grandes (LLMs), desde los conceptos básicos hasta la arquitectura Transformer y GPT-2.

## Tabla de contenidos

- [Para quién es](#para-quién-es)
- [Qué vas a aprender](#qué-vas-a-aprender)
- [Contenido](#contenido)
- [Cómo usar este repositorio](#cómo-usar-este-repositorio)
- [Requisitos](#requisitos)
- [Fuentes](#fuentes)
- [Contribuir](#contribuir)
- [Licencia](#licencia)

## Para quién es

Personas que usan LLMs y quieren entender qué ocurre por dentro, sin quedarse en la superficie.

## Qué vas a aprender

- Qué es un LLM y en qué se diferencia de la IA tradicional.
- Cómo el texto se convierte en tokens, vocabulario y contexto.
- Cómo funcionan la atención y la arquitectura Transformer.
- Cómo se implementa GPT-2 en código.

## Contenido

El repositorio está en construcción. Las lecciones se publican a medida que están listas.

Estado: **Completo**, **En progreso** o **Pendiente**.

- 00. Roadmap: Pendiente
  - Ruta de desarrollador web
  - Ruta fullstack
  - Ruta de AI engineer
  - Qué aprender y qué ignorar
- 01. Introducción a los LLMs: Pendiente
  - Qué es un LLM
  - Conceptos clave
  - Historia de los LLMs
  - LLM vs IA tradicional
  - Tipos de modelos
- 02. Fundamentos del lenguaje: Pendiente
  - Tokens y tokenización
  - Vocabulario
  - Contexto y ventana de contexto
- [03. Redes neuronales](contenido/03-redes-neuronales/): En progreso
  - Qué es un Transformer
  - Atención, masked attention y multi-head attention
  - Q, K y V
  - Positional encoding y RoPE
  - Arquitectura de GPT-2
  - Ejemplo disponible: [implementación de GPT-2](contenido/03-redes-neuronales/ejemplos/) en script y notebook

## Cómo usar este repositorio

Sigue los módulos en orden numérico. Cada módulo reúne sus lecciones y sus ejemplos dentro de `contenido/NN-modulo/`. El notebook de GPT-2 se puede abrir directamente en Google Colab.

## Requisitos

- Python 3 con PyTorch y NumPy. El notebook instala `einops` y `xformers`.

## Fuentes

Sección por completar con los cursos, videos y canales en los que se basa el contenido.

## Contribuir

Se aceptan correcciones y aportes. Lee [`CONTRIBUTING.md`](CONTRIBUTING.md).

## Licencia

- Código: [MIT](LICENSE).
- Contenido: [CC BY 4.0](LICENSE-CONTENT.md).
