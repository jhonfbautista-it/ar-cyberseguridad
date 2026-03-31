# 🎯 Comparador de Opciones AR - JFMAX

Este proyecto te permite **probar 3 métodos diferentes** de Realidad Aumentada para que elijas el mejor según tus necesidades.

## 📱 Cómo Probar en tu Celular

### Método Rápido (Recomendado):

1. **Sube estos archivos a GitHub Pages o Netlify**
   - Crea repo en GitHub
   - Sube todos los archivos
   - Activa GitHub Pages
   - Accede desde tu celular

2. **O usa Python localmente:**
   ```bash
   cd ar-opciones-test
   python -m http.server 8000
   ```
   Luego abre desde tu celular: `http://TU-IP-LOCAL:8000`

3. **Escanea los QR** que aparecen en la página principal

---

## 🎯 Las 3 Opciones Explicadas

### **OPCIÓN 1: Marcadores Predefinidos (HIRO/KANJI)**

**¿Cómo funciona?**
```
Usuario escanea QR → Abre navegador → Descarga marcador HIRO/KANJI → 
Imprime → Muestra a cámara → Ve el avatar 3D
```

**📊 PROS:**
- ✅ Muy preciso y estable
- ✅ No requiere configuración técnica
- ✅ Tracking perfecto
- ✅ Funciona siempre bien

**📉 CONTRAS:**
- ⚠️ Necesitas imprimir marcadores específicos
- ⚠️ Todos usan los mismos marcadores (HIRO/KANJI)
- ⚠️ No puedes personalizar el marcador

**🎯 Mejor para:**
- Capacitaciones formales
- Demos de producto
- Cuando quieres máxima precisión
- Usuarios que pueden imprimir

**Descarga los marcadores:**
- HIRO: https://raw.githubusercontent.com/AR-js-org/AR.js/master/data/images/hiro.png
- KANJI: https://raw.githubusercontent.com/AR-js-org/AR.js/master/data/images/kanji.png

---

### **OPCIÓN 2: QR/Códigos Personalizados**

**¿Cómo funciona?**
```
Usuario escanea QR personalizado → Abre navegador → 
Muestra el QR a la cámara → Ve el avatar 3D sobre el QR
```

**📊 PROS:**
- ✅ Puedes usar TUS PROPIOS códigos QR
- ✅ Cada QR puede tener un mensaje diferente
- ✅ Perfecto para campañas personalizadas
- ✅ Puedes generar códigos con tu logo/marca

**📉 CONTRAS:**
- ⚠️ Requiere generar archivos .patt para cada QR
- ⚠️ Configuración más técnica
- ⚠️ Un poco menos preciso que HIRO/KANJI

**🎯 Mejor para:**
- Campañas de marketing con múltiples mensajes
- Eventos donde cada stand tiene su QR
- Cuando necesitas trackear diferentes códigos
- Branding personalizado

**Cómo generar tus propios marcadores:**
1. Ve a: https://jeromeetienne.github.io/AR.js/three.js/examples/marker-training/examples/generator.html
2. Sube tu imagen/QR
3. Descarga el archivo .patt
4. Úsalo en el código

---

### **OPCIÓN 3: Sin Marcadores (Markerless)**

**¿Cómo funciona?**
```
Usuario escanea QR → Abre navegador → 
Permite cámara → Toca botones → Personajes aparecen en el espacio real
```

**📊 PROS:**
- ✅ NO necesitas imprimir NADA
- ✅ Experiencia más moderna y "wow"
- ✅ Usuario controla dónde aparecen los objetos
- ✅ Muy interactivo

**📉 CONTRAS:**
- ⚠️ Menos preciso en el posicionamiento
- ⚠️ Los objetos pueden "flotar"
- ⚠️ Funciona mejor en superficies planas
- ⚠️ Varía según el dispositivo

**🎯 Mejor para:**
- Ferias y eventos casuales
- Demos rápidas sin preparación
- Cuando no puedes imprimir nada
- Experiencias exploratorias

---

## 📊 Tabla Comparativa Rápida

| Característica | Opción 1 | Opción 2 | Opción 3 |
|---------------|----------|----------|----------|
| **Imprimir** | ✅ Sí | ✅ Sí | ❌ No |
| **Precisión** | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐ |
| **Facilidad** | ⭐⭐⭐⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐⭐⭐ |
| **Personalización** | ⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ |
| **Estabilidad** | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐ |
| **Complejidad técnica** | Baja | Alta | Media |

---

## 🚀 Instrucciones de Prueba

### 1️⃣ Probar OPCIÓN 1:
```bash
1. Abre opcion1-marcadores.html en tu celular
2. Descarga e imprime marcador HIRO o KANJI
3. Permite acceso a cámara
4. Apunta al marcador impreso
5. ¡Ve aparecer el personaje!
```

### 2️⃣ Probar OPCIÓN 2:
```bash
1. Abre opcion2-qr-custom.html en tu celular
2. Permite acceso a cámara
3. Apunta a cualquier código de barras o QR
4. (Funciona con barcode matrix type 3x3)
5. ¡Ve aparecer el objeto 3D!
```

### 3️⃣ Probar OPCIÓN 3:
```bash
1. Abre opcion3-markerless.html en tu celular
2. Permite acceso a cámara
3. Toca los botones en pantalla
4. Los personajes aparecen frente a ti
5. ¡Mueve el celular para verlos desde todos los ángulos!
```

---

## 💡 Mi Recomendación

### Para JFMAX / APC Colombia:

**Si tu objetivo es:**

#### 🎓 **Capacitación formal de ciberseguridad:**
→ **OPCIÓN 1** (Marcadores HIRO/KANJI)
- Razón: Máxima precisión y confiabilidad
- Puedes imprimir los marcadores en manuales de capacitación
- Funciona siempre, sin fallas

#### 🎪 **Campaña con múltiples mensajes personalizados:**
→ **OPCIÓN 2** (QR Personalizados)
- Razón: Cada QR puede tener mensaje diferente
- Ejemplo: QR1 = "Phishing", QR2 = "Ransomware", QR3 = "Ingeniería Social"
- Puedes poner tu logo en los QRs

#### 🚀 **Demo rápida en evento/feria:**
→ **OPCIÓN 3** (Sin Marcadores)
- Razón: No necesitas llevar papeles impresos
- Más "wow factor" para el público
- Setup instantáneo

---

## 🛠️ Personalización

Cada opción es fácil de personalizar:

### Cambiar Mensajes:
```html
<!-- Busca esta línea en el HTML: -->
<a-text value="TU MENSAJE AQUÍ" ...>
```

### Cambiar Colores:
```html
<!-- Busca y cambia el atributo color: -->
<a-box color="#ff0033" ...>
<a-plane color="#00d4ff" ...>
```

### Agregar Modelos 3D:
```html
<!-- Reemplaza las primitivas con tu modelo: -->
<a-entity gltf-model="url(./tu-modelo.glb)" scale="1 1 1">
```

---

## 📦 Archivos del Proyecto

```
ar-opciones-test/
├── index.html                  # Página principal con QRs y comparación
├── opcion1-marcadores.html     # Marcadores HIRO/KANJI
├── opcion2-qr-custom.html      # QR personalizados
├── opcion3-markerless.html     # Sin marcadores
└── README.md                   # Este archivo
```

---

## 🎯 Siguiente Paso

**Después de probar las 3 opciones:**

1. Decide cuál te gustó más
2. Avísame cuál elegiste
3. Te ayudo a:
   - Personalizarlo con tus mensajes de ciberseguridad
   - Agregar tus modelos 3D específicos
   - Generar múltiples QRs personalizados
   - Implementar audio/música
   - Publicarlo en producción

---

## 📞 Contacto

**Desarrollado por:** JFMAX (John Freddy Bautista Díaz)  
**Para:** APC Colombia  
**Año:** 2026

---

## 🔥 Tips Importantes

### Para que funcione bien:

1. **Iluminación:** Usa buena luz, evita reflejos
2. **Distancia:** Mantén el celular a 20-30cm del marcador
3. **Estabilidad:** Mantén el celular firme
4. **Impresión:** Si imprimes marcadores, usa buena calidad (no borroso)
5. **Navegador:** Usa Chrome en Android o Safari en iOS
6. **HTTPS:** Para producción, necesitas HTTPS (GitHub Pages lo tiene)

### Problemas comunes:

**"No detecta el marcador"**
- Verifica que el marcador esté bien iluminado
- Asegúrate que el marcador esté completo en pantalla
- Prueba acercándote o alejándote

**"No se ve el 3D"**
- Revisa que permitiste acceso a cámara
- Recarga la página
- Prueba con otro navegador

**"Cámara no funciona"**
- iOS solo funciona en Safari
- Verifica permisos de cámara en configuración
- Asegúrate de estar usando HTTPS (no HTTP)

---

¡Listo! Ahora prueba las 3 opciones y dime cuál te funciona mejor. 🚀
