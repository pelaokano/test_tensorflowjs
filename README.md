# Bienvenido al repositorio test_tensorflowjs 🤓

Este repositorio contiene todos los componentes necesarios para desplegar una aplicación web que permite implementar un modelo de machine learning entrenado en Python con la librería Tensorflow, que luego es exportado a tensorflowjs para trabajar en Javascript, es un precursor o inicio de un gemelo digital de un relé de protección basado en Machine Lerning.

Este modelo permite clasificar cuando una falla es dentro o fuera de una linea de alta tensión. Se utilizo una base de datos del software Digsilent en donde se modelaron tres lineas de alta tensión ([ base_digilent ](https://github.com/pelaokano/test_tensorflowjs/tree/main/base_digilent " base_digilent ")), se generan archivos comtrade mediante un script de Python que interactua con Digsilent y luego se entrena el modelo ([jupyter](https://github.com/pelaokano/test_tensorflowjs/tree/main/jupyter "jupyter")) considerando como fallas internas las producidas en la linea 1, y las fallas externas son las producidas en la linea 3.

- [Archivos comtrades](https://github.com/pelaokano/test_tensorflowjs/tree/main/resultados "archivos comtrades"): Mediante un script en Python que interactua con el software Digsilent se genera el conjunto de entrenamiento, archivos comtrades que muestran el comportamiento de las variables (voltaje y corriente) mientras se simula la falla en las lineas.

- [Modelo exportado a tensorflowjs](https://github.com/pelaokano/test_tensorflowjs/tree/main/jsmodel "modelo exportado a tensorflowjs"): Luego de entrenado el modelo se procede a exportar a un formato compatible con la libreria tensorflowjs de javascript.

- [Archivos de prueba](https://github.com/pelaokano/test_tensorflowjs/tree/main/archivos_test "archivos de prueba"): Son archivos generados comtrades exportados en formato csv para probar la aplicación web.

- [imagenes del sitio web](https://github.com/pelaokano/test_tensorflowjs/tree/main/imagen "imagenes del sitio web"): Imagen de la red modelada en Disilent.

- [Archivo index](https://github.com/pelaokano/test_tensorflowjs/blob/main/index.html "archivo index"): Archivo que integra el modelo en tensorflowjs y todo el codigo javascript y html necesario para desplegar la aplicación web.

- [Sitio web de la app](https://pelaokano.github.io/ "sitio web de la app"): Link del sitio web desplegado en github page.

Nota:
 - Sitio para crear archivos README: https://pandao.github.io/editor.md/en.html
 - Sitio con emoji: https://getemoji.com/