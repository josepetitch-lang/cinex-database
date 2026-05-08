# Taquilla Evidence
<img width="479" height="268" alt="Captura de pantalla 2026-05-07 220621" src="https://github.com/user-attachments/assets/48b058a7-8278-4eb7-81d9-d97780d6fdd3" />

# Data Photo
<img width="1346" height="247" alt="Captura de pantalla 2026-05-07 215651" src="https://github.com/user-attachments/assets/da69a340-179b-4091-b366-23242d0c705e" />

# Funciones Evidence
<img width="758" height="365" alt="Captura de pantalla 2026-05-07 215700" src="https://github.com/user-attachments/assets/a0e48c68-e8b7-4c60-b48d-64a9e5e57b3e" />

# Usuarios Evidence
<img width="816" height="446" alt="Captura de pantalla 2026-05-07 215709" src="https://github.com/user-attachments/assets/c1fd4be1-438c-4914-979c-0942fbdce1f7" />


# CODE EVIDENCE: 

INSERT INTO Taquilla (ID_TAQUILLA, Direccion, Horario) 
VALUES (1, 'Cine Central UNEFA', '09:00 - 21:00');


INSERT INTO Sala (ID_SALA, FILA, Numero_Sala, Disponibilidad, Taquilla_Sala) 
VALUES (1, 'A', 1, 50, 1);

INSERT INTO Sala (ID_SALA, FILA, Numero_Sala, Disponibilidad, Taquilla_Sala) 
VALUES (2, 'B', 2, 40, 1);


INSERT INTO Funciones (ID_Funciones, Pelicula, Duracion, Hora, FECHA, Sala_Funcion)
VALUES (1, 'Avengers: Endgame', '3h', '14:00', '2026-05-03', 1);
[10:46 a. m., 3/5/2026] who cares: INSERT INTO Usuarios (Id, CI, Nombre, Apellido, Usuario, Contraseña)
VALUES (1, '28123456', 'Administrador', 'UNEFA', 'admin', '1234');

ALTER TABLE Usuarios ADD COLUMN Puesto TEXT;

INSERT INTO Taquilla (ID_TAQUILLA, Direccion, Horario, ID_Funcion_Taquilla)
VALUES (1, 'Sede Principal Falcón', '08:00 - 20:00', 1);
