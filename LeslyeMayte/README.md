<p align="center">
  <img src="../assets/plantcare.jpg"
       alt="PlantCare"
       width="100%">
</p>

<h1 align="center">🌿 Evaluación de Leslie Mayte</h1>

<p align="center">
  <strong>Plant Care V1.0 · Experiencia de usuario</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/EVALUADOR-LESLYEMAYTE-A16ACB?style=for-the-badge">
  <img src="https://img.shields.io/badge/PRUEBAS-10-087B55?style=for-the-badge">
</p>

<p align="center">
  🌿 ¡Cada opinión nos ayuda a mejorar Plant Care! 💚
</p>

---

## 👤 Mi información

| 📝 Dato | 💚 Información |
|:---|:---|
| **Evaluador** | Leslie  (`@LeslyeMayte`) |
| **Planta representante** | 🌿 Eucalipto |
| **Versión de Plant Care** | `1.0 (Build 1)` |
| **Fecha de evaluación** | 26/10/2026 |
| **Modelo de teléfono** | POCO M6 (2404APC5FG) |
| **Versión de Android** | Android 15 |
| **Estado general** | ✅ Diez retos revisados, con observaciones |

---

## 🎮 ¡Mis 10 pruebas!

Revisé las funciones principales de Plant Care en un teléfono físico, con cuentas autorizadas y una cuenta adicional de prueba. La comprobación de roles corresponde a la interfaz visible; no fue una auditoría de permisos internos del servidor.

**Estados disponibles:**

- ⬜ Pendiente
- ✅ Funcionó correctamente
- ⚠️ Encontré un problema
- ➖ No pude probarlo

En cada fila registro lo observado y una calificación orientativa de **1 a 5**.

| N.º | 🌿 Prueba | Estado | ⭐ Nota | 💬 Mi comentario |
|:---:|:---|:---:|:---:|:---|
| 01 | 👑 Prueba de cuenta de administración | ✅ | 5/5 | Entré con la cuenta autorizada. Aparecieron Usuarios, Categorías, Recetas y Perfil. En modo usuario se mostraron Explorar, Buscar, Favoritos y Perfil. Se comprobó esa separación visible, no los permisos internos del servidor. |
| 02 | 👤 Creación de usuario (Admin) | ✅ | 4/5 | El formulario vacío mostró validaciones. Después creé un usuario con rol Usuario y se actualizaron listado y contadores. Los avisos iniciales permanecieron mientras completaba los campos hasta reenviar; recomendaría actualizarlos al editar. |
| 03 | 📄 Descarga de PDF de usuarios | ✅ | 4/5 | Con Guardar como PDF se creó usuarios_plantas_medicinales.pdf en Descargas. La vista previa mostró una página con los dos usuarios de ese momento. Recomendaría explicar los pasos o permitir descarga directa. |
| 04 | 📂 Creación de categoría y receta | ⚠️ | 4/5 | Creé QA261026 y la receta QA261026 - PRUEBA NO USAR. Sin imagen apareció “Bad state: Selecciona una imagen para la receta”. Después de adjuntarla, la publicación funcionó y fue visible desde el usuario nuevo. Recomendaría indicar que la imagen es obligatoria. |
| 05 | 🔐 Acceso en modo usuario | ✅ | 5/5 | Cerré administración e inicié sesión con el usuario recién creado. Pude consultar y buscar la receta publicada. No aparecieron las pestañas de administración. |
| 06 | 📱 Visualización y navegación general | ✅ | 4/5 | Recorrí Explorar, Buscar, Favoritos, Perfil, categorías y detalles sin cierres observados. Pude desplazar el detalle hasta la nota educativa. Recomendaría confirmar el cierre de sesión, pues tocar el icono termina la sesión directamente. |
| 07 | 🔍 Consulta de categorías y recetas | ✅ | 5/5 | Consulté ingredientes, preparación y beneficio. Buscar “estomago” encontró “Dolor de estómago” sin escribir el acento. También encontré QA261026 desde la cuenta nueva. |
| 08 | 📥 Descarga de receta medicinal | ⚠️ | 4/5 | Descargar abrió Compartir. Mediante Imprimir > Guardar como PDF guardé la receta de prueba en Descargas. Conservó título, categoría, ingredientes, preparación, beneficio y aviso educativo. La viñeta del ingrediente aparece como un recuadro con una cruz en teléfono y computadora. Recomendaría corregir el símbolo y separar Guardar de Compartir. |
| 09 | ⭐ Guardar y ver recetas en favoritos | ✅ | 5/5 | Quité una receta guardada y comprobé el estado vacío. La agregué otra vez y apareció, restaurando el estado inicial. Con el usuario nuevo guardé QA261026 y apareció en Favoritos; la quité al terminar. |
| 10 | 🌿 Experiencia general de la app | ✅ | 4/5 | Funcionaron acceso por rol, creación de usuario y contenido, consulta, búsqueda, favoritos y exportación. Colores consistentes y secciones claras. Mejoraría validaciones, exportación y gestión posterior del contenido. |

> 💚 Puedo consultar las instrucciones completas en la [guía de las 10 pruebas](../PLAN_10_PRUEBAS.md).

---

## ⭐ Mi escala de calificación

| Estrellas | Calificación | Significado |
|:---:|:---:|:---|
| ⭐ | 1/5 | Muy malo |
| ⭐⭐ | 2/5 | Malo |
| ⭐⭐⭐ | 3/5 | Regular |
| ⭐⭐⭐⭐ | 4/5 | Bueno |
| ⭐⭐⭐⭐⭐ | 5/5 | Excelente |

**Mi calificación general:** 4 / 5

**¿Por qué elegí esa calificación?**

Es el promedio de las diez notas. Pude completar las funciones del recorrido, con detalles en la validación de la imagen obligatoria y en el aspecto del PDF. La exportación funcionó mediante Android.

---

## 🐛 Reporte de errores

### PC-01 · Mensaje técnico al publicar sin imagen

| 🔍 Información | 📝 Mi respuesta |
|:---|:---|
| **Función afectada** | Administración > Recetas > Publicar receta |
| **¿Qué intentaba hacer?** | Publicar con nombre, categoría, ingredientes, preparación y beneficio, sin seleccionar imagen. |
| **¿Qué ocurrió?** | Apareció “Bad state: Selecciona una imagen para la receta”. La publicación funcionó después de adjuntar la imagen. |
| **¿Qué esperaba que sucediera?** | Identificar de antemano que la imagen es obligatoria y recibir una instrucción sin texto técnico. |
| **¿Puedo repetir el problema?** | Observado en un intento. Falta repetir en otra sesión. |
| **Importancia del problema** | Solicitar imagen. |
| **Captura de pantalla** | Conservada en el paquete de evidencias, sin credenciales ni datos personales. |

### PC-02 · Viñeta incorrecta en el PDF de receta

| 🔍 Información | 📝 Mi respuesta |
|:---|:---|
| **Función afectada** | Detalle de receta > Descargar receta en PDF |
| **¿Qué intentaba hacer?** | Generar y guardar el PDF de QA261026. |
| **¿Qué ocurrió?** | Apareció un recuadro con una cruz antes del ingrediente. El resto del contenido fue legible. |
| **¿Qué esperaba que sucediera?** | Una viñeta legible y un formato consistente. |
| **¿Puedo repetir el problema?** | El mismo archivo mostró el defecto en teléfono y computadora. Falta repetir con otra receta. |
| **Importancia del problema** | Baja: defecto visual. |
| **Captura de pantalla** | Conservada en el paquete de evidencias. |

Recomendaría usar símbolos compatibles e incluir las fuentes necesarias. No se confirmó la causa técnica exacta.

---

## 💬 Tres preguntas adicionales

### 💚 1. ¿Qué fue lo que más me gustó de Plant Care?

**Mi respuesta:**

Las categorías, la búsqueda y los favoritos permiten encontrar y volver a consultar recetas fácilmente. Me gustó la separación de ingredientes, preparación y beneficio, la nota educativa y el estilo visual consistente.

### 🛠️ 2. ¿Qué mejoraría o cambiaría de la aplicación?

**Mi respuesta:**

Marcaría los campos obligatorios, actualizaría las validaciones al corregirlos y evitaría mensajes como “Bad state”. Corregiría la viñeta del PDF, separaría Guardar de Compartir y pediría confirmación al cerrar sesión. En las pantallas recorridas no localicé controles visibles para editar o eliminar categorías y recetas; recomendaría añadirlos.

### 🌿 3. ¿Recomendaría esta aplicación a alguien interesado en la medicina natural? ¿Por qué?

**Mi respuesta:**

La recomendaría para explorar y organizar contenido educativo, por sus categorías, búsqueda y favoritos.

---

## 📝 Mis observaciones adicionales

Aquí puedo comentar aspectos que no estén incluidos en las diez pruebas.

**🎨 Diseño y colores:**

La combinación de verde y fondo claro es consistente, y los botones principales se identifican fácilmente. Corregiría el símbolo del PDF.

**📱 Facilidad de uso y navegación:**

La consulta y los favoritos fueron sencillos. El icono de salida terminó la sesión directamente; recomendaría pedir confirmación. También explicaría el uso de Compartir e Imprimir para guardar archivos.

**⚡ Velocidad y rendimiento:**

No observé cierres ni bloqueos durante el recorrido. No medí tiempos exactos, memoria, batería ni rendimiento prolongado o con muchos registros.

**💡 Otras sugerencias:**

Actualizar las validaciones al editar, facilitar descarga directa y mostrar controles de edición de contenido. En Recetas vi Publicar y Retirar, pero no una opción visible de edición durante el recorrido.

---

## 📸 Evidencias (opcional)

Conservé capturas y el PDF de receta de prueba en un paquete separado. Este README no incorpora archivos ni enlaces que requieran modificar carpetas ajenas. Se excluyen acceso, perfiles, contactos y reporte de usuarios para evitar exponer datos personales o credenciales.

---

## ✅ Mi evaluación final

| 🌿 Elemento | Resultado |
|:---|:---|
| Pruebas revisadas | 10 / 10 |
| Problemas encontrados | 2 detalles y sugerencias de usabilidad |
| Calificación general | 4 / 5 |
| ¿Terminé mi evaluación? | ✅ Sí, dentro del alcance descrito |

### 💚 Mi conclusión

Pude completar el recorrido de administración y usuario: crear cuenta, categoría y receta de prueba; consultar esa receta con el usuario nuevo, aunque no se pudo ejecutar el inicio de sesión mediante Google; usar favoritos y guardar PDF mediante Android. Priorizaría corregir los detalles registrados y simplificar la exportación y la gestión de contenido.

Al terminar retiré la receta QA261026 de publicación y desactivé el usuario de prueba. La categoría QA261026 y la receta como Borrador permanecen como registros de evaluación.

---

## 📤 Entrega de Leslie Mayte

**Fecha límite:** viernes 23 de octubre de 2026.

**Hora:** 11:59 p. m. (centro de México).

Guardaré mis respuestas en una rama propia y crearé un **Pull Request hacia `main`**.

Modificaré únicamente mi documento.

<p align="center">
  <a href="../README.md">
    <img src="https://img.shields.io/badge/VOLVER-AL%20INICIO-087B55?style=for-the-badge">
  </a>
  <a href="../PLAN_10_PRUEBAS.md">
    <img src="https://img.shields.io/badge/VER-GUÍA%20DE%20PRUEBAS-A16ACB?style=for-the-badge">
  </a>
</p>

---

<h3 align="center">🌿 ¡Gracias por participar, Leslye Mayte! 💚</h3>
