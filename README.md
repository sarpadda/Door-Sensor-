# Door-Alarm-using-C


The door alarm project has been designed which triggers beeping alarm when it detects motion in the door using the acceleration
sensor on the SJ one board.

The primary SJ one board which act as door alarm is packaged into a box. The SJ
one board inside box is powered using 4 AA cells connected in series providing voltage of 6V to
the board. The same voltage source powers the beeping alarm which is connected to the SJ one
board. The accelerometer on the board is used to detect motion by calibrating its values. When
accelerometer detects motion, it triggers beeping alarm.

There is secondary SJ one board which act as remote control to shut off the alarm. The remote
connects with the primary SJ one board using mesh network topology. When the main door
alarm starts beeping, it can be shut off by pressing reset button on the remote control.
