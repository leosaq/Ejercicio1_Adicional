
# Ejercicio1_Adicional

---
1) Guarda un nuevo propietario en la base de datos.  
Establece una conexión, prepara una consulta `INSERT`, asigna los valores desde el objeto recibido y ejecuta la inserción. Luego cierra la conexión.
![image](https://github.com/user-attachments/assets/3d462796-650a-4866-a1ab-c741971a49fb)
---

2) Inserta un turno en la base de datos **solo si no hay conflictos**.

Primero verifica que el vehículo no tenga ya un turno asignado en el mismo día, y que no tenga otro turno en el mismo andén ese mismo día.  
Si no hay conflictos, ejecuta la inserción del nuevo turno.  
Devuelve `true` si se pudo insertar correctamente, o `false` si se detectó un conflicto.


![image](https://github.com/user-attachments/assets/878c8adb-5df8-45d4-8513-482bd17ee6a2)


---
3) Inserta un nuevo vehículo en la base de datos.  
Establece una conexión, prepara una consulta `INSERT`, asigna los valores de placa, marca, estado e ID del propietario desde el objeto recibido, y ejecuta la inserción. Finalmente, cierra la conexión.
![image](https://github.com/user-attachments/assets/dc9a60a8-898b-412a-9c97-957216e7a487)

---
4) Contiene la lógica principal del sistema.  
Centraliza las operaciones para guardar propietarios, vehículos y turnos, delegando el trabajo a las clases de base de datos (`BDPropietario`, `BDVehiculo`, `BDTurno`).  
Permite registrar datos directamente desde la interfaz, validando las reglas necesarias, como evitar turnos duplicados por vehículo en el mismo día o andén.


![image](https://github.com/user-attachments/assets/22d32bd5-f35e-40dc-b7b5-b37df31b493a)

---

5) Diseño de ventana

   
   ![image](https://github.com/user-attachments/assets/f2154338-11e7-475b-ac53-faa9056d0bd6)

---

6)  Script SQL

 
   ![image](https://github.com/user-attachments/assets/540ffb47-bbb1-46f0-b572-76d31a8cf9e0)

   
---
7) Al rellenar todos los Datos si el vehiculo tiene ya en un turno registrado en ese dia mostrara lo siguiente


![image](https://github.com/user-attachments/assets/48ecb0a2-5417-44e4-8fb8-3c1bed54982f)












