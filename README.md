# Coffee Room Dataset

This dataset was collected between 4:42pm 24/07/2017 and 9:50am 31/07/2017 in the Scientific Computing Department's first floor coffee room. It is intended for use in STFC's Summer Coding Week 2017.

It contains sensor measurements at intervals of 5 seconds for the entire period. The left hand column contains the time information as a Unix timestamp, while the right hand column contains the sensor readings. 

The sensors are:
- Humidity (percentage)
- Temperature (degrees centrigrade with an error of ~2%)
- Light Dependent Resistor (Analog reading, but largely meaningless because this sensor had a loose wire: the readings are close to meaningless, but do jump about in an interesting way when someone is in the room)
- Movement (binary reading. 1=movement, 0=no movement)