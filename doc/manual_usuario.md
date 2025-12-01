# MANUAL DE USUARIO CINEMA WITCHERZH

## Descripción General
El Cinema WitcherZH es un programa de consola desarrollado en Python que permite gestionar el sistema de un cine universitario. Está diseñado para ofrecer una experiencia intuitiva y eficiente para la comunidad universitaria.

## Funcionalidades Principales

### 1. **Registrarse como Usuario**
**Propósito:** Crear una cuenta en el sistema del cine.

**Proceso:**
- Seleccione la opción **1. REGISTRAR USUARIO** del menú principal
- Ingrese los siguientes datos:
  - **Nombre:** Mínimo 3 letras, sin números
  - **Apellido:** Mínimo 3 letras, sin números  
  - **Documento:** Entre 3 y 15 dígitos, solo números
  - **Vínculo:** Elija entre:
    - Estudiante ($7,500)
    - Docente ($10,000)
    - Administrativo ($8,500)
    - Oficial interno ($7,000)
    - Público externo ($15,000)

**Validaciones:**
- El sistema verifica automáticamente que los datos sean válidos
- No se permiten documentos duplicados
- El vínculo determina el precio del tiquete

### 2. **Realizar Reservas de Películas**
**Propósito:** Comprar tiquetes para las funciones del fin de semana.

**Requisitos:**
- Debe estar registrado previamente en el sistema
- Tener su documento a la mano

**Proceso:**
1. Seleccione **2. REGISTRAR RESERVA**
2. Ingrese su número de documento
3. Elija una película de la cartelera disponible
4. Seleccione un asiento disponible del mapa de butacas
5. Confirme la reserva y reciba su factura

**Características:**
- Visualización de asientos: "O" = Disponible, "X" = Ocupado
- Elección libre de butacas
- Factura automática con todos los detalles
- Descuento automático según tipo de vínculo

### 3. **Cancelar Reservas**
**Propósito:** Eliminar reservas existentes.

**Proceso:**
1. Seleccione **3. CANCELAR RESERVA**
2. Ingrese su documento
3. Vea la lista de sus reservas activas
4. Seleccione la reserva a cancelar
5. Confirme la cancelación

**Efectos:**
- El asiento vuelve a estar disponible
- Se libera el espacio en la función
- Se elimina la reserva de su historial

### 4. **Consultar Cartelera del Fin de Semana**
**Propósito:** Ver las películas disponibles.

**Proceso:**
- Seleccione **4. CONSULTAR FUNCIONES FIN DE SEMANA**
- Vea la lista completa con:
  - Día y hora de la función
  - Nombre de la película
  - Butacas disponibles

**Información mostrada:**
- Programación de viernes, sábado y domingo
- Disponibilidad en tiempo real
- Horarios y títulos de películas

### 5. **Acceso Administrador**
**Propósito:** Gestión del sistema para administradores.

**Credenciales de acceso:**
- Usuarios autorizados
- Documentos correspondientes requeridos

**Reportes disponibles:**
1. Total de reservas registradas
2. Total de tiquetes vendidos  
3. Total de reservas realizadas
4. Total de pagos recibidos
5. Promedio por venta diario
6. Lista completa de usuarios
7. Estadísticas de usuarios (más y menos reservas)

