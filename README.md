# max30100_firebase

*components required* :
                     * A WI_FI module preferably node-MCU(ESP-8232) to act as a micro controller.
                     * MAX-30100 heartbeat and blood oxygen sensor.
                     * connector pins for sensor to micro controller.
                     * breadboard(optional) for  stable readings.

# FIREBASE

->fire base is the basic backbone for most of the android applications present as it provides various services like authentication , realtime database , cloud storage support.
->the sensor readings are sent through the esp module and reaches the firebase account and the values are updated for every second in realtime database.
->make sure that the read and write parameters are turned off in realtime database(if used in locked mode instead of test mode )
