# PROYECTO RESERGO  
## Sistema de Gestión de Reservas de Hotel

DESCRIPCIÓN DEL PROYECTO  
RESERGO es un sistema de gestión de reservas para hoteles desarrollado como parte del curso de Ingeniería de Software en el Instituto Tecnológico de Oaxaca. El proyecto fue creado por Tania Santiago Vásquez y Liz Sanjuan Vásquez bajo la supervisión del profesor Rogelio Noé Limón Cordero.

CARACTERÍSTICAS PRINCIPALES  
El sistema ofrece:  
- Gestión de usuarios: Con roles de administrador y cliente  
- Reservas de habitaciones: Con diferentes tipos de habitaciones (individual, doble, suite, familiar)  
- Seguimiento de pagos: Con referencias únicas para cada transacción  
- Disponibilidad en tiempo real: Consulta de habitaciones disponibles por fechas  
- Interfaces diferenciadas: Para administradores y clientes  

ESTRUCTURA DEL PROYECTO  
BASE DE DATOS  
El sistema utiliza una base de datos MySQL con las siguientes tablas principales:  
- usuarios: Almacena credenciales y roles  
- clientes: Información detallada de clientes  
- administradores: Datos del personal administrativo  
- habitaciones: Catálogo de habitaciones con precios y disponibilidad  
- reservas: Registro de todas las reservas realizadas  

CÓDIGO FUENTE  
El proyecto está organizado en paquetes Java:  

- MODELOS: Clases que representan entidades del sistema  
  - Cliente.java  
  - Habitacion.java  
  - Login.java  
  - Pago.java  
  - Reserva.java  
  - SesionUsuario.java  

- CONTROLADORES: Lógica de negocio  
  - ControladorInicioSession.java  
  - ControladorReserva.java  

- VISTAS: Interfaces gráficas  
  - Clientes.java  
  - Disponibilidad.java  
  - Habitaciones.java  
  - InicioSession.java  
  - MenuAdmi.java  
  - MenuCliente.java  
  - MisReservas.java  
  - Registro.java  
  - Reserva.java  
  - ReservasAdmi.java  

- CONEXIÓN: Gestión de la base de datos  
  - Conexion.java  

FUNCIONALIDADES CLAVE  
- Autenticación segura: Con encriptación SHA-256 para contraseñas  
- Gestión de habitaciones: CRUD completo para administradores  
- Proceso de reserva: Selección de fechas, habitaciones y generación de comprobantes  
- Seguimiento de reservas: Para clientes y administradores  
- Generación de referencias de pago: Automática y única  

TECNOLOGÍAS UTILIZADAS  
- Java SE  
- MySQL  
- Swing para la interfaz gráfica  
- JDBC para conexión a base de datos  
- JCalendar para selección de fechas  

 
