# Desempe-o-Abstraccion-y-Herencia
Abstraccion y Herencia

PAQUETE ESTUDIANTE 11
Programación Orientada a Objetos — Herencia y Abstracción en Python
Nombre: ________________________	Ficha: ________________________	Fecha: ________________________

Instrucciones: Para cada ejercicio debes escribir: (1) la clase abstracta (usando ABC) con sus métodos abstractos, (2) la(s) subclase(s) que hereden e implementen dichos métodos, y (3) al menos un objeto de prueba con llamadas a los métodos. Recuerda importar ABC y abstractmethod del módulo abc.
Ejercicio 1   Sensor, Temperatura y Humedad	Nivel 2
Crea una clase abstracta Sensor con el atributo ubicacion y dos métodos abstractos: leer_dato() y mostrar_alerta(umbral). Crea dos subclases: SensorTemperatura (lectura en grados Celsius) y SensorHumedad (lectura en porcentaje). Cada subclase hereda e implementa sus métodos. Simula dos lecturas por sensor y verifica si se supera el umbral indicado.

Ejercicio 2   Bebida y Tinto	Nivel 1
Crea una clase abstracta Bebida con el atributo nombre y dos métodos abstractos: preparar() y servir(). Crea una subclase Tinto que herede de Bebida y agregue el atributo con_azucar (booleano). Implementa preparar() y servir() con mensajes que indiquen si lleva o no azúcar. Crea dos tintos distintos e invoca todos sus métodos.

Ejercicio 3   Contrato, Trabajador, Fijo y Temporal	Nivel 3
Crea una clase Contrato (tipo, fecha_inicio, duracion_meses). Crea una clase abstracta Trabajador con atributos nombre y contrato (objeto Contrato), y métodos abstractos calcular_salario() y generar_reporte(). Crea subclases EmpleadoFijo (salario_base mensual fijo) y EmpleadoTemporal (tarifa_dia x dias_trabajados). Cada subclase hereda de Trabajador, recibe un objeto Contrato e implementa ambos métodos. Instancia uno de cada tipo y genera sus reportes completos.
