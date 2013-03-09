hadokenIMU
==========

hadokenIMU is an Arduino Leonardo compatible 9DoF inertial measurement unit (IMU) with integrated LiPo battery charger and XBee-style radio 
connector.

The ATMega32U4 microcontroller can be flashed via an ICSP port on the back of the board using pogo pins in the standard 2x3 header, 0.1" spacing.

The IMU uses a MPU-9150 chip for 3-axis accelerometer, gyroscope, and magnetometer data over I2C.

The radio connector is designed for use with Roving Networks RN-XV WiFly modules, and uses the "Bee" footprint made popular by XBee.

Battery power is provided through a 2-pin JST header, standard on many LiPo batteries. A mini USB jack provides power to charge the battery 
and can be used to reprogram the ATMega32U4 chip.

This project is called hadokenIMU because these boards are an integrated design for gesture recognition gloves for Super Street Fire: live 
action Street Fighter 2 in a ring of fire. Wear two gloves, do the iconic move, receive fire - that's what this hardware was originally 
made for.
