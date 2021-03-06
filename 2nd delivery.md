# Second delivery update

## Comments received after the first delivery

The concept idea doesn't solve a real world problem and so it wouldn't be a valuable product.

## Changes done after the first delivery

Based on the feedback received after the first delivery we decided to start from scratch on a new concept idea: a smart signage system to be used inside the marinas.

## Technology update

### Work done up to now

We've developed:
- Firmware for the screen controller
- Firmware for boat detection device
- Cloud software to control devices via MQTT
- Cloud software to assign reservation
- Software for license plate recognition

### Future work
- Improve web interface
- Improve security
- The system have to work also with the boats without a license plate (<10 m).
  We will work on one of these proposals: 
    - QR Code ticket to scan at the entrance
    - Contactless check-in using bluetooth low energy
    - Use the GPS of the user smartphone
- Handle what to do when there isn't a reservation for an entering boat
- Change network connection to a more reliable one (probably LoRa)
- MQTT client for camera devices
## Evaluation update

### Work done up to now
- We measure the power consumption of:
  - The main board with radio module
  - The ultrasonic sensor
- We have tested how the network works with a number of nodes suitable for our proposal
- We have tested the reliability of the ultrasonic rangefinder
- The plate recogntion is working only for simple boats without aditional text near the plate
- We tested the power consumption and the delay in the license plate recognition
- The plate recognition is working slowly

### Future work
- Camera device power consumption
- Estimate the power consumption of the entire system (included brighter LED and real monitors)
- Making a more accurate plate recognition with taking in account cases where the boat is more designed and more writen word are near the plate
- Make the response faster than the first one
