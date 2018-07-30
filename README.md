# Documentación NERY

Desarrollo backend, apps en IONIC 3, Frontend panel y Broker NodeJs


# TODO list

 - [x] Base de datos MYSQL
 - [ ] API Django
	 - [x] Alertas
	 - [x] Registro AppUsers y PanelUsers
	 - [x] Login AppUsers y PanelUsers
	 - [x]  API CRUD dispositivos
	 - [x] API CRUD de registro de datos medidos por sensores
	 - [x] API CRUD de preferencias iniciales de usuarios
	 - [x] API CRUD de configuración del perfil de usuario
	 - [x] Tabla de tarifas de CFE
	 - [x] API CRUD de sensores
	 - [ ] Lógica de Orphan al eliminar registros de datos medidos por sensores
	 - [ ] Cálculo entre valor consumido y tarifas CFE
	 - [ ] Creación alertas predeterminadas
	 - [ ] Cálculo de valores de consumo por periodos(Actualmente se arroja el total)
	 - [ ]  Toda la conexión con el broker
	 - [ ] Manejo de decorators para administración de Is_owner(actualmente tiene lógica básica de usuario admin y usuario común)


 - [ ] App Ionic 3 maquetado
	- [x] Primera pantalla
	- [x] Inicio
	- [x] Registro
	- [x] Pantalla de inicio con gráficas de consumo
	- [x] Pantalla de lista de sensores
	- [x] Pantalla de agregador de sensor
	- [x] Pantalla de estadísticas de un sensore con gráficas y datos de consumo
	- [x] Pantalla de ajustes
	- [x] Pantalla de administrar alertas
	- [x] Pantalla de agregar nueva alerta
	- [x] Pantalla de cambiar contraseña
	- [ ] Pantalla de editar alertas
	- [ ] Pantalla de editar sensores
	- [ ] Pantalla de Dispositivos
		- [ ] Lista de dispositivos
		- [ ] Tutorial de agregado de dispositivo tipo Blastbot
	- [ ] Mejorar diseño por feedback
	- [ ] Ajustar flujo dependiendo de feedback
	- [ ] Agregar pantalla para agregar preferencias iniciales en primer login
	- [ ] Cambiar pantallas de agregado de alertas, incrustar la opción de agregar una alerta predeterminada

- [ ] App Ionic 3 endpoints conectados
	- [x] Inicio de sesión
	- [x] Registro
	- [x] Pantall de inicio, datos reales de sensores y consumo total(gráficas con datos reales de la DB)
	- [x] Lista de sensores
	- [x] Estadísticas de cada sensor(con la lógica básica es lo que arroja el endpoint actualmente)
	- [x] Agregado de alertas (básicas no predeterminadas)
	- [x] Editar ajustes(activar alertas, notificaciones, errores, etc)
	- [x] Cambiar contraseña
	- [ ] Administrar alertas creadas
	- [ ] Dispositivos
	- [ ] Historial de consumo(por periodos)
	- [ ] Implementar la vista en tiempo real(los datos son estáticos hasta que se recarga la vista)

# Scripts
Actualmente se tiene 2 scripts para simular la insersión de información en la DB de manera automática, un script simula la insersión y el otro simula fecha de corte y calcula la información con reglas básicas(consumo-costo).

# Broker
Actualmente no se ha desarrollado nada aún del broker, a espera de poder implementarlo con el hardware.
