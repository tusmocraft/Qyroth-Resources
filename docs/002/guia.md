# 🛠️ GUÍA MAESTRA: Modo Desarrollador de Discord y Copiado de IDs
**Categoría:** Tutoriales Técnicos #002 | **Proyecto:** Qyroth Resources

---

## 📌 Introducción y Requisitos
Si estás configurando un servidor de Discord profesional, gestionando bots o configurando sistemas de permisos avanzados **necesitas trabajar con IDs únicos (Snowflakes)**.

Cada elemento en Discord (usuario, canal, servidor, rol y mensaje) tiene un número de identificación único de 18 o más dígitos. Para poder visualizarlos y utilizarlos en tus archivos de configuración, es obligatorio activar el Modo Desarrollador.

---

## ⚙️ 1. Activación del Modo Desarrollador en PC (Actualizado)

La interfaz de Discord ha cambiado de lugar esta opción. Sigue estos nuevos pasos para la versión de escritorio y web:

1.  Abre Discord y haz clic en los **Ajustes de Usuario** (icono de rueda dentada <img width="24" height="25" alt="image" src="https://github.com/user-attachments/assets/de83f762-530b-4497-a52a-6ada559542ee" /> en la esquina inferior izquierda, junto a tu nombre).
2.  En el menú lateral, baja hasta la categoría de **Ajustes de App** y haz clic en **Desarrollador**.
3.  Busca la primera opción: **Modo desarrollador**.
4.  Activa el interruptor para que se ponga de color **azul**.

### 📸 Referencia Visual de Activación (by @tusmocraft)
Aquí puedes ver cómo debe quedar tu pantalla de ajustes después de activar el modo:

<img width="800" src="https://github.com/user-attachments/assets/94fc5c2a-0588-43c5-bcf7-188498a41fd3" alt="Ajustes de TUSMOCRAFT con Modo Desarrollador activado en Discord">

---

## 📱 2. Activación en Dispositivos Móviles (Android / iOS)

Para los que gestionan la comunidad desde el teléfono celular:

1.  Abre la app de Discord y toca tu **foto de perfil** (abajo a la derecha) para abrir los ajustes.
2.  Baja hasta la sección **Ajustes de App** y toca en **Avanzado**.
3.  Activa el interruptor de **Modo desarrollador**.

---

## 📋 3. Cómo Copiar IDs: Guía de Referencia Rápida

Una vez activo el modo, al hacer clic derecho (en PC) o mantener presionado (en móvil) sobre un elemento, aparecerá la opción al final del menú: **"Copiar ID"**.

### A. IDs de Servidores y Categorías
* **Servidores:** Haz clic derecho sobre el icono del servidor en la lista de la izquierda.
* **Categorías:** Haz clic derecho sobre el nombre de la categoría completa (ej: `🎮 CATEGORÍA GAMING`). Esto copia el ID del sector entero, muy útil para configurar bots de administración.

### B. IDs de Canales (Texto, Voz y Foros)
* Haz clic derecho sobre el nombre del canal específico (ej: `#guias-y-tutoriales`).
* Esto copia el ID del canal, que usarás en tus archivos para definir dónde van los logs, anuncios automáticos o permisos.

### C. IDs de Usuarios y Roles
* **Usuarios:** Haz clic derecho sobre el avatar o nombre de cualquier miembro (incluido tú mismo o un bot).
* **Roles:** Ve a Ajustes del Servidor > Roles. Haz clic en los tres puntos `...` junto al rol y selecciona **Copiar ID**.

### D. IDs de Mensajes Individuales
* Pasa el cursor sobre un mensaje, haz clic en los tres puntos `...` de "Más opciones" y selecciona **Copiar ID**. Útil para sistemas de soporte por tickets o reportes.

---

## 🚑 4. Solución de Problemas Frecuentes

### Error: "No me aparece la opción de Copiar ID"
-   **Causa:** Discord no siempre aplica los ajustes de inmediato o la sesión necesita recargarse.
-   **Solución:** Vuelve al menú *Desarrollador*, apaga el interruptor, espera unos segundos, vuélvelo a encender y reinicia la aplicación (Ctrl + R en PC).

### El ID copiado no funciona en el bot
-   **Verificación:** Asegúrate de no haber copiado el ID de un mensaje en lugar de un usuario. Los IDs de mensajes cambian con cada texto enviado; los de usuarios y canales son fijos. También revisa que el bot tenga permisos para ver ese canal o categoría en específico.

---
© 2026 Qyroth Resources | Guías de Infraestructura por tusmocraft
