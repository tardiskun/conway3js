# Conway's Life 3D Experience

Experiencia visual interactiva que combina el Juego de la Vida de Conway con un campo de estrellas 3D y un sistema de zoom/traveling para explorar individuos.

## Archivos Disponibles

### 1. **conway_3d_experience.html** (Versión básica)
- Implementación completa del Juego de la Vida de Conway
- Campo de estrellas 3D como fondo
- Sistema de zoom básico entre vistas
- Controles de simulación completos

### 2. **conway_3d_enhanced.html** (Versión mejorada)
- Todos los elementos de la versión básica
- Nebulosas 3D adicionales
- Efectos de luz mejorados
- 4 niveles de zoom: Ciudad → Calle → Individual → Primer Plano
- Transiciones suaves entre vistas
- Función para enfocar celdas específicas
- Edificios 3D como fondo
- Efectos de animación más fluidos

## Características Principales

### 🎮 Juego de la Vida de Conway
- Autómata celular clásico con reglas estándar
- Rejilla configurable (20x20 a 80x80)
- Velocidad de simulación ajustable
- Patrones predefinidos (en la versión mejorada)

### 🌌 Efectos 3D
- **Campo de estrellas**: 8000+ estrellas con colores variables
- **Estrellas parpadeantes**: 150 estrellas 3D con efectos de pulsación
- **Nebulosas**: Nubes de gas interestelares con transparencias
- **Fondo de ciudad**: Edificios 3D alrededor de la rejilla

### 🔍 Sistema de Zoom/Traveling
El sistema implementa exactamente lo que pediste: **"como si fuese un zoom de la ciudad hacia la vía pública, con gente viviendo y luego haciendo traveling por alguna de las calles y volviendo a ver la ciudad desde arriba"**

- **Vista de Ciudad**: Ves toda la rejilla como una ciudad
- **Vista de Calle**: Zoom a grupos de celdas (como calles)
- **Vista Individual**: Enfoque en una sola celda (como una persona)
- **Primer Plano**: Vista extremadamente cercana
- **Transiciones suaves**: Animaciones fluidas con easing cúbico

### 🎯 Enfoque en Individuos
- Botón **"Enfocar Celda"** que busca una celda viva y hace zoom automático
- También puedes hacer **click en cualquier celda** para activarla/desactivarla
- La cámara se mueve suavemente hacia la celda seleccionada

---

## 🎛️ Controles
   Acción | Teclado | Botón |
 |--------|---------|-------|
 | Pausar/Reanudar | Espacio | Pausa |
 | Patrón aleatorio | R | Aleatorio |
 | Reiniciar | - | Reiniciar |
 | Enfocar celda | F | Enfocar Celda |
 | Zoom In | - | Zoom In |
 | Zoom Out | - | Zoom Out |
 | Traveling | - | Traveling |
 | Activar celda | Click | - |

**Sliders:**
- Tamaño de rejilla: 20-80
- Velocidad: 1x-20x

**Ratón:**
- Click: Alternar celda
- Arrastrar: Rotar cámara
- Scroll: Zoom manual

---

## 🚀 Cómo Usar

1. **Abre** `conway_3d_enhanced.html` en tu navegador (Chrome, Firefox, Edge)
2. **Explora**:
   - Haz click en "Aleatorio" para generar un patrón
   - Usa los botones de zoom o las teclas C/S/I
   - Haz click en "Enfocar Celda" para ver una celda individual
   - Usa el ratón para rotar y explorar

---

## 💡 Detalles Técnicos

- **Three.js r128**: Biblioteca 3D para WebGL
- **OrbitControls**: Controles de cámara interactivos
- **Geometrías optimizadas**: BufferGeometry para mejor rendimiento
- **Iluminación**: Luz ambiental + direccional + punto
- **Sombras**: Shadow mapping para realismo
- **Niebla**: Efecto de profundidad

---

**¡Disfruta explorando el universo del Juego de la Vida con efectos 3D espectaculares! 🌟**
