Connecting the Cables
#####################


Connecting the power
====================

.. tabs::

   .. group-tab:: Mirte PCB

      Currently the PCB is only used by ourselves. Instructions can therefore be found in the same (Dutch) `instruction manual <https://surfdrive.surf.nl/files/index.php/s/RULqnIFU7yhXLJZ/download?path=%2F&files=W2%20-%20in%20elkaar%20zetten.pdf>`_.

   .. group-tab:: Breadboard





Connecting the peripherals
==========================

The Mirte PCB is nothing more than just a bunch of cables on a board. You can of
course also connect the same hardware to a breadboard. The fritzing image below 
shows you how to connect all the hardware in order to get the same pin layout
as the PCB. But you are also free to chose different pins and change the 
configuration later on.

.. tabs::

   .. group-tab:: Mirte PCB

      .. tabs::

         .. group-tab:: Motor

            .. |motor1| image:: images/motor_pcb.png
               :width: 49%

            .. |motor2| image:: images/motor.png
               :width: 49%

            |motor1| |motor2|

         .. group-tab:: Servo

            .. |servo1| image:: images/servo_pcb.png
               :width: 49%

            .. |servo2| image:: images/servo.png
               :width: 49%

            |servo1| |servo2|

         .. group-tab:: OLED

            .. |oled1| image:: images/oled_pcb.png
               :width: 49%

            .. |oled2| image:: images/oled.png
               :width: 49%

            |oled1| |oled2|

         .. group-tab:: Line follow

            .. |line1| image:: images/line_pcb.png
               :width: 49%

            .. |line2| image:: images/line.png
               :width: 49%

            |line1| |line2|

         .. group-tab:: Distance

            .. |dist1| image:: images/distance_pcb.png
               :width: 49%

            .. |dist2| image:: images/distance.png
               :width: 49%

            |dist1| |dist2|

   .. group-tab:: Pi Pico

     .. image:: images/full_pico_bb.png
        :width: 600
        :alt: Alternative text

   .. group-tab:: Arduino Nano

     .. image:: images/full_nano_bb.png
       :width: 600
       :alt: Alternative text

     .. note::
       Please note that:

       - The motors are now controlled with one PWM and one digital pin.
       - Two I2C OLED screens are only possible when you have two OLEDS with different addresses (either by default, or soldered).

   .. group-tab:: Arduino Uno

     .. image:: images/full_uno_bb.png
       :width: 600
       :alt: Alternative text

     .. note::
       Please note that:

       - The motors are now controlled with one PWM and one digital pin.
       - Two I2C OLED screens are only possible when you have two OLEDS with different addresses (either by default, or soldered).
       - The digital value of the IR line sensor is not used.
       - The power of all peripherals (or at least the motor controller) needs to come from the breadboard power supply.

   .. group-tab:: STM32

      .. image:: images/full_PCB_bb.png
        :width: 600
        :alt: Alternative text



