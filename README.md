# CALCULOAREA
# Act3
CALCULOAREA

Proyecto escolar de Laboratorio de Programación para aplicar el enfoque modular y el diseño Top-Down en C++.

Objetivo

Calcular el área de un círculo a partir de un radio positivo usando una función modular.

Fórmula utilizada:

Área = PI × radio²

Estructura

/calculoarea/
├── .gitignore                      <-- Archivo para que Git ignore carpetas de configuración (.vscode)
├── LICENSE                         <-- Archivo de licencia MIT del proyecto (Uso escolar)
├── README.md                       <-- Archivo explicativo del programa desarrollado
├── docs/                           <-- Carpeta exclusiva para documentación
│   └── InformeProyectoCALCULOAREA.pdf <-- ENTREGABLE (Informe PDF en Normas APA v7)
├── src/                            <-- Carpeta para los códigos fuente del proyecto
│   └── main.cpp                    <-- Código fuente modular en C++
└── capturas/                       <-- Carpeta para guardar las evidencias locales (Imágenes .png)
    ├── compilacion_area.png        <-- Captura de la terminal compilando y corriendo el programa
    └── diagrama_flujo.png          <-- Captura o foto del diagrama de flujo de su programa

Compilación en Windows

Desde la raíz del proyecto:

g++ src/main.cpp -o src/area.exe
.\src\area.exe

Enfoque modular

El programa separa el cálculo del área en la función calcularAreaCirculo, que recibe el radio, realiza la operación y devuelve el resultado a main().
