📋 Sistema de Validación de Entradas - Los Hijos de Tencha

Sistema completo para la gestión y validación de entradas para eventos, desarrollado específicamente para Los Hijos de Tencha. Incluye panel administrativo y validador con escáner QR integrado.

🚀 Características Principales

🔐 Panel Administrativo (index.html)

✅ Login seguro con contraseña única para administradores
✅ Gestión de eventos: Crear, listar y organizar eventos
✅ Gestión de asistentes: Agregar asistentes a eventos específicos
✅ Generación de QR: Cada asistente recibe un código QR único
✅ Descarga de QR: Exportar entradas como imágenes PNG
✅ Visualización de estadísticas: Total, ingresados y pendientes por evento
📷 Panel Validador (validador.html)

✅ Login seguro independiente para validadores
✅ Escáner QR integrado: Lectura rápida de códigos QR
✅ Validación manual: Ingresar ID manualmente cuando el escáner falle
✅ Cambio de cámara: Alternar entre cámara frontal y trasera
✅ Lista de asistentes: Ver todos los asistentes de un evento
✅ Control de ingreso: Registra automáticamente fecha y hora de ingreso
✅ Prevención de doble ingreso: No permite validar dos veces el mismo código
🛠️ Tecnologías Utilizadas

Frontend: HTML5, CSS3, JavaScript Vanilla
Backend: Firebase Firestore (Base de datos en tiempo real)
Autenticación: Sistema simple de contraseña
Generación QR: QRCode.js
Escáner QR: html5-qrcode
Descarga de QR: html2canvas

🎯 Flujo de Uso

Para Administradores:

Acceder al panel: Abrir index.html y login con tencha2026
Crear evento: Completar formulario en pestaña "Crear"
Agregar asistentes: Seleccionar evento y completar datos
Ver asistentes: Pestaña "Asistentes" para listar y generar QR
Descargar QR: Presionar botón 📱 para ver y descargar entrada
Para Validadores:

Acceder al validador: Abrir validador.html y login con tencha2026
Escanear QR: Usar la cámara para leer códigos
Validación manual: Si el escáner falla, ingresar ID manualmente
Verificar ingreso: El sistema marca automáticamente al asistente
Lista de asistentes: Ver todos los asistentes y sus estados

🔒 Seguridad

Login independiente: Admin y Validador tienen sesiones separadas
Prevención de doble ingreso: Un asistente solo puede validar una vez
Almacenamiento local: La sesión persiste hasta cerrar el navegador
Contraseña única: Misma contraseña para ambos paneles (configurable)
🖥️ Requisitos del Sistema

Navegador web moderno (Chrome, Firefox, Edge, Safari)
Conexión a Internet (para Firebase y dependencias)
Cámara (para el validador)
JavaScript habilitado
🚨 Solución de Problemas

La cámara no funciona en el validador

Verificar permisos de cámara en el navegador
Probar en otro navegador (Chrome recomendado)
Usar la validación manual como alternativa
Error de conexión a Firebase

Verificar conexión a Internet
Revisar que las credenciales de Firebase sean correctas
Asegurar que Firestore esté habilitado
No se generan los QRs

Verificar que el asistente tenga ID asignado
Revisar la consola del navegador por errores
Confirmar que las librerías se cargaron correctamente
📝 Notas Importantes

Logo: Asegúrate de tener img/logo.webp en la ruta correcta
Persistencia: Los datos se almacenan en Firebase, no localmente
Responsive: Adaptado para móviles y desktop
Offline: Requiere conexión a Internet para funcionar
📄 Licencia

Proyecto desarrollado exclusivamente para Los Hijos de Tencha. Todos los derechos reservados.

👥 Equipo

Desarrollado por: [Tu Nombre / Empresa]
Cliente: Los Hijos de Tencha
Versión: 1.0.0

