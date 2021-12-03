#	vcosme9-ARDUINO

#	Este documento contiene la parte de Arduino del proyecto 3A de GTI.
#	Se encarga de enviar datos de distintos sensores a la APP de Android, para que
#	luego dichos datos sean añadidos a la bbdd.
	
#	La funcionalidad está virtualmente completa. Solo falta que tome datos reales de los
#	sensores, en lugar de los generados artificialmente.

#	Para probar la aplicación, hay que instalarla en un dispositivo nRF mini. Seguidamente, hay que
#	usar una aplicación de detección de beacons. Si dicha aplicación lee los beacons enviados, y si
#	el nombre de dichos beacons es "vcosme9", entonces funciona correctamente.