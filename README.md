# BoxApp 🥊

Aplicación de entrenamiento de boxeo profesional construida con **React Native** y **Expo**. Diseñada para gestionar sesiones de entrenamiento, controlar el peso y categoría, y visualizar el progreso.

## Características Principales

- **Temporizador profesional**: Preparación, Rounds (trabajo) y Descanso con presets rápidos (AMATEUR, PRO, HIIT).
- **Entrenador de voz (TTS)** y **feedback háptico** (vibración).
- **Perfil de boxeador**: registro de peso y cálculo automático de categoría.
- **Seguimiento de progreso**: gráficos de historial de peso.
- **Diseño premium**: modo oscuro y acentos rojos/dorados.
- **Internacionalización**: soporte para Español e Inglés.

## Tecnologías

- **Core**: React Native, Expo
- **UI**: Gluestack UI, Lucide Icons
- **Navegación**: React Navigation
- **Almacenamiento**: @react-native-async-storage/async-storage
- **Gráficos**: react-native-gifted-charts
- **I18n**: i18next, expo-localization
- **Multimedia & UX**: expo-av, expo-speech, expo-haptics, expo-keep-awake

## Instalación y Uso

1. Clona el repositorio:

```bash
git clone https://github.com/hahn92/BoxAppWeb.git
cd BoxAppWeb
```

2. Instala dependencias:

```bash
npm install
```

3. Inicia la aplicación (Expo):

```bash
npx expo start
```

4. Ejecuta en dispositivo:
- Escanea el código QR con **Expo Go** (Android/iOS).
- Presiona `a` para Android Emulator, `i` para iOS Simulator.

## Estructura del Proyecto

- `src/screens`: Pantallas principales (Home, Timer, Profile, Stats)
- `src/components`: Componentes reutilizables
- `src/navigation`: Configuración de navegación
- `src/utils`: Lógica de negocio (cálculo de categorías, formateo)
- `src/hooks`: Custom hooks (persistencia de datos)

## Notas

- Para activar sonidos reales, añade archivos de audio en `assets/` y habilita la lógica en `src/screens/TimerScreen.js`.
- Para pruebas unitarias de la lógica (ej. cálculo de categoría), utiliza **jest**.

---

¿Quieres que también añada una sección «Capturas» en la página principal y un logo en `assets/`? (Puedo generar un placeholder SVG si lo deseas).