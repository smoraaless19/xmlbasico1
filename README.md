<!--
Nombre: Sergio Morales
Curso: ASIR1
Fecha: 20/03/2025
Ejercicio: XML Básico I
-->

<!-- Definición de una persona -->
<persona>
    <nombre>Juan Pérez</nombre>
    <edad>30</edad>
    <ciudad>Madrid</ciudad>
</persona>

<!-- 
Fecha: 12/02/2025
Cambio: Se agregó el campo correo-electronico 
-->
<persona>
    <nombre>Juan Pérez</nombre>
    <edad>30</edad>
    <ciudad>Madrid</ciudad>
    <correo-electronico>juan@example.com</correo-electronico>
</persona>

<!-- Estructura organizada de una empresa -->
<empresa>
    <empleado>
        <nombre>Ana López</nombre>
        <puesto>Desarrolladora</puesto>
        <email>ana.lopez@example.com</email>
    </empleado>
    <empleado>
        <nombre>Carlos Ramírez</nombre>
        <puesto>Diseñador</puesto>
        <email>carlos.ramirez@example.com</email>
    </empleado>
</empresa>

<!-- Control de versiones con Git -->

<!-- Inicializar Git en el directorio del proyecto -->
git init

<!-- Crear un archivo .gitignore para evitar archivos innecesarios -->
echo "logs/" >> .gitignore
echo "backup/" >> .gitignore

<!-- Realizar el primer commit -->
git add .
git commit -m "Inicio del archivo XML"

<!-- Agregar el repositorio remoto -->
git remote add origin https://github.com/usuario/repositorio.git

<!-- Subir los cambios al repositorio remoto -->
git push -u origin main

<!-- Reglas generales -->
<!-- 
Mantener una estructura clara y ordenada.
Comentar cambios con fecha.
Usar nombres de etiquetas descriptivos.
-->
