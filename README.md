# Die Roboter Garage

Die Roboter Garage sind einige kleine Roboter, die über das Internet durch den Maker Space gesteuert werden. Die Roboter selbst basieren auf einem ESP32 mit Kameramodul und 2 Servos. Der Kamerafeed wird auf einen Server gestreamed und dort per OpenCV die Gesichter von Personen entfernt. Danach soll das Video über eine Website angezeigt werden. Von dieser Website aus werden die Kommandos für den Roboter per Websocket an den Bot übertragen.

