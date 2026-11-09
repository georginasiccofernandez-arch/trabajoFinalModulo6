# Reflexión individual - Georgina Sicco
 Mi revisión segun la división de tareas en el equipo consistió en correr el pipeline y las pruebas, hacer este cálculo por mi cuenta y revisar los resúmenes; no escribí el código base. Al comprobar V001 y V002 entendí que es importante calcular el margen global usando las ventas totales y el margen total, en lugar de promediar los porcentajes de cada venta ya que las operaciones tienen distintos montos.
 
Para comprobarlo, recalculé las dos filas: la politica v1 (V001) tuvo 250 UM en ventas, 150 en costos y por lo tanto 100 de margen; V002 tiene 1.200 en ventas, 840 en costos y 360 de margen. Juntas suman 1.450 en ventas y 460 de margen, o sea, 31,72%. Después comparé los resúmenes v1 y v2: los importes generales se mantienen, pero el estado pasa de "SIN ALERTA" a "ALERTA" cuando el umbral cambia de 25% a 30%.

Me es importante destacar que, una alerta indica que el resultado cruza una regla definida, pero por sí sola no explica la causa ni demuestra que las ventas hayan bajado, por esto siempre es interesante la revisión humana de la política para poner el resultado en contexto.
