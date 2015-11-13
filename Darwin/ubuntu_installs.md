Para python GDAL

$ sudo apt-get install libhdf5-7
$ sudo apt-get install libgdal-dev

Con pip tuve que especificar la version para que sea igual a la del sistema
$ gdal-config --version
1.11.0
$pip install pygdal==1.11.0