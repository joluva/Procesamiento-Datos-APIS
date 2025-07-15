# Procesamiento-Datos-APIS
curso data sciences APIs de los módulos de procesamiento de datos

## Descripción

Se encuentran todos los modulos correspondientes a las APIS de la materia

## Módulos que integran la materia

### MOD-1 API-1 
    Instalación de Python
    Instalación IDE Visual Studio Code
    Instalación de las bibliotecas numpy - pandas
    Verificación de las versiones de todo lo instalado
    Creación de un script donde se crean dos arrays ( a - b) usando numpy, luego           sumar ambos y mostrando el resultado

### MOD-2 API-2
    Aplicar lo aprendido con pandas y numpy
    Crear array 3D y mostrar con un print la salida del mismo
    Agregar datos al array 
    Crear un array con formato (3,3), mostrarlo con shape
    Con pandas crear una seria de marcas_productos
    Crear una seie color cantidad, donde el index sea el nombre de colores(Azul, Blanco, Celeste, Nogro, Rojo)

### MOD-3 API-3
    Después de haber realizado las actividades de los módulos 1 y 2, la empresa
    Data-Lab observa que estamos avanzando exitosamente.
    Continuando con el proceso de onboarding sobre procesamiento de datos,
    nos piden en este módulo que demostremos nuestros conocimientos
    relacionados con el ordenamiento de datos, donde debemos realizar los
    siguientes ejercicios que les permitirá conocer si sabemos lo necesario para
    ordenar.
    Consigna:
        1 - Generar con pandas una serie de marcas de autos (Marcas_Autos), por
            ejemplo "RENAULT","BMW", "TOYOTA", "FORD","CITROEN", "FIAT",
            y compartir el output en una captura de pantalla donde se demuestre el
            orden de las marcas de manera alfabética.
        2 - Usando pandas, vamos a crear un DataFrame que contenga: usuarios,
            fecha, cantidad de consultas. Compartir el output en una captura de pantalla
            donde se demuestre el DataFrame con sus datos requeridos.
            Ejemplo de fecha: '2023-01-23'.
            Ejemplo de usuario: 'gcastillo'.
            Ejemplo de consulta: 7.
        3 – El objetivo general es crear una tabla dinámica usando pandas a través
            de un DataFrame. En este ejercicio debemos compartir el output en una
            captura de pantalla en 2 pasos. En el primer paso, mostrar el DataFrame con
            sus datos requeridos, llamado (planilla_enero) que contenga los siguientes
            datos aleatorios: "Nombre", "Fecha", "Consumos Mensuales".

### MOD-4 API-4
    Finalmente estamos por terminar el proceso de onboarding que
    comenzamos en el M1 y se continuó en el M2 y M3, la empresa de
    servicios Data-Lab, le agrada el desenvolvimiento en las tareas y los
    procesos que se están desarrollando durante el onboarding.
    Recordando las tareas que esta empresa busca en su personal, se pueden
    atender los proyectos de los clientes donde se deben resolver problemas
    relacionados al área de procesamiento de datos.
    Por ello para terminar el onboarding, se deben realizar los siguientes
    ejercicios, que les permitirá conocer si sabemos lo necesario sobre los
    tipos de datos y cómo se grafican.
    Consignas:
        1 -Instalar la librería de python tk y la librería matplotlib.
           Luego dejar una captura de pantalla de las 2 herramientas instaladas.
           (Sugerencia capturar la ventanita de tk, para esto revisar comando tkinter).
        2 - Ejecutar el siguiente ejercicio y colocar la captura de pantalla de la gráfica
            que generó.
            python3
        3- De una gráfica, generar el ejercicio necesario para obtenerlo, se deja
           ejemplo de cómo sería el código, rellenar lo necesario:
           python3
                matplotlib import pyplot as plt
                x = []
                y = []
                # buscar función para el tipo de gráfico de barras
                plt.EJEMPLO(x, y)
                plt.show()
        4 - Ejecutar el siguiente ejercicio, compartir una captura de pantalla,
            cambiando el título y modificando cantidades de frutas.
                data = {'manzanas': 10, 'naranjas': 15, 'limones': 5, 'peras': 20}
                Nombres= list(data.keys())
                Valores= list(data.values())
                fig, axs = plt.subplots(1, 3, figsize=(9, 3), sharey=True)
                axs[0].bar(Nombres, Valores)
                axs[1].scatter(Nombres, Valores)
                axs[2].plot(Nombres, Valores)
                fig.suptitle('Cantidades y Tipos')
                plt.show()