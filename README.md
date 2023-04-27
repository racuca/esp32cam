# esp32cam
esp32cam source for camerawebserver and python opencv face detection

execution

1. arduino settings
   - board : ESP32 Wrover Module
   - Upload speed : 512000
   - Flash Frequency: 80MHz
   - Partition Scheme : "Huge APP (3MB No OTA/1MB SPIFFS)"
   
   first download arduino source.
   
2. python opencv
    create virtual env.
    packages to install:
   
   pip install requests
   pip install opencv-python
   pip install opencv-contrib-python

  in test.py 
  URL = "http://<IP address on arduino serial monitor>"
  and run test.py
  
You will see a rectangle on your face.
  
