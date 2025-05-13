# Prueba-de-desempeño
1.al usuario se le dara un menu de opciones con las funciones necesario para iniciar el codigo, cada una enumerada del 1 al 6
- 2.para ejecutar el programa es necesario agregar almenos dos productos que se añaden a traves de la funcion add_Products, pueden ser mas de dos valores pero para hacerlo facil y explicito es recomendable usar 2(el programa cuenta con todo tipo de restrincciones para que el usuario no se le permita ingresar un valor invalido
3.una vez agregados se puede empezar a operar con las otras funciones:Show_Product,Update_Products,Delete_Products,Calculate_Totalvalue.
4.cada una de estas funciones y en este paso explicare cada una:
-Show_Product: esta funcion permite al usuario buscar un producto en especifico para conocer su valor y monto. primero le pide al usuario el nombre de el producto que quiere buscar, una vez lo encuentra este le muestra el valor y el monto del producto, en el caso de no encontrarlo se le mandara un mensaje avisandole al usuario que no existe este producto en el inventario, lo cual deberia agregarlo
-Update_Products:esta funcion permite actualizar el precio a un producto.le pide el nombre del producto,si el producto de encuentra en el inventario, se le solicita el precio que quiere establecer a ese producto,despues cambia los valores del precio y actualiza el inventario, en el caso de que no se encuentre se le avisa al usuario que no existe
-Delete_Products:esta funcion permite eliminar un producto del inventario.empieza pidiendole al usuario el nombre del producto que quiere eliminar y si lo encuentra elimina este elemento del inventario, en el caso de que no, este le avisa al usuario que no existe el elemento que esta buscando
-Calculate_Totalvalue:esta funcion calcula el valor total multiplicando el precio de los productos por su cantidad, mostrandolo por consola
5.para salir del programa el ususario debe seleccionar la opcion salir
