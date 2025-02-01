
# SushiPop
Desarrollo web para SushiPop. Trabajo realizado en grupo para materia de la TECNICATURA SUPERIOR EN ANALISIS DE SISTEMAS en ORT. Commits no estan visibles debido a que esta es una copia. 

🍣 SushiPOP - Sistema de Gestión y Venta de Sushi 🍣
SushiPOP es una plataforma web para la gestión y venta de sushi que permite a clientes realizar pedidos, a empleados gestionar productos y pedidos, y a administradores administrar el sistema.

⚠️ IMPORTANTE: Este proyecto aún se encuentra en desarrollo y necesita mejoras en ciertas áreas. Además de las mejoras listadas, hay varios aspectos que requieren retoques para optimizar la experiencia del usuario y el funcionamiento del sistema.

📌 Funcionalidades principales
🛒 Carrito de Compras
Los clientes pueden agregar productos al carrito desde la página de productos.
Se permite seleccionar la cantidad de cada producto antes de agregarlo.
El carrito muestra los productos agregados y permite eliminarlos.
Una vez completada la selección, los clientes pueden proceder al checkout para finalizar la compra.
👤 Creación de Usuarios
El sistema permite la creación de usuarios con distintos roles:

Clientes: Se pueden registrar desde la plataforma y acceder a su perfil.
Empleados: Solo pueden ser creados por un usuario ADMIN.
Administradores (ADMIN): Se crea automáticamente un administrador con permisos totales al iniciar el sistema.
👥 Tipos de Usuarios y Permisos
1️⃣ Cliente
Puede registrarse e iniciar sesión.
Puede ver y modificar su perfil (nombre, dirección, teléfono, fecha de nacimiento).
Puede agregar productos al carrito y realizar pedidos.
Puede visualizar su historial de compras.
2️⃣ Empleado
No puede registrarse por sí mismo. Solo el ADMIN puede crearlos.
Puede acceder al listado de clientes.
Puede ver su perfil, pero no modificarlo.
Tiene acceso a la gestión de pedidos y productos.
3️⃣ Administrador (ADMIN)
Es el usuario con permisos totales dentro del sistema.
Puede crear, modificar y eliminar empleados.
Puede administrar categorías de productos y productos.
Puede ver la lista de clientes y empleados.
No tiene acceso a compras ni carrito de compras.
🏷️ Creación de Productos y Categorías
Productos:

Solo pueden ser creados por EMPLEADOS.
Se debe seleccionar una categoría al crear un producto.
Se pueden agregar imágenes a los productos.
Categorías:

Solo pueden ser creadas y gestionadas por EMPLEADOS.
Permiten organizar los productos en grupos como Piezas, Rolls, Entradas, Bebidas, etc.
🛍️ Carrito de Compras
Solo está disponible para clientes.
Se muestra un ícono de carrito en la navbar cuando el usuario está logueado.
Los productos en el carrito pueden ser eliminados antes de la compra.
Actualmente no hay un proceso de pago integrado (futuro desarrollo).
🔧 Estado del Proyecto y Mejoras Pendientes
Aunque el sistema es funcional, aún requiere ajustes y optimización en los siguientes aspectos:
✅ Pulir la experiencia del carrito de compras (Confirmación de compra y persistencia de productos).
✅ Optimizar las vistas y el diseño de la interfaz para una mejor usabilidad.

Además de estas mejoras específicas, hay varios aspectos que necesitan retoques para optimizar la funcionalidad y la experiencia del usuario.

💬 Contribuciones y Feedback
Este proyecto está en constante desarrollo, ¡cualquier sugerencia o mejora es bienvenida! 🎉
