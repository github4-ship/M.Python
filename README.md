# M.Python



# Proyecto de Aplicación Interactiva con Streamlit

Este repositorio contiene una aplicación interactiva desarrollada con Streamlit que incluye:
- Sistema de autenticación con usuario y contraseña.
- Menú lateral para navegación entre páginas.
- Conexión a múltiples fuentes de datos (simuladas en este prototipo).
- Visualización de tablas interactivas y opciones de exportación.

## Requisitos Previos

1. Tener Python 3.8 o superior instalado.
2. Instalar las dependencias listadas en `requirements.txt`.

## Instalación Local

Sigue estos pasos para ejecutar la aplicación en tu máquina local:

1. Clona este repositorio:
   ```bash
   git clone https://github.com/github4-ship/M.Python.git
   cd M.Python
   ```

2. (Opcional) Crea un entorno virtual y actívalo:
   - **Windows**:
     ```bash
     python -m venv env
     .\env\Scripts\activate
     ```
   - **macOS/Linux**:
     ```bash
     python3 -m venv env
     source env/bin/activate
     ```

3. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
   ```

4. Ejecuta la aplicación:
   ```bash
   streamlit run app.py
   ```

5. Abre el navegador en el enlace proporcionado (por defecto: `http://localhost:8501`).

## Publicación en Streamlit Cloud

1. **Sube este repositorio a tu cuenta de GitHub**.
2. Ve a [Streamlit Cloud](https://streamlit.io/cloud) e inicia sesión con tu cuenta de GitHub.
3. Selecciona "New App" y conecta este repositorio.
4. Configura el archivo principal como `app.py` y haz clic en "Deploy".
5. Copia el enlace público generado y compártelo.

## Uso de la Aplicación

1. Inicia sesión con las credenciales:
   - **Usuario:** admin
   - **Contraseña:** admin
2. Navega entre las páginas:
   - Página 1: Muestra datos simulados de una base SQL.
   - Página 2: Muestra datos simulados de una API externa.

## Estructura del Proyecto

```
.
├── app.py               # Archivo principal de la aplicación
├── common
│   └── utils.py         # Funciones comunes como autenticación y carga de datos
├── .streamlit
│   └── config.toml      # Configuración de tema para la aplicación
├── requirements.txt     # Lista de dependencias
├── README.md            # Guía del proyecto
```

