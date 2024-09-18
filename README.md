<h1>Procesamiento de Imagen a Matriz con OpenCV y NumPy</h1>
<br>


 Se utiliza cv2.imread('carro.jpg') para leer la imagen carro.jpg. El resultado es una matriz tridimensional que contiene los valores de los píxeles en formato BGR (Azul, Verde, Rojo).

Verificación de la imagen: Si la imagen se carga correctamente, el programa continúa; de lo contrario, muestra un mensaje de error: ERROR DE MATRIZ.

Conversión a matriz NumPy: Una vez cargada la imagen, se convierte a una matriz NumPy mediante np.array(imagen). Esto permite manipular y procesar los datos de la imagen fácilmente.

Impresión de la matriz: La matriz resultante se imprime en la consola, mostrando los valores de los píxeles.

Manejo de errores: Si la imagen no se puede cargar, se imprime un mensaje de error indicando el fallo en la carga.
