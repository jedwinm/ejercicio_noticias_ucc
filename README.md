# Portal de Noticias UCC - Ejercicio Académico

## 📋 Descripción del Proyecto

Este repositorio contiene un sitio web estático diseñado como ejercicio práctico para estudiantes de séptimo semestre de Diseño Crossmedia de la Universidad Cooperativa de Colombia. El objetivo es desarrollar habilidades en **construcción de contenido**, **UX Writing** y **escritura para personas**.

### 🎯 Objetivos de Aprendizaje

- Aplicar principios de UX Writing en la redacción de noticias
- Adaptar el tono y estilo de comunicación según la categoría
- Estructurar contenido periodístico de forma clara y accesible
- Escribir para personas, no para buscadores
- Trabajar colaborativamente en un proyecto usando Git y GitHub
- Implementar buenas prácticas de contenido web

---

## 📁 Estructura de Archivos

```
ejercicio_noticias_ucc/
│
├── index.html                      # Página principal del sitio
├── template-noticia.html           # Plantilla para crear noticias
├── styles.css                      # Estilos neumórficos del sitio
├── LINEAMIENTOS_EJERCICIO.pdf      # Documento con instrucciones completas
├── README.md                       # Este archivo
│
└── noticias/                       # Carpeta donde crearás tus noticias
    ├── salud/
    ├── politica/
    ├── deportes/
    ├── tecnologia/
    ├── cultura/
    ├── economia/
    ├── educacion/
    ├── medio-ambiente/
    ├── entretenimiento/
    └── ciencia/
```

---

## 🚀 Guía Rápida para Estudiantes

### Paso 1: Clonar el Repositorio

```bash
# Clona el repositorio a tu computadora
git clone [URL-DEL-REPOSITORIO]

# Ingresa a la carpeta del proyecto
cd ejercicio_noticias_ucc
```

### Paso 2: Crear una Rama de Trabajo

```bash
# Crea una rama con tu nombre (sin espacios)
git checkout -b tu-nombre-apellido

# Ejemplo:
git checkout -b juan-perez
```

### Paso 3: Leer los Lineamientos

Antes de comenzar, **lee detenidamente** el documento `LINEAMIENTOS_EJERCICIO.pdf`. Este documento contiene:

- Instrucciones detalladas del ejercicio
- Lineamientos de comunicación para cada categoría
- Guía de buenas prácticas de UX Writing
- Criterios de evaluación

### Paso 4: Crear tus Noticias

#### 4.1. Duplicar la Plantilla

```bash
# Copia la plantilla y renómbrala
cp template-noticia.html noticias/salud/noticia-salud-1.html
```

#### 4.2. Editar el Contenido

Abre el archivo HTML con tu editor de código favorito (VS Code, Sublime Text, etc.) y:

1. Lee los comentarios HTML que dicen `<!-- INSTRUCCIÓN: ... -->`
2. Reemplaza el lorem ipsum con tu contenido real
3. Actualiza los metadatos (título, fecha, autor, categoría)
4. Asegúrate de que las imágenes tengan descripciones (alt) significativas
5. Añade etiquetas relevantes al final del artículo

#### 4.3. Nomenclatura de Archivos

Usa nombres descriptivos y claros para tus archivos:

```
✅ Correcto:
- noticia-salud-nuevo-tratamiento-cancer.html
- noticia-tecnologia-inteligencia-artificial-educacion.html

❌ Incorrecto:
- noticia1.html
- mi-articulo.html
```

### Paso 5: Guardar tus Cambios (Commit)

```bash
# Añade los archivos que modificaste
git add noticias/salud/noticia-salud-1.html

# O añade todos los cambios
git add .

# Crea un commit con un mensaje descriptivo
git commit -m "Añadida noticia de salud sobre tratamiento del cáncer"
```

### Paso 6: Subir tus Cambios (Push)

```bash
# Sube tus cambios a GitHub
git push origin tu-nombre-apellido
```

### Paso 7: Crear un Pull Request

1. Ve al repositorio en GitHub
2. Haz clic en "Compare & pull request"
3. Escribe un título descriptivo: "Noticias de [Tu Nombre] - Categoría X"
4. Añade una descripción con:
   - Lista de noticias que añadiste
   - Cualquier duda o comentario
5. Asigna el pull request al profesor

---

## ✍️ Requisitos del Ejercicio

### Cantidad de Noticias

Cada estudiante debe crear **30 noticias en total**:
- **3 noticias por categoría** × 10 categorías = 30 noticias

### Categorías Obligatorias

1. ❤️ **Salud** - Información médica, bienestar y prevención
2. 🏛️ **Política** - Análisis político, gobierno y legislación
3. ⚽ **Deportes** - Competiciones, atletas y resultados
4. 💻 **Tecnología** - Innovación, gadgets y tendencias tech
5. 🎨 **Cultura** - Arte, eventos y expresiones culturales
6. 💰 **Economía** - Mercados, finanzas y negocios
7. 🎓 **Educación** - Aprendizaje, instituciones y pedagogía
8. 🌍 **Medio Ambiente** - Ecología, sostenibilidad y cambio climático
9. 🎬 **Entretenimiento** - Cine, música, series y celebridades
10. 🔬 **Ciencia** - Descubrimientos, investigación y avances

### Elementos Obligatorios en Cada Noticia

✅ **Título principal** (H1) - Claro, conciso y atractivo (50-70 caracteres)
✅ **Subtítulo/bajada** - Información complementaria (100-150 caracteres)
✅ **Fecha de publicación** - En formato: DD de Mes de YYYY
✅ **Autor** - Tu nombre completo
✅ **Categoría** - Una de las 10 categorías
✅ **Imagen destacada** - Con descripción alt y pie de foto
✅ **Primer párrafo** - Responde las 5W (Qué, Quién, Cuándo, Dónde, Por qué)
✅ **Cuerpo del artículo** - Mínimo 5 párrafos bien estructurados
✅ **Al menos 2 imágenes de apoyo** - Con descripciones y pies de foto
✅ **Una cita textual** (opcional pero recomendado)
✅ **5-8 etiquetas** - Palabras clave relevantes

---

## 🎨 Lineamientos de Estilo

### Principios de UX Writing

1. **Claridad sobre todo**: Escribe de forma simple y directa
2. **Sé conciso**: Elimina palabras innecesarias
3. **Usa voz activa**: "El gobierno anunció" en lugar de "Fue anunciado por el gobierno"
4. **Evita jerga**: Si debes usar términos técnicos, explícalos
5. **Jerarquiza información**: Lo más importante primero (pirámide invertida)
6. **Usa subtítulos**: Facilitan el escaneo y la lectura
7. **Escribe para personas**: Piensa en tu audiencia, no en el algoritmo

### Longitudes Recomendadas

- **Título**: 50-70 caracteres
- **Subtítulo**: 100-150 caracteres
- **Primer párrafo**: 60-80 palabras
- **Párrafos subsiguientes**: 40-60 palabras
- **Artículo completo**: 400-600 palabras

### Imágenes

- **Formato**: JPG o PNG
- **Peso máximo**: 500 KB por imagen
- **Dimensiones recomendadas**: 
  - Imagen destacada: 1200x600 px
  - Imágenes de apoyo: 800x500 px
- **Alt text obligatorio**: Descripción clara para accesibilidad
- **Pie de foto**: Contexto y créditos de la imagen

---

## 🤝 Trabajo Colaborativo

### Buenas Prácticas de Git

1. **Actualiza tu rama frecuentemente**:
   ```bash
   git pull origin main
   ```

2. **Haz commits pequeños y frecuentes**: Un commit por noticia es ideal

3. **Escribe mensajes de commit descriptivos**:
   ```bash
   ✅ Correcto:
   "Añadida noticia de tecnología sobre IA en educación"
   "Corregidas imágenes en noticia de deportes"
   
   ❌ Incorrecto:
   "update"
   "cambios"
   ```

4. **Revisa el trabajo de tus compañeros**: Comenta en sus pull requests de forma constructiva

### Resolución de Conflictos

Si encuentras conflictos al hacer push:

```bash
# Actualiza tu rama con los últimos cambios
git pull origin main

# Resuelve los conflictos en tu editor
# Guarda los archivos

# Añade los archivos resueltos
git add .

# Completa el merge
git commit -m "Resueltos conflictos de merge"

# Sube los cambios
git push origin tu-rama
```

---

## ⏱️ Cronograma

**Duración total**: 2 horas

- **0:00 - 0:15**: Lectura de lineamientos y organización
- **0:15 - 1:45**: Redacción de las 30 noticias
- **1:45 - 2:00**: Revisión final y entrega

---

## 📊 Criterios de Evaluación

### Contenido (40%)
- ✅ Cumplimiento de elementos obligatorios
- ✅ Calidad y claridad de la redacción
- ✅ Aplicación correcta del tono según categoría
- ✅ Estructura periodística (pirámide invertida)

### UX Writing (30%)
- ✅ Claridad y concisión
- ✅ Uso de lenguaje accesible
- ✅ Jerarquización de información
- ✅ Títulos y subtítulos efectivos

### Aspectos Técnicos (20%)
- ✅ HTML semántico correcto
- ✅ Descripciones alt en imágenes
- ✅ Metadatos completos
- ✅ Nomenclatura de archivos

### Colaboración (10%)
- ✅ Uso correcto de Git y GitHub
- ✅ Mensajes de commit descriptivos
- ✅ Participación en revisiones

---

## 🛠️ Herramientas Recomendadas

### Editores de Código
- [Visual Studio Code](https://code.visualstudio.com/) (Recomendado)
- [Sublime Text](https://www.sublimetext.com/)
- [Atom](https://atom.io/)

### Extensiones Útiles para VS Code
- **Live Server**: Para previsualizar cambios en tiempo real
- **Prettier**: Formateo automático de código
- **Spanish - Code Spell Checker**: Corrección ortográfica en español

### Recursos de Imágenes Gratuitas
- [Unsplash](https://unsplash.com/)
- [Pexels](https://www.pexels.com/)
- [Pixabay](https://pixabay.com/)

### Herramientas de UX Writing
- [Hemingway Editor](http://www.hemingwayapp.com/): Mejora la legibilidad
- [Grammarly](https://www.grammarly.com/): Corrección gramatical

---

## 🐛 Solución de Problemas Comunes

### "No puedo ver los estilos en mi página"

✅ Verifica que el archivo `styles.css` esté en la misma carpeta raíz
✅ Revisa que el link en el HTML sea: `<link rel="stylesheet" href="../../styles.css">`

### "Mi imagen no se muestra"

✅ Verifica que la ruta de la imagen sea correcta
✅ Asegúrate de que el archivo de imagen exista
✅ Usa rutas relativas, no absolutas

### "Git me pide usuario y contraseña constantemente"

✅ Configura tu nombre y email:
```bash
git config --global user.name "Tu Nombre"
git config --global user.email "tu@email.com"
```

### "Mi pull request tiene conflictos"

✅ Sigue la sección "Resolución de Conflictos" de este documento
✅ Pide ayuda al profesor si no puedes resolverlos

---

## 📞 Contacto y Soporte

Si tienes dudas durante el ejercicio:

1. **Revisa este README y el PDF de lineamientos**
2. **Pregunta a tus compañeros** en el grupo de trabajo
3. **Consulta al profesor** levantando la mano o por el canal designado

---

## 📝 Notas Importantes

- ⚠️ **NO** modifiques los archivos `index.html`, `styles.css` o `template-noticia.html`
- ⚠️ **NO** trabajes directamente en la rama `main`
- ⚠️ **NO** copies contenido de internet sin adaptarlo
- ⚠️ **NO** uses generadores de texto automáticos sin revisión
- ✅ **SÍ** pide retroalimentación a tus compañeros
- ✅ **SÍ** revisa tu ortografía y gramática antes de hacer commit
- ✅ **SÍ** diviértete aprendiendo y experimentando

---

## 📚 Recursos Adicionales

### Sobre UX Writing
- [Guía de UX Writing de Google](https://design.google/library/ux-writing/)
- [Content Design London](https://contentdesign.london/)

### Sobre Periodismo Digital
- [Manual de Estilo de la Fundéu](https://www.fundeu.es/)
- [Guía de Redacción de EL PAÍS](https://elpais.com/)

### Sobre Git y GitHub
- [Git - La guía sencilla](https://rogerdudler.github.io/git-guide/index.es.html)
- [GitHub Learning Lab](https://lab.github.com/)

---

## 📄 Licencia

Este material es de uso exclusivo para fines educativos en la Universidad Cooperativa de Colombia.

---

## 👨‍🏫 Créditos

**Universidad Cooperativa de Colombia**  
Programa: Diseño Crossmedia  
Semestre: Séptimo  
Año: 2026

---

¡Mucho éxito en tu ejercicio! 🚀📝