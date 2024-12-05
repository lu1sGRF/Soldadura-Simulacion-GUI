# Soldadura-Simulacion-GUI

**Soldadura-Simulacion-GUI** es una herramienta intuitiva que facilita la simulación de procesos de soldadura. Desarrollada como una interfaz gráfica (GUI), permite a los usuarios gestionar archivos de entrada, configurar simulaciones con **CalculiX** y visualizar los resultados en **ParaView**.

La aplicación está diseñada para investigadores, estudiantes y profesionales que trabajan con simulaciones en ingeniería mecánica y procesos térmicos. Ofrece opciones para analizar resultados, convertir formatos y simplificar flujos de trabajo en proyectos complejos.

---

## 🎥 Video de Demostración

[![Video de Demostración](https://img.youtube.com/vi/VIDEO_ID/maxresdefault.jpg)](https://www.youtube.com/watch?v=VIDEO_ID)

---

## ✨ Características

- Interfaz gráfica fácil de usar.
- Gestión automática de carpetas y archivos para simulaciones (`Input`, `Run` y `Results`).
- Configuración de ejecutables de **CalculiX** y **ParaView**.
- Ejecución de simulaciones con opciones de log.
- Conversión automática de archivos `.frd` a `.vtu`.
- Visualización de resultados con ParaView.
- Validación automática de archivos `.inp` (ASCII o binario).
- Manejo de errores con mensajes claros y detallados para el usuario.

---

## 📂 Estructura de Carpetas

Durante el uso de la herramienta, se generan las siguientes carpetas:
- **Input:** Almacena los archivos de entrada seleccionados.
- **Run:** Contiene los archivos generados durante la simulación.
- **Results:** Guarda los archivos convertidos listos para visualizar en ParaView.

---

## 📦 Cómo Descargar y Usar

### 1. Descargar el ejecutable
- Ve a la sección **Releases** de este repositorio: [Releases](https://github.com/tu_usuario/Soldadura-Simulacion-GUI/releases).
- Descarga la última versión del archivo `.exe`.

### 2. Ejecutar la aplicación
- No necesitas instalar Python ni dependencias.
- Solo ejecuta el archivo `.exe` descargado.
- Sigue las instrucciones dentro de la aplicación para realizar tus simulaciones.

---

## 🛠️ Si deseas trabajar con el código fuente

### Requisitos
1. **Python**: 3.8 o superior.
2. **Bibliotecas de Python**:
   - `customtkinter`
   - `flask`
3. **Software adicional**:
   - **CalculiX**: Necesitas el ejecutable `ccx.exe`.
   - **ParaView**: Necesitas el ejecutable para la visualización.

### Instalación del código fuente
1. **Clona este repositorio**:
   ```bash
   git clone https://github.com/tu_usuario/Soldadura-Simulacion-GUI.git
   cd Soldadura-Simulacion-GUI
