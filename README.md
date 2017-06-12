# app-compiler-4any-device

Es un compilador cross devices de aplicaciones hibridas HTML5, le llamo cross devices porque puede compilar para cualquier tipo de dispositivo tanto móvil como de escritorio. Esta hecho sobre NodeJS y para móviles usa Phonegap 6.4.2 y para Desktop(s) usa NWJS 0.12.1.

Se deja el código html en una carpeta y mediante unos sencillos comandos gulp donde se le pasa el s.o. para el que se quiere publicar la aplicación y por si solo es capaz de coger todas las librerias y fuentes necesarios para acabar dejando en la carpeta dist/app-$so/ un zip con la aplicación lista para publicar en los Apps Stores o instalarlo en cualquier s.o. de escritorio.

Es una herramienta para centralizar la preparación de los distintos paquetes de distribución de una aplicación hibrida HTML5, como puede ser por ejemplo [app-dashboard-skeleton](https://github.com/manumartor/app-dashboard-skeleton). 

También sirve como herramienta para invocar los test unitarios, que se vayan lanzando automáticamente al guardar cualquier cambio en el código para no tener que estar nosotros manualmente lanzando el comando cada vez. Y sirve como herramienta para gestionar el versionado, es decir, cuando se quiera subir el número de versión antes de preparar el paquete simplemente llamando con consola a un comando este nos hace unas preguntas por pantalla y con eso ya automáticamente se modifica el número de versión en todos los ficheros necesarios.

Los o.s. para los que esta preparado y testeado son:
* android
* ios
* osx32
* osx64
* linux32
* linux64
* win32
* win64

Para información más detallada sobre su funcionamiento, como instalarlo... [ver la Wiki](https://github.com/manumartor/app-compiler-4any-device/wiki)

## Issues ##

Visit the [gitHub issues tracker](https://github.com/manumartor/app-compiler-4any-device/issues).

## Author ##

* Manu Martínez ([http://www.martor.es](http://www.martor.es)): manu.martor@gmail.com

## License ##

Apache 2.0 [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)
