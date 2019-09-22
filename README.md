# proyecto2-QA-Grupo04

## Topicos especiales en telematica

Realizado por:
- Stiven Hurtado Loaiza
- Alejandro Diaz
- Juan pablo Urango


![image](https://user-images.githubusercontent.com/30469862/63234944-36b18100-c1fd-11e9-9627-99f1158fded5.png)

### 15-09-2019
Se agrega al marco de referencia los QA, implementados y especificados al proyecto (Disponibilidad, seguridad y rendimiento)
en el cual se trabaja pruebas de carga y stress en (rendimiento) con JMeter, se desplega la app en otro servidor y se instala nginx en otro servidor para el balanceo de carga y se pretende tener otro servidor para la base de datos (disponibilidad) , en (seguridad) se trabaja con el protocolo 443 el cual es para la transferencia segura de datos y se trabaja con una dependencia (bcryptjs) en el cual encripta la contraseña, tambien se pretende implementar autenticacion con redes sociales por medio de Google Auth que ofrece un modulo passport-google-oauth.

### 21-09-2019
Se hacen cambios en las vistas para diferenciar cuando el balanceador de carga apunta ya sea al servidor de la app1 o servidor de la app2.

### 21-09-2019
Se implementan los cambios de diseño y se agregan módulos nuevos como compression de node con la finalidad de disminuir el tamaño de bytes con los cuales responden los servicios web implementados y así mejorar el atributo de rendimiento en la web app

### 21-09-2019
Se agrega en el documento de marco de referencia las evidencias resultantes de las pruebas realizadas con JMeter, unas antes de las mejoras para rendimiento y las otras luego de implementar los cambios, para así lograr ver el comparativo de resultados.

### 21-09-2019
Se hacen las pruebas pertinentes con el balanceador de carga apagando un servidor, en el cual responde satisfactoriamente hacia el otro servidor, y tambien se hace lo mismo con el otro servidor para garantizar que responda a los dos servidores cuando uno de los dos se encuentra caido.





