<div align="center">

# INSTITUTO TECNOLÓGICO NACIONAL DE MÉXICO
## INSTITUTO TECNOLÓGICO DE OAXACA

**Nombre de la carrera:**  
Ingeniería en Sistemas Computacionales  

**Nombre de la materia:**  
Programación web  

**Título del trabajo:**  
Portafolio de Evidencias Web (Basado en Plantilla Bootstrap)  

**Integrante:**  
Pacheco Aragón Yareli Yazmin (N.C. 23161067)  

**Docente:**  
Adelina Martinez Nieto  

**Grupo:** B  

**Fecha de entrega:**  
Julio 2026  

</div>

---

##  Descripción del Proyecto
Este proyecto consiste en el diseño, personalización y despliegue en vivo de un portafolio web profesional e individual, adaptado a partir de una plantilla libre de internet. El objetivo es estructurar de forma limpia y atractiva mi trayectoria académica, competencias técnicas y proyectos desarrollados en la carrera de ingeniería.

* **Framework CSS Utilizado:** Bootstrap v5.2.3
* **Plantilla Base:** Start Bootstrap - Resume
* **Enlace de Descarga de la Plantilla:** [https://github.com/startbootstrap/startbootstrap-resume](https://github.com/startbootstrap/startbootstrap-resume)

###  Secciones que Componen el Portafolio
1. **Sobre Mí:** Breve introducción sobre mi perfil como estudiante de ingeniería en el Instituto Tecnológico de Oaxaca, metas y enfoque profesional.
2. **Proyectos:** Espacio que detalla el desarrollo de sistemas reales aplicados, como una plataforma de gestión escolar en Java y PostgreSQL, un catálogo interactivo con MongoDB y un módulo síncrono de inactividad.
3. **Educación:** Resumen cronológico de mi formación académica, detallando mi educación superior actual y mi bachillerato en el COBAO Plantel 32.
4. **Habilidades:** Visualización de lenguajes dominados (Java, Python, JS, HTML/CSS) y áreas de competencia curricular como Autómatas, Ingeniería de Software y Sistemas Operativos.
5. **Intereses:** Redacción personalizada en primera persona que describe mi pasión por el diseño web, el lenguaje Ensamblador, el funcionamiento interno de la IA y mi nivel de inglés B1.

---

##  Proceso de Creación (Paso a Paso)

A partir de los archivos fuente de la plantilla descargada, realicé el siguiente procedimiento para estructurar y adaptar el portafolio según los lineamientos requeridos:

1. **Descarga y Extracción:** Descargué el código original desde el repositorio de Start Bootstrap en formato `.zip` y lo extraje en mi computadora.
2. **Reestructuración Limpia de Carpetas (Puntos de Rúbrica):** Ignoré por completo la carpeta de desarrollo `src` y tomé los archivos compilados de la carpeta `dist`. Creé un directorio raíz limpio para mi entrega y generé tres carpetas obligatorias: `css/`, `js/` e `img/`.
3. **Migración y Renombrado de Archivos:** 
   * Moví el archivo `index.html` a la raíz de mi proyecto.
   * Tomé el archivo original `styles.css` de la plantilla, lo pegué dentro de mi nueva carpeta `css` y lo renombré como `portafolio.css`.
   * Tomé el archivo original `scripts.js`, lo pegué en mi carpeta `js` y lo renombré como `portafolio.js`.
4. **Modificación de Rutas en el `index.html`:** Para evitar que la página se desarmara tras renombrar los archivos de estilos y scripts, abrí el código en el editor y actualicé los enlaces de la siguiente manera:
   * El CSS superior se cambió a: `<link href="css/portafolio.css" rel="stylesheet" />`
   * El script inferior se cambió a: `<script src="js/portafolio.js"></script>`
5. **Personalización de Contenido Técnico:** Modifiqué cada bloque de texto y párrafo original de la plantilla para plasmar mi información real. Reemplacé las plantillas genéricas de trabajos por proyectos reales de mi tira de materias (utilizando entornos como PostgreSQL, AWS, Java y MongoDB), y cambié las secciones lógicas para incluir mis conocimientos en Autómatas y Sistemas Operativos.
6. **Sección de Intereses Humana:** Redacté en primera persona mis áreas de enfoque actuales (Diseño Web, Ensamblador, Inteligencia Artificial) e incluí de forma realista mi nivel de competencia lingüística actual (Inglés B1).
7. **Integración de Fotografía Profesional:** Sustituí la imagen genérica de la barra de navegación lateral por una foto real propia (`img/profile.jpg`), cuidando la vestimenta formal, el fondo neutro y la iluminación profesional adecuada para un perfil de ingeniería.

---

##  Capturas de Pantalla

A continuación, se anexan las muestras del portafolio web renderizado correctamente desde el navegador web de forma local:

### Vista de Perfil y Presentación Principal
![Vista de Portafolio - Sección Sobre Mí](img/captura_perfil.png)
*(Aquí se aprecia la carga correcta de los estilos CSS modificados, la tipografía y mi fotografía real de perfil profesional).*

### Vista del Portafolio de Proyectos y Competencias
![Vista de Portafolio - Proyectos y Skills](img/captura_proyectos.png)
*(Muestra de las secciones adaptadas con el lenguaje real en desarrollo de software, bases de datos y la visualización de mis habilidades técnicas).*

---

