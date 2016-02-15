# IoT
if you want the example and source you can get them from here:
git clone git://git.eclipse.org/gitroot/paho/org.eclipse.paho.mqtt.python.git



These scritps use the mqtt protocal to talk to a mqtt broker (test.meqetto.org) using publish and subsrcibe send and receve messeages.

use sub.py to subscribe to data channels
use pub-pi-speed1.py to publish lastest speed test log entry to the /paho/test/pi-speed1 channel
use pub-pi-temp.py to publish lastest pi temperature to the /paho/test/pi-temp channel


I am currently running these in crontab and sending the data to the following channels via the publish functions of the mqtt-python module 
paho/test/pi-speed1
paho/test/pi-temp
 
 test

