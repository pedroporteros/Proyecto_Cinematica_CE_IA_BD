# 📽️ Cinemática: Una vida en una imagen  

Este repositorio contiene el desarrollo del proyecto titulado **"Cinemática: Una vida en una imagen"**, llevado a cabo como parte del Centro de Datos de Lanzarote, especialización en **Inteligencia Artificial y Big Data**.

El objetivo principal del proyecto es crear una solución basada en Inteligencia Artificial capaz de convertir imágenes estáticas en vídeos cortos y realistas utilizando el modelo generativo **Stable Video Diffusion (SVD)**.

---

## 📝 Información general del proyecto

- **Estudiante:** Pedro Porteros de Quintana  
- **Tutor:** Antonio Manuel Hernández de León  
- **Especialización:** Inteligencia Artificial y Big Data  
- **Fecha de finalización:** Abril 2025  

---

## 🎯 Objetivos

### General:
Implementar un sistema basado en Inteligencia Artificial capaz de convertir imágenes estáticas en vídeos cortos.

### Específicos:
- Investigar y documentar el estado del arte en generación automática de vídeos a partir de imágenes estáticas (*Image-to-Video synthesis*).
- Implementar exitosamente el modelo **Stable Video Diffusion (SVD)** optimizado para generar vídeos coherentes con al menos 50 frames.
- Desarrollar una interfaz gráfica amigable utilizando **Gradio**, que permita a usuarios sin conocimientos técnicos generar vídeos en menos de 2 minutos.

---

## 🚀 Tecnologías utilizadas

El proyecto se desarrolló usando las siguientes tecnologías y herramientas:

- **Python** (Lenguaje de programación principal)
- **Google Colab** (Entorno de desarrollo con GPU A100 60GB)
- **PyTorch** (Framework para implementación del modelo)
- **Stable Video Diffusion Pipeline (SVD-XT)** (Pipeline preentrenada de Hugging Face)
- **Gradio** (Creación de interfaz gráfica interactiva)
- **Unsplash, Pixabay, Pexels** (Fuentes de imágenes libres para dataset)

---

## 📂 Estructura del repositorio
```text
Cinematica-Una-Vida-En-Una-Imagen/
├── Cinematica_proyecto_final.ipynb   # Notebook con el código completo
├── README.md                         # Descripción general del proyecto
├── examples/                         # Ejemplos de imágenes y vídeos generados (opcional)
├── assets/                           # Imágenes para documentación o interfaz (opcional)
└── docs/                             # Documentación complementaria del proyecto (opcional)
```
---

## 🛠️ Instalación y Uso del Proyecto

1. Clona el repositorio

```bash
git clone 
```

2. Ejecuta el notebook
   
- Accede al archivo Cinematica_proyecto_final.ipynb desde Google Colab para aprovechar la GPUs de alto rendimiento (Nota: Deberás subir el notebook a tu Colab).

3. Interfaz gráfica (Gradio)
- La interfaz está implementada en el notebook. Al ejecutarla, generará una URL que puedes usar directamente para probar la aplicación y generar vídeos a partir de tus propias imágenes.

---

# 📚 Bibliografía recomendada

- [Stable Diffusion Documentation](https://huggingface.co/docs/stable-diffusion) (Hugging Face). Documentación oficial.
- [Documentación oficial de Gradio](https://gradio.app/)
- [Video Diffusion Models. Paper](https://arxiv.org/abs/2204.03458)

---

# 📌 Limitaciones actuales y futuras mejoras

- El tiempo de generación depende fuertemente de los recursos computacionales disponibles (GPU).
- En futuras actualizaciones, se planea optimizar la eficiencia computacional para alcanzar tiempos de procesamiento cercanos al tiempo real y explorar la integración en plataformas móviles y web.























   
