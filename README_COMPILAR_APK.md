# Saludos 3D Estilo Pixar - Jesús (8:00 a. m. y 10:00 p. m.)

Proyecto Android nativo (Kotlin) que incluye:
- **Personaje 3D animado estilo Pixar** renderizado a 60 FPS (`assets/character3d.html`) con sombreado volumétrico, ojos grandes expresivos con reflejos especulares, parpadeo natural, respiración, saludo con la mano, seguimiento táctil con la mirada y **sincronización labial (lip-sync) en tiempo real**.
- **Escenarios dinámicos Día/Noche:** Cielo soleado cálido para las **8:00 a. m.** y noche estrellada con luna para las **10:00 p. m.**
- **Voz Masculina en Español:** Configurada mediante el motor `TextToSpeech` de Android seleccionando voces masculinas en español y ajuste de timbre (`pitch`) personalizable.
- **Notificaciones Diarias Exactas:** Programadas automáticamente todos los días a las **8:00 a. m.** (`08:00`) y **10:00 p. m.** (`22:00`), con persistencia tras reiniciar el teléfono (`BootReceiver`).
- **Saludo personalizado para Jesús:** Al abrir la app o tocar la notificación, el personaje saluda a **Jesús** con voz y animación de forma inmediata.

## Cómo generar tu archivo `.apk` instalable

### Opción 1: En la nube con GitHub Actions (Sin instalar Android Studio - 2 min)
1. Descomprime este archivo `.zip`.
2. Crea un repositorio en GitHub y sube todos los archivos descomprimidos (incluyendo la carpeta `.github`).
3. Ve a la pestaña **Actions** de tu repositorio, espera ~2 minutos a que termine el flujo **Compilar APK Saludos 3D Pixar** y descarga **`SaludosPixar3D-Jesús-APK`** en la sección **Artifacts**.

### Opción 2: Con Android Studio en tu PC
1. Abre la carpeta descomprimida en **Android Studio**.
2. Ve al menú **Build > Build Bundle(s) / APK(s) > Build APK(s)** para generar el archivo `app-debug.apk`.
