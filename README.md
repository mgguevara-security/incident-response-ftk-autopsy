\# Investigación Forense: Caso Oceanix Living (OLI-2022A-0098)



\## 1. Resumen del Incidente

Se investiga una filtración de datos críticos en la empresa \*\*Oceanix Living\*\*. El activo comprometido es el proyecto \*\*AquaDome 3000\*\* (diseños de hábitats flotantes). La seguridad física fue vulnerada ya que el sistema afectado no tiene conexión a Internet, lo que apunta a una amenaza interna mediante el uso de dispositivos extraíbles.



\## 2. Marco de Respuesta a Incidentes

Como analista de seguridad, apliqué el protocolo de respuesta para asegurar la escena del crimen digital:

\* \*\*Identificación:\*\* Se detectó la falta de integridad en los planos técnicos.

\* \*\*Contención:\*\* Se confiscaron los dispositivos de 6 sospechosos autorizados.

\* \*\*Preservación:\*\* Se inició la cadena de custodia para la memoria USB de \*\*Tuttle Leach\*\* (Aprendiz de ingeniería).



\## 3. Fase Técnica 1: Adquisición de Evidencia (FTK Imager)

Para garantizar que la evidencia sea admisible ante la ley, utilicé \*\*FTK Imager\*\* para crear una imagen forense.



\* \*\*Herramientas:\*\* Entorno virtualizado con herramientas forenses profesionales.

\* \*\*Procedimiento:\*\* Creación de una imagen física bit-a-bit para capturar todo el espacio del disco, incluyendo áreas no asignadas.

\* \*\*Integridad:\*\* Verificación mediante Hashes (MD5/SHA1) para asegurar que la copia es idéntica al original.



!\[Escritorio Forense](./imagenes/escritorio\_herramientas.png)

\*Figura 1: Entorno de trabajo con FTK Imager y Autopsy.\*



!\[Cadena de Custodia](./imagenes/cadena\_custodia.png)

\*Figura 2: Registro oficial de la evidencia y cadena de custodia.\*



!\[Creando Imagen FTK](./imagenes/creando\_imagen\_ftk.png)

\*Figura 3: Proceso de adquisición de la imagen forense de la USB sospechosa.\*



\## 4. Fase Técnica 2: Análisis Digital (Autopsy)

Con la imagen forense creada, utilicé \*\*Autopsy\*\* para explorar el contenido de la USB y desmentir la versión del sospechoso (quien afirmaba tener solo fotos submarinas).



\### Hallazgos de "Data Carving":

Al analizar los \*\*archivos eliminados\*\*, logré recuperar documentos que el sospechoso intentó borrar para ocultar el robo.



\* \*\*Evidencia encontrada:\*\* Archivos recuperados del proyecto AquaDome 3000 (planos y especificaciones).

\* \*\*Estado de los archivos:\*\* Marcados como eliminados en el sistema de archivos, pero recuperados íntegramente mediante el análisis de sectores.



!\[Analisis de Eliminados](./imagenes/analisis\_eliminados.png)

\*Figura 4: Recuperación de documentos críticos eliminados en Autopsy.\*



\## 5. Conclusión

La investigación demuestra de manera irrefutable que el dispositivo USB de Tuttle Leach fue utilizado para extraer información confidencial de Oceanix Living. El intento de eliminar los archivos confirma la mala intención. 



Este caso destaca la importancia de la \*\*seguridad física\*\* y el \*\*análisis forense\*\* para resolver incidentes de amenazas internas.



---

\*Este proyecto forma parte de mi formación en ciberseguridad y análisis forense digital.\*

