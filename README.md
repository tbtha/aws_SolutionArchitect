#### Basicos de AWS 
~~~
ºREGION
como elegir una region ? 
-> compliance, los paises a veces quieren que sus datos permanezcan en su pais 
-> Proximity, reducir latencia 
-> Available services 
-> Pricing /Precios 
ºZONA DE DISPONIBILIDAD 
En una region usualmente sin 3, lo minimo son 2 y lo maximo son 6 
AWS Region Sydney : ap-southeast-2
Available zone  ap-southeast-2a  ap-southeast-2b  ap-southeast-2c
Esta ZA sera uno o mas centro de datos discretos que tienen energia , redes y conectividad redundante
Estas ZA estan separadas entre si para que estan asiladas de desastres 
Igualmente estan conectadas con un andcho de banda alto, redes de latencia ultrabajas y por lo tanto estan completamente vinculados 
ºPuntos de presencia / Edge Location 
Utiles para cuando entreguemos contenido a los usuarios finales con la menos latencia posible 
~~~


****

~~~
Mediante AWS, obtendrá el control y la confianza que necesita para dirigir su empresa de forma segura con el entorno de informática en la nube más flexible y seguro disponible en la actualidad.

Los servicios y soluciones de seguridad de AWs se centran en ofrecer beneficios estrategicos clave a fin permitirle implementar la postura de seguridad optima para su oganizacion 
-> para evitar, defina los permisos e identidad del usuario, defina la protecion de la infraestructura y las medidas de proteccion de los datos para una estategia de adopcion planificada y fluida de AWS
-> para detectar, obtenemos visibilidad de la seguridad de la organizacion con los servicios de registro y monitoreo , tambien debe incorporar esta info a una plataforma escalable para la administracion futura de eventos, prubas y auditoria (AWS y sus servicios pueden ayudarlos a responder ¿Quién tiene acceso a este recurso?/¿Quién ejecutó qué acción?/¿Cuándo y desde dónde se ejecutó la acción?/¿Dónde hay evidencia de que el usuario ejecutó la acción?)
-> para responder, automatice la respuesta a incidentes y la recuperacion frente a estos para ayudar a cambiar el enfoque principal de los equipos de seguridad en torno a responder a la causa raiz o analizarla 
-> para solucionar, Apoveche la automatizacion basada en eventos para corregir y proteger rapidamente su entorno de Aws casi en tiempo real 

~~~

### antes de arquitecto
##### AWS Certified Solutions Architect – Associate valida la experiencia técnica en el diseño y la implementación de sistemas escalables, de alta disponibilidad y tolerantes a errores en AWS.

#### Diseño de arquitecturas resistentes
~~~
Como diseñar soluciones en multiples niveles, 

Solcuiones en funcion de los patrones que acceso, habla del diseño con respecto a quien y que necesita acceder a la arquitectura concreta y como se va a acceder a ella 

2.Arquitecturas de alta disponibilidad y que toleran fallos 

3 Mecanimos de desacoplamiento, diseñaremos un acoplamiento debil entre componentes 
~~~
#### Arquitecturas de alta disponibilidad y que toleran fallos 

****






























