# Qronos · Coordinación de pabellones HLF

Prototipo de revisión de una aplicación para coordinar el uso de pabellones quirúrgicos del Hospital Clínico Dra. Eloísa Díaz Insunza (La Florida) con la sociedad concesionaria.

- Versión de revisión con **datos ficticios**. No ingresar información de pacientes.
- Acceso con clave personal: vinculada a un dispositivo, con vencimiento, límite de intentos fallidos y registro de ingresos (solicitarla al autor).
- Las claves de revisión son de solo lectura en el servidor: los cambios de prueba quedan solo en el equipo del revisor.
- Base de datos: Supabase (funciones RPC con verificación de clave; la tabla no es accesible directamente).

© 2026 Mauro César Alcaíno Sánchez
