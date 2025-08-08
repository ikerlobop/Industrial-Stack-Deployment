# Industrial Data Stack

Este proyecto contiene una arquitectura ligera para el procesamiento, visualización y gestión de datos industriales usando Docker Compose. Integra múltiples servicios útiles para entornos de IoT, automatización y análisis en tiempo real.

##  Servicios incluidos

- **Python App**: Versión Python 3.12
- **InfluxDB**: Base de datos de series temporales para almacenar métricas industriales.
- **Grafana**: Visualización avanzada de datos provenientes de InfluxDB.
- **Node-RED**: Entorno de desarrollo visual para orquestación y conexión de datos IoT.
- **Apache Flink**: Procesamiento de datos en tiempo real.

3. Accede a los servicios desde tu navegador:

   - Grafana: http://localhost:3000  
   - Node-RED: http://localhost:1880  
   - InfluxDB: http://localhost:8086  
   - Flink Dashboard: http://localhost:8081

## Credenciales por defecto

- **Grafana**:  
  Usuario: `admin`  
  Contraseña: `admin123`

- **InfluxDB Admin**:  
  Usuario: `admin`  
  Contraseña: `admin123`

- **InfluxDB User**:  
  Usuario: `user`  
  Contraseña: `user123`

---

Este stack es ideal como base para proyectos de **monitorización**, **procesamiento de datos industriales** y **prototipado IoT**.
