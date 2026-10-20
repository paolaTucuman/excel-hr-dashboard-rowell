# Datos de práctica

Tres tablas de empleados ficticios de ROWELL S.A. utilizadas en el trabajo final guiado de Excel avanzado y reutilizadas en un curso de Power BI. Fueron proporcionadas en el curso; su origen anterior no está documentado.

| Archivo | Filas | Columnas |
| --- | ---: | --- |
| `Tabla empleados.csv` | 194 | `ID_EMPLEADO`, `NOMBRE`, `CUIDAD`, `FECHA_NAC.`, `SEXO`, `DEPARTAMENTO`, `CARGO`, `JEFE` |
| `Tabla Sueldo.csv` | 194 | `ID_EMPLEADO`, `SUELDO` |
| `Tabla evaluación.csv` | 194 | `ID_EMPLEADO`, `PUNTAJE_EVALUACIÓN` |

Cada tabla contiene una fila por `ID_EMPLEADO`; la clave permite combinar las tres sin duplicar empleados. Los archivos usan punto y coma como separador y codificación Windows-1252. En el CSV de evaluación, los decimales usan coma. `CUIDAD` es el encabezado que trae el archivo original para la ciudad.

No hay periodo de observación ni fecha de corte en los CSV. Los nombres, jefes y demás registros forman parte de los datos ficticios del ejercicio.
