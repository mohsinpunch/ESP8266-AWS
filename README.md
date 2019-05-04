# ESP8266 AWS IoT Example

This project shows how to connect your ESP8266 to AWS IoT.

Don't forget to add your certificate and key to the `data` directory
and upload your spiffs (data) folder using the following terminal command:
```
platformio run --target uploadfs
```

For more information, check: http://michaelteeuw.nl

## Warning

This examples uses an insecure SSL connection. Do not use the MQTT connection for sensitive data. Keep in mind that the S in IOT stands for Security. ;)