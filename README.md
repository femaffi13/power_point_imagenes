# Ordenar Imágenes y Crear Presentación PowerPoint

Este repositorio contiene un script que lee imágenes cargadas dentro de una carpeta llamada `imagenes` y las ordena en función de su fecha. La imagen más reciente será la última diapositiva en una presentación de PowerPoint y la fecha más antigua será la primera diapositiva. Esto es útil para ver una clase y tomar capturas de pantalla, luego con este código puedes armar una presentación `.pptx` con las capturas realizadas.

## Características

- **Lectura de imágenes:** El script lee todas las imágenes en la carpeta `imagenes`.
- **Ordenamiento por fecha:** Las imágenes se ordenan según su fecha.
- **Generación de presentación:** Crea una presentación de PowerPoint con las imágenes ordenadas, la más antigua siendo la primera diapositiva y la más reciente la última.

## Requisitos

- Python 3.x
- Paquetes necesarios listados en `requirements.txt` (pueden incluir bibliotecas como `Pillow` y `python-pptx`)

## Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/femaffi13/power_point_imagenes.git
   cd power_point_imagenes

2. Instala los requisitos:
   ```bash
   pip install -r requirements.txt

## Uso

1. Coloca tus imágenes en la carpeta imagenes.
2. Ejecuta el script principal main.py.
3. La presentación de PowerPoint se generará en el mismo directorio.


## Contribución

Si deseas contribuir a este proyecto, por favor realiza un fork del repositorio y envía un pull request con tus cambios.